---
title: SmartObjectProvider.NewSmartObjectViaCopy
second_title: Aspose.PSD voor .NET API-referentie
description: SmartObjectProvider methode. Maakt een nieuwe slimme objectlaag door de bronlaag te kopiëren.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
## SmartObjectProvider.NewSmartObjectViaCopy method

Maakt een nieuwe slimme objectlaag door de bronlaag te kopiëren.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | De bronlaag. |

### Winstwaarde

De gekloonde[`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instantie.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | U kunt alleen een ingesloten slim object vervangen. |

### Voorbeelden

Deze voorbeelden laten zien hoe u slimme objectlagen kopieert in een PSD-afbeelding.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Deze voorbeelden laten zien hoe u slimme objectlagen kopieert in een PSD-afbeelding.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Het nummer van de laag om te kopiëren
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // Laten we de ingebedde afbeelding van het slimme object omkeren (voor een binnenste PSD-afbeelding keren we alleen de eerste laag om)
            InvertImage(innerImage);

            // Laten we de ingesloten slimme objectafbeelding in de PSD-laag vervangen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // De gedupliceerde laag deelt zijn ingebedde afbeelding met het originele slimme object
        // en het moet expliciet worden bijgewerkt, anders blijft de renderingcache ongewijzigd.
        // We werken elk slim object bij om ervoor te zorgen dat de nieuwe laag gemaakt door NewSmartObjectViaCopy
        // deelt de ingesloten afbeelding niet met de anderen.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Keert de rasterafbeelding inclusief de PSD-afbeelding om.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// Keert de rasterafbeelding om.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### Zie ook

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* montage [Aspose.PSD](../../../)


