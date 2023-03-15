---
title: ITextStyle.AutoKerning
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: ITextStyle संपत्त. ऑट कर्नंग प्रप्त करत है य सेट करत है
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/
---
## ITextStyle.AutoKerning property

ऑटो कर्निंग प्राप्त करता है या सेट करता है।

```csharp
public AutoKerning AutoKerning { get; set; }
```

### संपत्ति मूल्य

दो अक्षरों के बीच ऑटो कर्निंग।

### उदाहरण

निम्न कोड नए ITextStyle गुणों के समर्थन के समर्थन को प्रदर्शित करता है।

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

// मूल्यों की जाँच करें
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

### यह सभी देखें

* enum [AutoKerning](../../../aspose.psd.fileformats.psd/autokerning/)
* interface [ITextStyle](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* सभा [Aspose.PSD](../../../)


