---
title: Class SmartObjectProvider
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.SmartObjectProvider τάξη. Καθορίζει τον πάροχο έξυπνου αντικειμένου που παρέχει λήψη / ρύθμιση πηγών δεδομένων από παγκόσμιους πόρους συνδέσμων του αρχείου PSD και των περιεχομένων τους.
type: docs
weight: 4000
url: /el/net/aspose.psd.fileformats.psd/smartobjectprovider/
---
## SmartObjectProvider class

Καθορίζει τον πάροχο έξυπνου αντικειμένου που παρέχει λήψη / ρύθμιση πηγών δεδομένων από παγκόσμιους πόρους συνδέσμων του αρχείου PSD και των περιεχομένων τους.

```csharp
public class SmartObjectProvider
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [ConvertToSmartObject](../../aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/#converttosmartobject_1)(params int[]) | Μετατρέπει επίπεδα σε ενσωματωμένο έξυπνο αντικείμενο. |
| [ConvertToSmartObject](../../aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/#converttosmartobject)(Layer[]) | Μετατρέπει επίπεδα σε ενσωματωμένο έξυπνο αντικείμενο. |
| [EmbedAllLinked](../../aspose.psd.fileformats.psd/smartobjectprovider/embedalllinked/)() | Ενσωματώνει όλα τα συνδεδεμένα έξυπνα αντικείμενα στην εικόνα. |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/)(SmartObjectLayer) | Δημιουργεί ένα νέο επίπεδο έξυπνου αντικειμένου αντιμετωπίζοντας το αρχικό επίπεδο. |
| [UpdateAllModifiedContent](../../aspose.psd.fileformats.psd/smartobjectprovider/updateallmodifiedcontent/)() | Ενημερώνει το περιεχόμενο όλων των τροποποιημένων έξυπνων αντικειμένων στην εικόνα. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ενημέρωσης Συνδεδεμένων Έξυπνων αντικειμένων.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Αυτό το παράδειγμα δείχνει πώς να ενημερώσετε το εξωτερικό ή το ενσωματωμένο επίπεδο έξυπνου αντικειμένου χρησιμοποιώντας αυτές τις μεθόδους:
// RelinkToFile, UpdateModifiedContent, ExportContents
ExampleOfUpdatingSmartObjectLayer("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfUpdatingSmartObjectLayer("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfUpdatingSmartObjectLayer(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // Αυτό το παράδειγμα δείχνει πώς μπορείτε να αλλάξετε το επίπεδο έξυπνου αντικειμένου στο αρχείο PSD και να εξάγετε / ενημερώσετε τα περιεχόμενά του.
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "updating_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_modified.png";
    string png2OutputPath = dataDir + fileName + "_updated_modified.png";
    string psd2OutputPath = dataDir + fileName + "_updated_modified.psd";
    string exportPath = dataDir + fileName + "_exported." + GetFormatExt(format);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        var contentType = smartObjectLayer.ContentType;
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        if (contentType == SmartObjectType.AvailableLinked)
        {
            Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
            // Ας εξάγουμε την εικόνα εξωτερικού έξυπνου αντικειμένου από το επίπεδο έξυπνου αντικειμένου PSD σε μια νέα θέση
            // γιατί πρόκειται να το τροποποιήσουμε.
            smartObjectLayer.ExportContents(exportPath);
            smartObjectLayer.RelinkToFile(exportPath);
        }

        // Ας αντιστρέψουμε το περιεχόμενο του έξυπνου αντικειμένου: εσωτερική (όχι προσωρινή) εικόνα
        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(new LoadOptions()))
        {
            InvertImage(innerImage);
            using (var stream = new MemoryStream())
            {
                innerImage.Save(stream);
                smartObjectLayer.Contents = stream.ToArray();
            }
        }

        // Ας ελέγξουμε αν το τροποποιημένο περιεχόμενο δεν επηρεάζει ακόμη την απόδοση.
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        smartObjectLayer.UpdateModifiedContent();

        // Ας ελέγξουμε αν το ενημερωμένο περιεχόμενο επηρεάζει την απόδοση και η εικόνα psd έχει αποθηκευτεί σωστά
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Αυτό το παράδειγμα δείχνει πώς να μετατρέψετε το ενσωματωμένο έξυπνο αντικείμενο σε εξωτερικά συνδεδεμένα περιεχόμενα χρησιμοποιώντας τη μέθοδο ConvertToLinked.
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("new_panama-papers-4.psd", 0x10caa, 0, 0, 0x280, 0x169, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r3-embedded.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-tiff.psd", 0xca94, 0, 0, 0xb, 0x10, FileFormat.Tiff);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-bmp.psd", 0x278, 0, 0, 0xb, 0x10, FileFormat.Bmp);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-gif.psd", 0x3ec, 0, 0, 0xb, 0x10, FileFormat.Gif);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg.psd", 0x327, 0, 0, 0xb, 0x10, FileFormat.Jpeg);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-jpeg2000.psd", 0x519f, 0, 0, 0xb, 0x10, FileFormat.Jpeg2000);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-psd.psd", 0xc074, 0, 0, 0xb, 0x10, FileFormat.Psd);
ExampleOfEmbeddedSmartObjectLayerToLinkedConversion("r-embedded-png.psd", 0x207, 0, 0, 0xb, 0x10, FileFormat.Png);

void ExampleOfEmbeddedSmartObjectLayerToLinkedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    // Αυτό δείχνει πώς να μετατρέψετε ένα ενσωματωμένο επίπεδο έξυπνου αντικειμένου στο αρχείο PSD σε εξωτερικό.
    var formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_linked_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_external.png";
    string psdOutputPath = dataDir + fileName + "_to_external.psd";
    string externalPath = dataDir + fileName + "_external." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        Directory.CreateDirectory(Path.GetDirectoryName(externalPath));
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer.ConvertToLinked(externalPath);

        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        // Ας ελέγξουμε αν η εικόνα που έχει μετατραπεί έχει αποθηκευτεί σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);
    }
}

// Αυτό το παράδειγμα δείχνει πώς να ενσωματώσετε ένα εξωτερικό επίπεδο έξυπνου αντικειμένου ή όλα τα συνδεδεμένα επίπεδα στο αρχείο PSD χρησιμοποιώντας τη μέθοδο EmbedLinked.
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfLinkedSmartObjectLayerToEmbeddedConversion("rgb8_2x2_linked2.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
void ExampleOfLinkedSmartObjectLayerToEmbeddedConversion(
    string filePath,
    int contentsLength,
    int left,
    int top,
    int right,
    int bottom,
    FileFormat format)
{
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "to_embedded_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + "_to_embedded.png";
    string psdOutputPath = dataDir + fileName + "_to_embedded.psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer0 = (SmartObjectLayer)image.Layers[0];
        smartObjectLayer0.EmbedLinked();
        AssertAreEqual(contentsLength, smartObjectLayer0.Contents.Length);
        AssertAreEqual(left, smartObjectLayer0.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer0.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer0.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer0.ContentsBounds.Bottom);
        if (image.Layers.Length >= 2)
        {
            var smartObjectLayer1 = (SmartObjectLayer)image.Layers[1];
            AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer0.ContentType);
            AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer1.ContentType);

            image.SmartObjectProvider.EmbedAllLinked();
            foreach (Layer layer in image.Layers)
            {
                var smartLayer = layer as SmartObjectLayer;
                if (smartLayer != null)
                {
                    AssertAreEqual(SmartObjectType.Embedded, smartLayer.ContentType);
                }
            }
        }

        Directory.CreateDirectory(Path.GetDirectoryName(psdOutputPath));
        // Ας ελέγξουμε αν η εικόνα που έχει μετατραπεί έχει αποθηκευτεί σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }

    using (PsdImage image = (PsdImage)Image.Load(psdOutputPath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(SmartObjectType.Embedded, smartObjectLayer.ContentType);
    }
}

// Αυτό το παράδειγμα δείχνει πώς μπορείτε να αλλάξετε το επίπεδο εξωτερικού έξυπνου αντικειμένου Adobe® Photoshop® και να εξαγάγετε / ενημερώσετε τα περιεχόμενά του
// χρησιμοποιώντας τις μεθόδους ExportContents και ReplaceContents.
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked.psd", 0x53, 0, 0, 2, 2, FileFormat.Png);
ExampleOfExternalSmartObjectLayerSupport("rgb8_2x2_linked2.psd", 0x4aea, 0, 0, 10, 10, FileFormat.Psd);
void ExampleOfExternalSmartObjectLayerSupport(string filePath, int contentsLength, int left, int top, int right, int bottom, FileFormat format)
{
    string formatExt = GetFormatExt(format);
    string fileName = Path.GetFileNameWithoutExtension(filePath);
    string dataDir = "external_support_output" + Path.DirectorySeparatorChar;
    filePath = filePath;
    string pngOutputPath = dataDir + fileName + ".png";
    string psdOutputPath = dataDir + fileName + ".psd";
    string linkOutputPath = dataDir + fileName + "_inverted." + formatExt;
    string png2OutputPath = dataDir + fileName + "_updated.png";
    string psd2OutputPath = dataDir + fileName + "_updated.psd";
    string exportPath = dataDir + fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[image.Layers.Length - 1];
        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);
        AssertAreEqual(contentsLength, smartObjectLayer.Contents.Length);
        AssertAreEqual(SmartObjectType.AvailableLinked, smartObjectLayer.ContentType);

        Directory.CreateDirectory(Path.GetDirectoryName(exportPath));
        // Ας εξάγουμε την εικόνα συνδεδεμένου έξυπνου αντικειμένου από το επίπεδο έξυπνου αντικειμένου PSD
        smartObjectLayer.ExportContents(exportPath);

        // Ας ελέγξουμε αν η αρχική εικόνα έχει αποθηκευτεί σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Ας αντιστρέψουμε την εικόνα του συνδεδεμένου έξυπνου αντικειμένου
            InvertImage(innerImage);
            innerImage.Save(linkOutputPath);

            // Ας αντικαταστήσουμε την εικόνα συνδεδεμένου έξυπνου αντικειμένου στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(linkOutputPath);
        }

        // Ας ελέγξουμε αν η ενημερωμένη εικόνα έχει αποθηκευτεί σωστά
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}

// Αντιστρέφει την εικόνα.
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

// Λαμβάνει την επέκταση μορφής.
string GetFormatExt(FileFormat format)
{
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : format.ToString().ToLowerInvariant();
    return formatExt;
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)

