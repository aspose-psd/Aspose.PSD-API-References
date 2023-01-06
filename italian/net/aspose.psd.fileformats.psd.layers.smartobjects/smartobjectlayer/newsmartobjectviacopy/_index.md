---
title: NewSmartObjectViaCopy
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Crea un nuovo livello di oggetti intelligenti copiando questo. Riproduce la funzionalità Livello gt Oggetti avanzati gt Nuovo oggetto avanzato tramite copia di Adobe Photoshop. Si noti che è abilitato solo per gli oggetti intelligenti incorporati perché limmagine incorporata viene anche copiato. Se si desidera condividere limmagine incorporata utilizzareDuplicateLayeraspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer metodo.
type: docs
weight: 120
url: /it/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

Crea un nuovo livello di oggetti intelligenti copiando questo. Riproduce la funzionalità `Livello -&gt; Oggetti avanzati -&gt; Nuovo oggetto avanzato tramite copia` di Adobe� Photoshop�. Si noti che è abilitato solo per gli oggetti intelligenti incorporati perché l'immagine incorporata viene anche copiato. Se si desidera condividere l'immagine incorporata, utilizzare[`DuplicateLayer`](../duplicatelayer) metodo.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Valore di ritorno

Il clonato[`SmartObjectLayer`](../../smartobjectlayer) esempio.

### Esempi

Questi esempi mostrano come copiare i livelli di oggetti intelligenti in un'immagine PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Questi esempi mostrano come copiare i livelli di oggetti intelligenti in un'immagine PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Il numero del livello da copiare
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
            // Invertiamo l'immagine dell'oggetto intelligente incorporato (per un'immagine PSD interna invertiamo solo il suo primo livello)
            InvertImage(innerImage);

            // Sostituiamo l'immagine dell'oggetto intelligente incorporato nel livello PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Il livello duplicato condivide la sua immagine incorporata con l'oggetto intelligente originale
        // e dovrebbe essere aggiornato esplicitamente altrimenti la sua cache di rendering rimane invariata.
        // Aggiorniamo ogni oggetto intelligente per assicurarci che il nuovo livello creato da NewSmartObjectViaCopy
        // non condivide l'immagine incorporata con gli altri.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Inverte l'immagine raster inclusa l'immagine PSD.
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

// Inverte l'immagine raster.
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

### Guarda anche

* class [SmartObjectLayer](../../smartobjectlayer)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
