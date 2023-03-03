---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: Referencia de API de Aspose.PSD para .NET
description: SmartObjectLayer método. Crea una nueva capa de objeto inteligente copiando esta. Reproduce la funcionalidad Capa  Objetos inteligentes  Nuevo objeto inteligente a través de la copia de Adobe Photoshop. Tenga en cuenta que está habilitado solo para objetos inteligentes incrustados porque la imagen incrustada también se copia. Si desea compartir la imagen incrustada useDuplicateLayer método.
type: docs
weight: 120
url: /es/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

Crea una nueva capa de objeto inteligente copiando esta. Reproduce la funcionalidad `Capa -&gt; Objetos inteligentes -&gt; Nuevo objeto inteligente a través de la copia` de Adobe� Photoshop�. Tenga en cuenta que está habilitado solo para objetos inteligentes incrustados porque la imagen incrustada también se copia. Si desea compartir la imagen incrustada, use[`DuplicateLayer`](../duplicatelayer/) método.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Valor_devuelto

el clonado[`SmartObjectLayer`](../) instancia.

### Ejemplos

Estos ejemplos demuestran cómo copiar capas de objetos inteligentes en una imagen PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Estos ejemplos demuestran cómo copiar capas de objetos inteligentes en una imagen PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // El número de capa a copiar
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
            // Invirtamos la imagen del objeto inteligente incrustado (para una imagen PSD interna, invertimos solo su primera capa)
            InvertImage(innerImage);

            // Reemplacemos la imagen del objeto inteligente incrustado en la capa PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // La capa duplicada comparte su imagen incrustada con el objeto inteligente original
        // y debe actualizarse explícitamente; de lo contrario, su caché de representación permanece sin cambios.
        // Actualizamos cada objeto inteligente para asegurarnos de que la nueva capa creada por NewSmartObjectViaCopy
        // no comparte la imagen incrustada con los demás.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Invierte la imagen raster incluyendo la imagen PSD.
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

// Invierte la imagen ráster.
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

### Ver también

* class [SmartObjectLayer](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* asamblea [Aspose.PSD](../../../)


