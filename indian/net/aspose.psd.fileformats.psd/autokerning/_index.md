---
title: Enum AutoKerning
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.AutoKerning एनुम. फटशप ऑट कर्नंग मड प्रतकं के बच क दूर
type: docs
weight: 1600
url: /hi/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

फोटोशॉप ऑटो कर्निंग मोड (प्रतीकों के बीच की दूरी)।

```csharp
public enum AutoKerning
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Manual | `0` | मैन्युअल कर्निंग मान. |
| Metric | `1` | मेट्रिक्स कर्निंग कर्न जोड़े का उपयोग करता है, जो अधिकांश फोंट (उनके डिजाइनरों से) के साथ शामिल हैं। |
| Optical | `2` | ऑप्टिकल कर्निंग उनके आकार के आधार पर आसन्न वर्णों के बीच की दूरी को समायोजित करता है। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)


