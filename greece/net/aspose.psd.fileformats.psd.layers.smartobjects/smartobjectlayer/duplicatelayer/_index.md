---
title: "SmartObjectLayer.DuplicateLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "SmartObjectLayer μέθοδος. Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιγράφοντας αυτό το τρέχον. Σημειώστε ότι για ενσωματωμένα έξυπνα αντικείμενα η ενσωματωμένη εικόνα μοιράζεται. Εάν θέλετε να αντιγράψετε την ενσωματωμένη εικόνα, χρησιμοποιήστε τη μέθοδο NewSmartObjectViaCopy."
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
{{< psd/tize >}}
## SmartObjectLayer.DuplicateLayer method

Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιγράφοντας αυτό. Σημειώστε ότι για ενσωματωμένα έξυπνα αντικείμενα η ενσωματωμένη εικόνα είναι κοινόχρηστη. Εάν θέλετε να αντιγράψετε την ενσωματωμένη εικόνα, χρησιμοποιήστε τη μέθοδο [`NewSmartObjectViaCopy`](../newsmartobjectviacopy/).

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Τιμή Επιστροφής

Το κλωνοποιημένο [`SmartObjectLayer`](../) αντίγραφο.

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να αντιγράψετε επίπεδα έξυπνων αντικειμένων σε μια εικόνα PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Αυτά τα παραδείγματα δείχνουν πώς να αντιγράψετε επίπεδα έξυπνων αντικειμένων σε μια εικόνα PSD.
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
            // Ας αντιστρέψουμε την ενσωματωμένη εικόνα έξυπνου αντικειμένου (για μια εσωτερική εικόνα PSD αντιστρέφουμε μόνο το πρώτο της επίπεδο)
            InvertImage(innerImage);

            // Ας αντικαταστήσουμε την ενσωματωμένη εικόνα smart object στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Το αντιγραμμένο επίπεδο μοιράζεται την ενσωματωμένη εικόνα του με το αρχικό έξυπνο αντικείμενο.
        // και πρέπει να ενημερωθεί ρητά, διαφορετικά η προσωρινή μνήμη απόδοσής του παραμένει αμετάβλητη.
        // Ενημερώνουμε κάθε έξυπνο αντικείμενο για να διασφαλίσουμε ότι το νέο επίπεδο που δημιουργείται από το NewSmartObjectViaCopy
        // δεν μοιράζεται την ενσωματωμένη εικόνα με τα άλλα.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Αντιστρέφει την ραστερ εικόνα, συμπεριλαμβανομένης της εικόνας PSD.
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

// Αναστρέφει την raster εικόνα.
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

### Δείτε επίσης

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


