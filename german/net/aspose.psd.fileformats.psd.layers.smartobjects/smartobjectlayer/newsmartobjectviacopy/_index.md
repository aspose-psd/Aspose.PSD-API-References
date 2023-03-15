---
title: SmartObjectLayer.NewSmartObjectViaCopy
second_title: Aspose.PSD für .NET-API-Referenz
description: SmartObjectLayer methode. Erstellt eine neue SmartObjektEbene durch Kopieren dieser Ebene. Reproduziert die Funktionalität Ebene  SmartObjekte  Neues SmartObjekt über Kopieren von Adobe Photoshop. Beachten Sie dass dies aufgrund des eingebetteten Bildes nur für eingebettete SmartObjekte aktiviert ist wird ebenfalls kopiert. Wenn Sie das eingebettete Bild teilen möchten verwenden Sie esDuplicateLayer Methode.
type: docs
weight: 120
url: /de/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/
---
## SmartObjectLayer.NewSmartObjectViaCopy method

Erstellt eine neue Smart-Objekt-Ebene durch Kopieren dieser Ebene. Reproduziert die Funktionalität „Ebene -&gt; Smart-Objekte -&gt; Neues Smart-Objekt über Kopieren“ von Adobe� Photoshop�. Beachten Sie, dass dies aufgrund des eingebetteten Bildes nur für eingebettete Smart-Objekte aktiviert ist wird ebenfalls kopiert. Wenn Sie das eingebettete Bild teilen möchten, verwenden Sie es[`DuplicateLayer`](../duplicatelayer/) Methode.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy()
```

### Rückgabewert

Der geklonte[`SmartObjectLayer`](../) Beispiel.

### Beispiele

Diese Beispiele zeigen, wie Sie Smart-Objekt-Ebenen in ein PSD-Bild kopieren.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Diese Beispiele zeigen, wie man Smart-Objekt-Ebenen in ein PSD-Bild kopiert.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Die zu kopierende Schichtnummer
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
            // Lassen Sie uns das eingebettete Smart-Objekt-Bild invertieren (für ein inneres PSD-Bild invertieren wir nur die erste Ebene)
            InvertImage(innerImage);

            // Lassen Sie uns das eingebettete Smart-Objekt-Bild in der PSD-Ebene ersetzen
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Die duplizierte Ebene teilt ihr eingebettetes Bild mit dem ursprünglichen Smart-Objekt
        // und es sollte explizit aktualisiert werden, sonst bleibt sein Rendering-Cache unverändert.
        // Wir aktualisieren jedes Smart-Objekt, um sicherzustellen, dass die neue Ebene, die von NewSmartObjectViaCopy
        // teilt das eingebettete Bild nicht mit den anderen.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Invertiert das Rasterbild einschließlich des PSD-Bildes.
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

* class [SmartObjectLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* Montage [Aspose.PSD](../../../)


