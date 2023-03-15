---
title: SmartObjectLayer.DuplicateLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: SmartObjectLayer méthode. Crée un nouveau calque dobjet intelligent en copiant celuici. Notez que pour les objets intelligents intégrés limage intégrée est partagée. Si vous souhaitez copier limage intégrée utilisezNewSmartObjectViaCopy méthode.
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
## SmartObjectLayer.DuplicateLayer method

Crée un nouveau calque d'objet intelligent en copiant celui-ci. Notez que pour les objets intelligents intégrés, l'image intégrée est partagée. Si vous souhaitez copier l'image intégrée, utilisez[`NewSmartObjectViaCopy`](../newsmartobjectviacopy/) méthode.

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Return_Value

Le cloné[`SmartObjectLayer`](../) instance.

### Exemples

Ces exemples montrent comment copier des calques d'objets intelligents dans une image PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Ces exemples montrent comment copier des calques d'objets intelligents dans une image PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Le numéro du calque à copier
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
            // Inversons l'image de l'objet intelligent intégré (pour une image PSD interne, nous inversons uniquement sa première couche)
            InvertImage(innerImage);

            // Remplaçons l'image de l'objet intelligent intégré dans la couche PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Le calque dupliqué partage son image intégrée avec l'objet intelligent d'origine
        // et il doit être mis à jour explicitement sinon son cache de rendu reste inchangé.
        // Nous mettons à jour chaque objet intelligent pour nous assurer que le nouveau calque créé par NewSmartObjectViaCopy
        // ne partage pas l'image intégrée avec les autres.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Inverse l'image raster, y compris l'image PSD.
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

// Inverse l'image raster.
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

### Voir également

* class [SmartObjectLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* Assemblée [Aspose.PSD](../../../)


