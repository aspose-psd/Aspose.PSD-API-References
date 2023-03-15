---
title: Enum AutoKerning
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.AutoKerning αρίθμηση. Η λειτουργία αυτόματης πυροδότησης του Photoshop απόσταση μεταξύ συμβόλων.
type: docs
weight: 1600
url: /el/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Η λειτουργία αυτόματης πυροδότησης του Photoshop (απόσταση μεταξύ συμβόλων).

```csharp
public enum AutoKerning
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| Manual | `0` | Μη αυτόματη τιμή πυρήνα. |
| Metric | `1` | Ο πυρήνας μετρήσεων χρησιμοποιεί ζεύγη πυρήνα, τα οποία περιλαμβάνονται στις περισσότερες γραμματοσειρές (από τους σχεδιαστές τους). |
| Optical | `2` | Ο οπτικός πυρήνας προσαρμόζει την απόσταση μεταξύ γειτονικών χαρακτήρων με βάση τα σχήματά τους. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της υποστήριξης νέων ιδιοτήτων ITextStyle.

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string srcFile = "A.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    var textLayer = (TextLayer)psdImage.Layers[1];
    textLayer.UpdateText("abc");

    psdImage.Save(outputFile);
}

// Ελέγξτε τις τιμές
using (var srcImage = (PsdImage)Image.Load(srcFile))
{
    var srcTextLayer = (TextLayer)srcImage.Layers[1];
    var etalonStyle = srcTextLayer.TextData.Items[0].Style;

    using (var outImage = (PsdImage)Image.Load(outputFile))
    {
        var outTextLayer = (TextLayer)outImage.Layers[1];
        var resultStyle = outTextLayer.TextData.Items[0].Style;

        AssertAreEqual(etalonStyle.AutoLeading, resultStyle.AutoLeading);
        AssertAreEqual(etalonStyle.FontIndex, resultStyle.FontIndex);
        AssertAreEqual(etalonStyle.Underline, resultStyle.Underline);
        AssertAreEqual(etalonStyle.Strikethrough, resultStyle.Strikethrough);
        AssertAreEqual(etalonStyle.AutoKerning, resultStyle.AutoKerning);
        AssertAreEqual(etalonStyle.StandardLigatures, resultStyle.StandardLigatures);
        AssertAreEqual(etalonStyle.DiscretionaryLigatures, resultStyle.DiscretionaryLigatures);
        AssertAreEqual(etalonStyle.ContextualAlternates, resultStyle.ContextualAlternates);
        AssertAreEqual(etalonStyle.LanguageIndex, resultStyle.LanguageIndex);
        AssertAreEqual(etalonStyle.VerticalScale, resultStyle.VerticalScale);
        AssertAreEqual(etalonStyle.HorizontalScale, resultStyle.HorizontalScale);
        AssertAreEqual(etalonStyle.Fractions, resultStyle.Fractions);
    }
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


