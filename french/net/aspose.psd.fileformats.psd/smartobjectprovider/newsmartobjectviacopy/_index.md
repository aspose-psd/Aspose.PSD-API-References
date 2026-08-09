---
title: "SmartObjectProvider.NewSmartObjectViaCopy"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode SmartObjectProvider. Crée un nouveau calque d'objet intelligent en copiant la source"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectProvider.NewSmartObjectViaCopy method

Crée un nouveau calque d'objet intelligent en copiant celui source.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | La couche source. |

### Valeur de retour

L'instance clonée [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Vous ne pouvez remplacer qu'un objet intelligent intégré. |

## Exemples

Ces exemples montrent comment copier des calques d'objet dynamique dans une image PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Ces exemples montrent comment copier des calques d'objet dynamique dans une image PSD.
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
            // Inversons l'image d'objet dynamique intégré (pour une image PSD interne, nous n'invertissons que son premier calque).
            InvertImage(innerImage);

            // Remplaçons l'image d'objet dynamique intégré dans le calque PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Le calque dupliqué partage son image intégrée avec l'objet dynamique original
        // et il doit être mis à jour explicitement, sinon son cache de rendu reste inchangé.
        // Nous mettons à jour chaque objet dynamique pour nous assurer que le nouveau calque créé par NewSmartObjectViaCopy
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

### Voir aussi

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


