---
title: "Απαρίθμηση AutoKerning"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.AutoKerning enum. Η λειτουργία αυτόματης διαστήματος Photoshop μεταξύ συμβόλων"
type: docs
weight: 1610
url: /el/net/aspose.psd.fileformats.psd/autokerning/
---
{{< psd/tize >}}
## AutoKerning enumeration

Η λειτουργία αυτόματης διαστήματος (kerning) του Photoshop (απόσταση μεταξύ συμβόλων).

```csharp
public enum AutoKerning
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Manual | `0` | Τιμή χειροκίνητου διαστήματος. |
| Metric | `1` | Η διαστήση μετρικών χρησιμοποιεί ζεύγη kern, τα οποία περιλαμβάνονται στα περισσότερα γραμματοσειράς (από τους σχεδιαστές τους). |
| Optical | `2` | Η οπτική διαστήση προσαρμόζει το κενό μεταξύ γειτονικών χαρακτήρων βάσει των σχημάτων τους. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των νέων ιδιοτήτων ITextStyle.

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


