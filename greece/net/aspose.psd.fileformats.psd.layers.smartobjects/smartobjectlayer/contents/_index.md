---
title: "SmartObjectLayer.Contents"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα SmartObjectLayer. Λαμβάνει ή ορίζει τα περιεχόμενα του επιπέδου έξυπνου αντικειμένου. Το ενσωματωμένο περιεχόμενο έξυπνου αντικειμένου είναι το ενσωματωμένο ακατέργαστο αρχείο εικόνας Data και οι ιδιότητές του. Το συνδεδεμένο περιεχόμενο έξυπνου αντικειμένου είναι το ακατέργαστο περιεχόμενο του συνδεδεμένου αρχείου εικόνας εάν είναι διαθέσιμο και οι ιδιότητές του LiFeDataSource. Δεν υποστηρίζουμε τη φόρτωση από τη βιβλιοθήκη γραφικών Adobe Photoshop όταν το IsLibraryLink είναι true. Για κανονικά αρχεία συνδέσμου, αρχικά χρησιμοποιούμε το RelativePath για να αναζητήσουμε το αρχείο σχετικά με τη διαδρομή της πηγαίας εικόνας SourceImagePath· εάν δεν είναι διαθέσιμο, κοιτάζουμε το FullPath· αν όχι, τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο φάκελο όπου βρίσκεται η εικόνα μας SourceImagePath."
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

Λαμβάνει ή ορίζει τα περιεχόμενα του επιπέδου έξυπνου αντικειμένου. Το ενσωματωμένο περιεχόμενο έξυπνου αντικειμένου είναι το ενσωματωμένο ακατέργαστο αρχείο εικόνας: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) και οι ιδιότητές του. Το συνδεδεμένο περιεχόμενο έξυπνου αντικειμένου είναι το ακατέργαστο περιεχόμενο του συνδεδεμένου αρχείου εικόνας εάν είναι διαθέσιμο και οι ιδιότητές του: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Δεν υποστηρίζουμε τη φόρτωση από τη βιβλιοθήκη γραφικών Adobe Photoshop όταν το [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) είναι true. Για κανονικά αρχεία συνδέσμου, αρχικά χρησιμοποιούμε το [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) για να αναζητήσουμε το αρχείο σχετικά με τη διαδρομή της πηγαίας εικόνας SourceImagePath· εάν δεν είναι διαθέσιμο, κοιτάζουμε το [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/), αν όχι, τότε αναζητούμε το αρχείο συνδέσμου στον ίδιο φάκελο όπου βρίσκεται η εικόνα μας: SourceImagePath.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

Τα περιεχόμενα του επιπέδου έξυπνου αντικειμένου byte[].

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| NotSupportedException | Δεν είναι δυνατή η λήψη των περιεχομένων από τη βιβλιοθήκη Adobe Photoshop. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των ενσωματωμένων Smart objects.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Αυτό το παράδειγμα δείχνει πώς να αλλάξετε το επίπεδο smart object στο αρχείο PSD και να εξάγετε / ενημερώσετε τα αρχικά ενσωματωμένα περιεχόμενα του smart object.
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

        // Ας εξάγουμε την ενσωματωμένη εικόνα smart object από το επίπεδο smart object του PSD
        smartObjectLayer.ExportContents(exportPath);

        // Ας ελέγξουμε αν η αρχική εικόνα αποθηκεύτηκε σωστά
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Ας αντιστρέψουμε την αρχική εικόνα smart object
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Ας αντικαταστήσουμε την ενσωματωμένη εικόνα smart object στο επίπεδο PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Ας ελέγξουμε αν η ενημερωμένη εικόνα αποθηκεύτηκε σωστά
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Δείτε επίσης

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


