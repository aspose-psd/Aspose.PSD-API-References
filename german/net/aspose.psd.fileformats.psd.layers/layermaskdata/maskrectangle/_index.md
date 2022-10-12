---
title: MaskRectangle
second_title: Aspose.PSD für .NET-API-Referenz
description: Holt oder setzt die MaskeRectangleaspose.psd/rectangleder Ebenenmaske in der PSDDatei. Es nimmt linke rechte obere und untere Eigenschaften und erstelltRectangleaspose.psd/rectangle
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Holt oder setzt die Maske[`Rectangle`](../../../aspose.psd/rectangle)der Ebenenmaske in der PSD-Datei. Es nimmt linke, rechte, obere und untere Eigenschaften und erstellt[`Rectangle`](../../../aspose.psd/rectangle)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Eigentumswert

Das Maskenrechteck.

### Beispiele

Dieses Beispiel zeigt, wie Rasterebenenmasken in der Adobe® Photoshop®-Datei programmgesteuert abgerufen, aktualisiert, entfernt und hinzugefügt werden.

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

string dataDir = "PSDNET640_1" + Path.DirectorySeparatorChar;

// Ruft den int-Wert konvertiert in Big-Endian-Byte-Reihenfolge ab.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Ruft den von Big Endian in Int32 konvertierten Wert ab.
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

// Ruft eine Rastermaske aus der Ebene eines PSD-Bildes ab und speichert sie in einer Datei
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

// Fügt der Ebene eine Rastermaske aus der Datei hinzu und speichert sie als Bild im PSD-Format
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

    // Das Hinzufügen von LayerMaskData reicht nicht aus, um korrekt zu speichern, da die Kanäle nicht aktualisiert werden;
    // Schicht.LayerMaskData = Maske; // Dies fügt den Maskenkanal nicht hinzu

    // Maske hinzufügen (oder aktualisieren).
    layer.AddLayerMask(maskData); // Aber dies fügt / aktualisiert sowohl die Maske als auch die Kanäle!
}

// Dieses Beispiel zeigt, wie Rasterebenenmasken in der Adobe® Photoshop®-Datei programmgesteuert abgerufen, aktualisiert, entfernt und hinzugefügt werden.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
Directory.CreateDirectory(dataDir);
var sourceFilePath = dataDir + "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Holen Sie sich eine Rastermaske aus der Ebene und speichern Sie sie in einer Datei
    SaveRasterMask(dataDir + "FourWithMasks2.msk", layer);

    // Ändern Sie die Ebenenmaske (invertieren) und speichern Sie das Bild
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Das Ändern von LayerMaskData reicht aus, um das Rendern zu bewirken
    image.Save(dataDir + "FourWithMasksUpdated2.png", pngOptions);

    // Aber das Ändern von LayerMaskData reicht nicht aus, um korrekt zu speichern, da die Kanäle nicht aktualisiert werden;
    layer.LayerMaskData = mask; // Das funktioniert auch nicht
    layer.AddLayerMask(mask); // Aber das aktualisiert sowohl die Maske als auch die Kanäle!
    image.Save(dataDir + "FourWithMasksUpdated2.psd");

    // Entferne eine Rastermaske aus der Ebene und speichere das Bild
    layer.LayerMaskData = null; // Nur das Entfernen von LayerMaskData reicht aus, um das Rendern zu bewirken, aber nicht zum Speichern im PSD-Format
    image.Save(dataDir + "FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Aber das entfernt sowohl die Maske als auch den Maskenkanal!
    image.Save(dataDir + "FourWithMasksRemoved2.psd");

    // Fügen Sie der Ebene eine Rastermaske aus der Datei hinzu und speichern Sie das Bild
    AddRasterMask(layer, dataDir + "raster.msk");
    image.Save(dataDir + "FourWithMasksAdded2.png", pngOptions);
    image.Save(dataDir + "FourWithMasksAdded2.psd");
}
```

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle)
* class [LayerMaskData](../../layermaskdata)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata)
* Montage [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
