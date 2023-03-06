---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: Aspose.PSD för .NET API-referens
description: SmartObjectLayer metod. Skapar ett nytt smart objektlager genom att kopiera detta. Återskapar funktionen Layer  Smart Objects  New Smart Object via Copy i Adobe Photoshop. Observera att det endast är aktiverat för inbäddade smarta objekt eftersom den inbäddade bilden kopieras också. Om du vill dela den inbäddade bilden användDuplicateLayer metod.
type: docs
weight: 120
url: /sv/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

Skapar ett nytt smart objektlager genom att kopiera detta. Återskapar funktionen `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` i Adobe� Photoshop�. Observera att det endast är aktiverat för inbäddade smarta objekt eftersom den inbäddade bilden kopieras också. Om du vill dela den inbäddade bilden använd[`DuplicateLayer`](../duplicatelayer/) metod.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Returvärde

Den klonade[`SmartObjectLayer`](../) exempel.

### Exempel

Dessa exempel visar hur man kopierar smarta objektlager i en PSD-bild.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Dessa exempel visar hur man kopierar smarta objektlager i en PSD-bild.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Lagernumret som ska kopieras
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
            // Låt oss invertera den inbäddade smarta objektbilden (för en inre PSD-bild inverterar vi bara dess första lager)
            InvertImage(innerImage);

            // Låt oss ersätta den inbäddade smarta objektbilden i PSD-lagret
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Det duplicerade lagret delar sin inbäddade bild med det ursprungliga smarta objektet
        // och den bör uppdateras explicit, annars förblir dess renderingscache oförändrad.
        // Vi uppdaterar varje smart objekt för att se till att det nya lagret skapat av NewSmartObjectViaCopy
        // delar inte den inbäddade bilden med de andra.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Inverterar rasterbilden inklusive PSD-bilden.
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

// Inverterar rasterbilden.
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

### Se även

* class [SmartObjectLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* hopsättning [Aspose.PSD](../../../)


