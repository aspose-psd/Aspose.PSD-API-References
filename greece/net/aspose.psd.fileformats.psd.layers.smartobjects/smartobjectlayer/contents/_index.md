---
title: SmartObjectLayer.Contents
second_title: Aspose.PSD για Αναφορά API .NET
description: SmartObjectLayer ιδιοκτησία. Λαμβάνει ή ορίζει τα περιεχόμενα του επιπέδου έξυπνου αντικειμένου. Τα περιεχόμενα του ενσωματωμένου έξυπνου αντικειμένου είναι το ενσωματωμένο αρχείο πρωτογενούς εικόναςData και τις ιδιότητές του. Τα περιεχόμενα συνδεδεμένου έξυπνου αντικειμένου είναι το μη επεξεργασμένο περιεχόμενο του συνδεδεμένου αρχείου εικόνας εάν είναι διαθέσιμο και οι ιδιότητές τουLiFeDataSource . Δεν υποστηρίζεται η φόρτωση από το Adobe Photoshop  Βιβλιοθήκη γραφικών ότανIsLibraryLink είναι αλήθεια. Για κανονικά αρχεία συνδέσμων αρχικά χρησιμοποιούμεRelativePath για να αναζητήσετε το αρχείο relative στη διαδρομή της εικόνας προέλευσηςSourceImagePath  αν δεν είναι διαθέσιμο κοιτάμεFullPath  αν όχι τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο κατάλογο όπου βρίσκεται η εικόνα μαςSourceImagePath .
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
## SmartObjectLayer.Contents property

Λαμβάνει ή ορίζει τα περιεχόμενα του επιπέδου έξυπνου αντικειμένου. Τα περιεχόμενα του ενσωματωμένου έξυπνου αντικειμένου είναι το ενσωματωμένο αρχείο πρωτογενούς εικόνας:[`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) και τις ιδιότητές του. Τα περιεχόμενα συνδεδεμένου έξυπνου αντικειμένου είναι το μη επεξεργασμένο περιεχόμενο του συνδεδεμένου αρχείου εικόνας, εάν είναι διαθέσιμο και οι ιδιότητές του:[`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Δεν υποστηρίζεται η φόρτωση από το Adobe� Photoshop� �� Βιβλιοθήκη γραφικών όταν[`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) είναι αλήθεια. Για κανονικά αρχεία συνδέσμων, αρχικά, χρησιμοποιούμε[`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) για να αναζητήσετε το αρχείο relative στη διαδρομή της εικόνας προέλευσηςSourceImagePath , αν δεν είναι διαθέσιμο κοιτάμε[`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , αν όχι τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο κατάλογο όπου βρίσκεται η εικόνα μας:SourceImagePath .

```csharp
public byte[] Contents { get; set; }
```

### Αξία περιουσίας

Τοbyte[] περιεχόμενα επιπέδου έξυπνου αντικειμένου.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| NotSupportedException | Δεν είναι δυνατή η λήψη περιεχομένου από τη βιβλιοθήκη Adobe Photoshop. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη ενσωματωμένων έξυπνων αντικειμένων.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Αυτό το παράδειγμα δείχνει τον τρόπο αλλαγής του επιπέδου έξυπνου αντικειμένου στο αρχείο PSD και εξαγωγής/ενημέρωσης του αρχικού ενσωματωμένου περιεχομένου του έξυπνου αντικειμένου.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Ας εξάγουμε την εικόνα του ενσωματωμένου έξυπνου αντικειμένου από το επίπεδο έξυπνου αντικειμένου PSD
        smartObjectLayer.ExportContents(exportPath);

        // Ας ελέγξουμε αν η αρχική εικόνα έχει αποθηκευτεί σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Ας αντιστρέψουμε την αρχική εικόνα έξυπνου αντικειμένου
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Ας αντικαταστήσουμε την εικόνα του ενσωματωμένου έξυπνου αντικειμένου στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Ας ελέγξουμε αν η ενημερωμένη εικόνα έχει αποθηκευτεί σωστά
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* class [SmartObjectLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* συνέλευση [Aspose.PSD](../../../)


