---
title: ITextStyle.Fractions
second_title: Aspose.PSD για Αναφορά API .NET
description: ITextStyle ιδιοκτησία. Τα σύμβολα των κλασμάτων μπορούν να αντικατασταθούν με ειδική γλυφή.
type: docs
weight: 140
url: /el/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fractions/
---
## ITextStyle.Fractions property

Τα σύμβολα των κλασμάτων μπορούν να αντικατασταθούν με ειδική γλυφή.

```csharp
public bool Fractions { get; set; }
```

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

* interface [ITextStyle](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* συνέλευση [Aspose.PSD](../../../)


