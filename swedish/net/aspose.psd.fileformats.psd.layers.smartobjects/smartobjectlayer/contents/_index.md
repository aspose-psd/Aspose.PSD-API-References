---
title: "SmartObjectLayer.Contents"
second_title: "Aspose.PSD för .NET API‑referens"
description: "SmartObjectLayer‑egenskap. Hämtar eller anger innehållet i smart objekt‑lagret. Det inbäddade smarta objektets innehåll är den inbäddade råa bildfilen Data och dess egenskaper. Det länkade smarta objektets innehåll är den råa innehållet i den länkade bildfilen om den är tillgänglig samt dess egenskaper LiFeDataSource. Vi stödjer inte inläsning från Adobe Photoshop Graphics Library när IsLibraryLink är true. För vanliga länkfiler använder vi först RelativePath för att söka efter filen relativt till källbildens sökväg SourceImagePath; om den inte är tillgänglig tittar vi på FullPath; om inte, letar vi efter länkfilen i samma katalog där vår bild finns SourceImagePath"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

Hämtar eller anger innehållet i smartobjektslagret. Det inbäddade smartobjektets innehåll är den inbäddade råa bildfilen: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) och dess egenskaper. Det länkade smartobjektets innehåll är det råa innehållet i den länkade bildfilen om den är tillgänglig samt dess egenskaper: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Vi stöder inte inläsning från Adobe� Photoshop� �� Graphics Library när [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) är sant. För vanliga länkar använder vi först [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) för att söka efter filen relativt till källbildens sökväg SourceImagePath; om den inte är tillgänglig söker vi på [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), och om inte det letar vi efter länken i samma katalog som vår bild finns: SourceImagePath.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

Byte[]-smartobjektlagrets innehåll.

### Undantag

| undantag | villkor |
| --- | --- |
| NotSupportedException | Kan inte hämta innehåll från Adobe� Photoshop� ��-biblioteket. |

## Exempel

Följande kod demonstrerar stöd för inbäddade smarta objekt.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Detta exempel visar hur man ändrar smarta objektlagret i PSD-filen och exporterar/uppdaterar smarta objektets ursprungliga inbäddade innehåll.
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

        // Låt oss exportera den inbäddade smarta objektbilden från PSD:s smarta objektlager
        smartObjectLayer.ExportContents(exportPath);

        // Låt oss kontrollera om den ursprungliga bilden har sparats korrekt
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

        // Låt oss kontrollera om den uppdaterade bilden har sparats korrekt
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


