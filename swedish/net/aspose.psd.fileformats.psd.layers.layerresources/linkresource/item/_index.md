---
title: LinkResource.Item
second_title: Aspose.PSD för .NET API-referens
description: LinkResource fast egendom. FårLinkDataSource vid det angivna indexet som är länkdatakällans unika identifierare..
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
## LinkResource indexer

Får[`LinkDataSource`](../../linkdatasource/) vid det angivna indexet som är länkdatakällans unika identifierare..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Indexet som länkdatakällas unika identifierare. |

### Returvärde

Den[`LinkDataSource`](../../linkdatasource/) instans.

### Fastighetsvärde

Den[`LinkDataSource`](../../linkdatasource/) .

### Exempel

Följande kod visar stödet för Embedded Smart-objekt.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Det här exemplet visar hur man ändrar det smarta objektlagret i PSD-filen och exporterar / uppdaterar det ursprungliga inbäddade innehållet för smarta objekt.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Låt oss exportera den inbäddade smarta objektbilden från PSD-smarta objektlagret
        smartObjectLayer.ExportContents(exportPath);

        // Låt oss kontrollera om originalbilden är korrekt sparad
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Låt oss invertera den ursprungliga smarta objektbilden
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Låt oss ersätta den inbäddade smarta objektbilden i PSD-lagret
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Låt oss kontrollera om den uppdaterade bilden sparas korrekt
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../linkresource/)
* hopsättning [Aspose.PSD](../../../)


