---
title: "LinkResource.Item"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα LinkResource. Λαμβάνει το LinkDataSource στο καθορισμένο δείκτη, το οποίο είναι το μοναδικό αναγνωριστικό της πηγής δεδομένων συνδέσμου"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/
---
{{< psd/tize >}}
## LinkResource indexer

Λαμβάνει το [`LinkDataSource`](../../linkdatasource/) στο καθορισμένο δείκτη, το οποίο είναι το μοναδικό αναγνωριστικό της πηγής δεδομένων συνδέσμου..

```csharp
public LinkDataSource this[Guid index] { get; }
```

| Παράμετρος | Περιγραφή |
| --- | --- |
| δείκτης | Ο δείκτης ως μοναδικό αναγνωριστικό της πηγής δεδομένων συνδέσμου. |

### Τιμή Επιστροφής

Το αντικείμενο [`LinkDataSource`](../../linkdatasource/).

### Property Value

Το [`LinkDataSource`](../../linkdatasource/).

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

* class [LinkDataSource](../../linkdatasource/)
* class [LinkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


