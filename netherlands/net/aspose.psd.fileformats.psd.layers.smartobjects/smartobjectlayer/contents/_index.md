---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD voor .NET API-referentie
description: SmartObjectLayer eigendom. Haalt de inhoud van de slimme objectlaag op of stelt deze in. De ingesloten inhoud van het slimme object is het ingesloten onbewerkte afbeeldingsbestandData en zijn eigenschappen. De inhoud van het gekoppelde slimme object is de onbewerkte inhoud van het gekoppelde afbeeldingsbestand als het beschikbaar is en zijn eigenschappenLiFeDataSource . We ondersteunen geen laden vanuit de Adobe Photoshop  grafische bibliotheek wanneerIsLibraryLink is waar. Voor gewone linkbestanden gebruiken we in eerste instantieRelativePath om het bestand te zoeken relative ten opzichte van het pad naar de bronafbeeldingSourceImagePath  als het niet beschikbaar is kijken we ernaarFullPath  zo niet dan zoeken we naar het linkbestand in dezelfde map waar onze afbeelding staatSourceImagePath .
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Haalt de inhoud van de slimme objectlaag op of stelt deze in. De ingesloten inhoud van het slimme object is het ingesloten onbewerkte afbeeldingsbestand:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) en zijn eigenschappen. De inhoud van het gekoppelde slimme object is de onbewerkte inhoud van het gekoppelde afbeeldingsbestand als het beschikbaar is en zijn eigenschappen:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . We ondersteunen geen laden vanuit de Adobe� Photoshop� �� grafische bibliotheek wanneer[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) is waar. Voor gewone linkbestanden gebruiken we in eerste instantie[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) om het bestand te zoeken relative ten opzichte van het pad naar de bronafbeeldingSourceImagePath , als het niet beschikbaar is, kijken we ernaar[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , zo niet, dan zoeken we naar het linkbestand in dezelfde map waar onze afbeelding staat:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Eigendoms-waarde

Debyte[] inhoud slimme objectlaag.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| NotSupportedException | Kan geen inhoud ophalen uit de Adobe� Photoshop� �� bibliotheek. |

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

* class [SmartObjectLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* montage [Aspose.PSD](../../../)


