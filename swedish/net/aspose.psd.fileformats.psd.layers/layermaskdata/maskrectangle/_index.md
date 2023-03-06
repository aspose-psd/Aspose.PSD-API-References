---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD för .NET API-referens
description: LayerMaskData fast egendom. Hämtar eller ställer in maskenRectangleav lagermasken i PSDfilen. Den tar egenskaper för vänster höger topp och botten och skaparRectangle
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Hämtar eller ställer in masken[`Rectangle`](../../../aspose.psd/rectangle/)av lagermasken i PSD-filen. Den tar egenskaper för vänster, höger, topp och botten och skapar[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Fastighetsvärde

Maskrektangeln.

### Exempel

Det här exemplet visar hur du hämtar, uppdaterar, tar bort och lägger till rasterlagermasker i Adobe® Photoshop®-filen programmatiskt.

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

// Får int-värdet omvandlat till big-endian byte-ordning.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Får värdet omvandlat från big endian till Int32.
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

// Får en rastermask från lagret i en PSD-bild och sparar den i en fil
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

// Lägger till en rastermask från filen till lagret och sparar den i PSD-formatbilden
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

    // Att bara lägga till LayerMaskData är inte tillräckligt för att spara korrekt eftersom kanaler inte uppdateras;
    // layer.LayerMaskData = mask; // Detta lägger inte till maskkanalen

    // Lägg till (eller uppdatera) masken
    layer.AddLayerMask(maskData); // Men detta lägger till / uppdaterar både masken och kanalerna!
}

// Det här exemplet visar hur du hämtar, uppdaterar, tar bort och lägger till rasterlagermasker i Adobe® Photoshop®-filen programmatiskt.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Hämta en rastermask från lagret och spara den i en fil
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Ändra lagermasken (invertera) och spara bilden
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Bara att ändra LayerMaskData är tillräckligt för att åstadkomma rendering
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Men att bara ändra LayerMaskData är inte tillräckligt för att spara korrekt eftersom kanaler inte uppdateras;
    layer.LayerMaskData = mask; // Det här fungerar inte heller
    layer.AddLayerMask(mask); // Men detta uppdaterar både masken och kanalerna!
    image.Save("FourWithMasksUpdated2.psd");

    // Ta bort en rastermask från lagret och spara bilden
    layer.LayerMaskData = null; // Att bara ta bort LayerMaskData räcker för att utföra rendering men inte för att spara till PSD-format
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Men detta tar bort både masken och maskkanalen!
    image.Save("FourWithMasksRemoved2.psd");

    // Lägg till en rastermask från filen till lagret och spara bilden
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Se även

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* hopsättning [Aspose.PSD](../../../)


