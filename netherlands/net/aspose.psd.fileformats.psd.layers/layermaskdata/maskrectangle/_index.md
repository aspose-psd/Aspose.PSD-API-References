---
title: LayerMaskData.MaskRectangle
second_title: Aspose.PSD voor .NET API-referentie
description: LayerMaskData eigendom. Krijgt of stelt het masker inRectanglevan het laagmasker in het PSDbestand. Het neemt de eigenschappen links rechts boven en onder en maaktRectangle
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

Krijgt of stelt het masker in[`Rectangle`](../../../aspose.psd/rectangle/)van het laagmasker in het PSD-bestand. Het neemt de eigenschappen links, rechts, boven en onder en maakt[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### Eigendoms-waarde

De maskerrechthoek.

### Voorbeelden

Dit voorbeeld laat zien hoe u rasterlaagmaskers in het Adobe® Photoshop®-bestand programmatisch kunt ophalen, bijwerken, verwijderen en toevoegen.

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

// Krijgt de int-waarde geconverteerd naar big-endian bytes-volgorde.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// Krijgt de waarde geconverteerd van de big endian naar Int32.
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

// Haalt een rastermasker op uit de laag van een PSD-afbeelding en slaat het op in een bestand
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

// Voegt een rastermasker uit het bestand toe aan de laag en slaat het op in de PSD-indeling
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

    // Alleen het toevoegen van LayerMaskData is niet voldoende voor correct opslaan, omdat kanalen niet worden bijgewerkt;
    // laag.LayerMaskData = masker; // Hiermee wordt het maskerkanaal niet toegevoegd

    // Voeg het masker toe (of werk het bij).
    layer.AddLayerMask(maskData); // Maar dit voegt zowel het masker als de kanalen toe / werkt het bij!
}

// Dit voorbeeld laat zien hoe u rasterlaagmaskers in het Adobe® Photoshop®-bestand programmatisch kunt ophalen, bijwerken, verwijderen en toevoegen.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // Haal een rastermasker uit de laag en sla het op in een bestand
    SaveRasterMask("FourWithMasks2.msk", layer);

    // Wijzig het laagmasker (omkeren) en sla de afbeelding op
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // Gewoon LayerMaskData wijzigen is voldoende om weergave te bewerkstelligen
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // Maar alleen het wijzigen van LayerMaskData is niet voldoende voor correct opslaan, omdat kanalen niet worden bijgewerkt;
    layer.LayerMaskData = mask; // Dit werkt ook niet
    layer.AddLayerMask(mask); // Maar dit werkt zowel het masker als de kanalen bij!
    image.Save("FourWithMasksUpdated2.psd");

    // Verwijder een rastermasker uit de laag en sla de afbeelding op
    layer.LayerMaskData = null; // Gewoon LayerMaskData verwijderen is voldoende om weergave te bewerkstelligen, maar niet om op te slaan in PSD-indeling
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // Maar dit verwijdert zowel het masker als het maskerkanaal!
    image.Save("FourWithMasksRemoved2.psd");

    // Voeg een rastermasker uit het bestand toe aan de laag en sla de afbeelding op
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### Zie ook

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* montage [Aspose.PSD](../../../)


