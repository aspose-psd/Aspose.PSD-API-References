---
title: "SmartObjectLayer.DuplicateLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "SmartObjectLayer‑metod. Skapar ett nytt smart objekt‑lager genom att kopiera detta. Observera att för inbäddade smarta objekt delas den inbäddade bilden. Om du vill kopiera den inbäddade bilden, använd metoden NewSmartObjectViaCopy."
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
{{< psd/tize >}}
## SmartObjectLayer.DuplicateLayer method

Skapar ett nytt smart objekt‑lager genom att kopiera detta. Observera att för inbäddade smarta objekt delas den inbäddade bilden. Om du vill kopiera den inbäddade bilden, använd metoden [`NewSmartObjectViaCopy`](../newsmartobjectviacopy/).

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Returvärde

Den klonade [`SmartObjectLayer`](../)‑instansen.

## Exempel

Dessa exempel visar hur man kopierar smartobjektlager i en PSD‑bild.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Dessa exempel visar hur man kopierar smartobjektlager i en PSD‑bild.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
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
            // Låt oss invertera den inbäddade smartobjektbilden (för en inre PSD‑bild inverterar vi bara dess första lager).
            InvertImage(innerImage);

            // Låt oss ersätta den inbäddade smarta objektbilden i PSD-lagret
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Det duplicerade lagret delar sin inbäddade bild med det ursprungliga smartobjektet.
        // och det bör uppdateras explicit, annars förblir dess renderingscache oförändrad.
        // Vi uppdaterar varje smartobjekt för att säkerställa att det nya lagret som skapats av NewSmartObjectViaCopy
        // inte delar den inbäddade bilden med de andra.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Inverterar rasterbilden inklusive PSD‑bilden.
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


