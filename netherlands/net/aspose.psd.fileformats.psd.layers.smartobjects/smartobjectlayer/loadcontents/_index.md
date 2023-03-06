---
title: SmartObjectLayer.LoadContents
second_title: Aspose.PSD voor .NET API-referentie
description: SmartObjectLayer methode. Haalt de ingesloten of gekoppelde afbeeldingsinhoud op van de slimme objectlaag.
type: docs
weight: 110
url: /nl/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/
---
## SmartObjectLayer.LoadContents method

Haalt de ingesloten of gekoppelde afbeeldingsinhoud op van de slimme objectlaag.

```csharp
public Image LoadContents(LoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | LoadOptions | De opties. |

### Winstwaarde

De geladen[`Image`](../../../aspose.psd/image/) slimme objectinstantie.

### Voorbeelden

De volgende code demonstreert de ondersteuning van Embedded Smart-objecten.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Dit voorbeeld laat zien hoe u de slimme objectlaag in het PSD-bestand kunt wijzigen en de originele ingesloten inhoud van het slimme object kunt exporteren/bijwerken.
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

        // Laten we de ingebedde slimme objectafbeelding exporteren vanuit de PSD slimme objectlaag
        smartObjectLayer.ExportContents(exportPath);

        // Laten we eens kijken of de originele afbeelding correct is opgeslagen
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Laten we de originele afbeelding van een slim object omkeren
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Laten we de ingesloten slimme objectafbeelding in de PSD-laag vervangen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Laten we eens kijken of de bijgewerkte afbeelding correct is opgeslagen
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Zie ook

* class [Image](../../../aspose.psd/image/)
* class [LoadOptions](../../../aspose.psd/loadoptions/)
* class [SmartObjectLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* montage [Aspose.PSD](../../../)


