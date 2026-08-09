---
title: "LayerMaskData.MaskRectangle"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerMaskData-Eigenschaft. Gibt oder setzt das Masken‑Rectangle der Ebenenmaske in der PSD‑Datei. Sie nimmt die Eigenschaften links, rechts, oben und unten und erstellt ein Rectangle."
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
{{< psd/tize >}}
## LayerMaskData.MaskRectangle property

Gibt oder setzt das Masken[`Rectangle`](../../../aspose.psd/rectangle/) der Ebenenmaske in der PSD‑Datei. Sie nimmt die Eigenschaften links, rechts, oben und unten und erstellt ein [`Rectangle`](../../../aspose.psd/rectangle/).

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Property Value

Das Masken‑Rectangle.

## Beispiele

Dieses Beispiel zeigt, wie man Raster‑Ebenenmasken in der Adobe® Photoshop®‑Datei programmgesteuert abruft, aktualisiert, entfernt und hinzufügt.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Gibt den int‑Wert zurück, der in die Big‑Endian‑Byte‑Reihenfolge konvertiert wurde.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Gibt den Wert zurück, der vom Big‑Endian in Int32 konvertiert wurde.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// Ruft eine Rastermaske aus der Ebene eines PSD‑Bildes ab und speichert sie in einer Datei.
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// Fügt eine Rastermaske aus der Datei zur Ebene hinzu und speichert das Bild im PSD‑Format.
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // Nur das Hinzufügen von LayerMaskData reicht für ein korrektes Speichern nicht aus, weil die Kanäle nicht aktualisiert werden;
    // layer.LayerMaskData = mask; // Dies fügt den Maskenkanal nicht hinzu

    // Maske hinzufügen (oder aktualisieren)
    layer.AddLayerMask(maskData); // But this adds / updates both the mask and channels!
}

// Dieses Beispiel zeigt, wie man Raster‑Ebenenmasken in der Adobe® Photoshop®‑Datei programmgesteuert abruft, aktualisiert, entfernt und hinzufügt.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Rastermaske aus der Ebene holen und in einer Datei speichern
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Ebenenmaske ändern (invertieren) und das Bild speichern
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Einfaches Ändern von LayerMaskData reicht aus, um das Rendering zu bewirken
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Aber das bloße Ändern von LayerMaskData reicht nicht für korrektes Speichern, weil die Kanäle nicht aktualisiert werden;
    layer.LayerMaskData = mask; // This does not work either
    layer.AddLayerMask(mask); // But this updates both the mask and channels!
    image.Save("FourWithMasksUpdated2.psd");

    // Rastermaske aus der Ebene entfernen und das Bild speichern
    layer.LayerMaskData = null; // Just removing LayerMaskData is enough to effect rendering but not for saving to PSD format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // But this removes both the mask and the mask channel!
    image.Save("FourWithMasksRemoved2.psd");

    // Rastermaske aus der Datei zur Ebene hinzufügen und das Bild speichern
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


