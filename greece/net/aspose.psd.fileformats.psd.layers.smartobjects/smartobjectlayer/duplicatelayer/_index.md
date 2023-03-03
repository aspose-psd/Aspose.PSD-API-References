---
title: SmartObjectLayer.DuplicateLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: SmartObjectLayer μέθοδος. Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιμετωπίζοντας αυτό. Παρατηρήστε ότι για τα ενσωματωμένα έξυπνα αντικείμενα η ενσωματωμένη εικόνα είναι κοινόχρηστη. Εάν θέλετε να αντιγράψετε την ενσωματωμένη εικόνα χρησιμοποιήστεNewSmartObjectViaCopy μέθοδος.
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
## SmartObjectLayer.DuplicateLayer method

Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιμετωπίζοντας αυτό. Παρατηρήστε ότι για τα ενσωματωμένα έξυπνα αντικείμενα η ενσωματωμένη εικόνα είναι κοινόχρηστη. Εάν θέλετε να αντιγράψετε την ενσωματωμένη εικόνα χρησιμοποιήστε[`NewSmartObjectViaCopy`](../newsmartobjectviacopy/) μέθοδος.

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Επιστρεφόμενη Αξία

Ο κλωνοποιημένος[`SmartObjectLayer`](../) παράδειγμα.

### Παραδείγματα

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
    int layerNumber = 0; // Ο αριθμός επιπέδου προς αντιγραφή
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
            // Ας αντιστρέψουμε την εικόνα του ενσωματωμένου έξυπνου αντικειμένου (για μια εσωτερική εικόνα PSD αντιστρέφουμε μόνο το πρώτο επίπεδο)
            InvertImage(innerImage);

            // Ας αντικαταστήσουμε την εικόνα του ενσωματωμένου έξυπνου αντικειμένου στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Το διπλό επίπεδο μοιράζεται την ενσωματωμένη εικόνα του με το αρχικό έξυπνο αντικείμενο
        // και θα πρέπει να ενημερωθεί ρητά διαφορετικά η κρυφή μνήμη απόδοσης παραμένει αμετάβλητη.
        // Ενημερώνουμε κάθε έξυπνο αντικείμενο για να βεβαιωθούμε ότι το νέο επίπεδο δημιουργήθηκε από το NewSmartObjectViaCopy
        // δεν μοιράζεται την ενσωματωμένη εικόνα με τους άλλους.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Αντιστρέφει την εικόνα ράστερ συμπεριλαμβανομένης της εικόνας PSD.
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

// Αντιστρέφει την εικόνα ράστερ.
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* συνέλευση [Aspose.PSD](../../../)


