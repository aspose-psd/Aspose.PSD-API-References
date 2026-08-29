---
title: "SmartObjectProvider.NewSmartObjectViaCopy"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "SmartObjectProvider-Methode. Erstellt eine neue Smart‑Object‑Ebene, indem die Quell‑Ebene kopiert wird."
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
{{< psd/tize >}}
## SmartObjectProvider.NewSmartObjectViaCopy method

Erstellt eine neue Smart-Object-Ebene, indem die Quell-Ebene kopiert wird.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | Die Quell‑Ebene. |

### Rückgabewert

Die geklonte [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Sie können nur ein eingebettetes Smart Object ersetzen. |

## Beispiele

Diese Beispiele zeigen, wie man Smart Object Layers in einem PSD-Bild kopiert.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Diese Beispiele zeigen, wie man Smart Object Layers in einem PSD-Bild kopiert.
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
            // Lassen Sie das eingebettete Smart Object Bild invertieren (bei einem inneren PSD-Bild invertieren wir nur dessen erste Ebene).
            InvertImage(innerImage);

            // Lassen Sie das eingebettete Smart‑Object‑Bild in der PSD‑Ebene ersetzen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Der duplizierte Layer teilt sein eingebettetes Bild mit dem ursprünglichen Smart Object.
        // und er sollte explizit aktualisiert werden, sonst bleibt sein Rendering-Cache unverändert.
        // Wir aktualisieren jedes Smart‑Object, um sicherzustellen, dass die neue Ebene, die durch NewSmartObjectViaCopy erstellt wird
        // teilt das eingebettete Bild nicht mit den anderen.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Invertiert das Rasterbild einschließlich des PSD‑Bildes.
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

// Invertiert das Rasterbild.
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

### Siehe auch

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


