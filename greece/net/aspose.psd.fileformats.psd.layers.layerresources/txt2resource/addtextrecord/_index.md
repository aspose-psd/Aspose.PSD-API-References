---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD για Αναφορά API .NET
description: Txt2Resource μέθοδος. Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το αναγνωριστικό της εγγραφής κειμένου.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το αναγνωριστικό της εγγραφής κειμένου.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Το κείμενο της εγγραφής. |
| bounds | RectangleF | Τα όρια. |

### Επιστρεφόμενη Αξία

Επιστρέφει αναγνωριστικό εγγραφής κειμένου για resource

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Άγνωστη έκδοση πόρου Txt2. |

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

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* συνέλευση [Aspose.PSD](../../../)

