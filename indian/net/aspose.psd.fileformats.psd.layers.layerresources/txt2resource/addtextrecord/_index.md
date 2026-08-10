---
title: "Txt2Resource.AddTextRecord"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Txt2Resource मेथड। टेक्स्ट रिकॉर्ड को रिसोर्स में जोड़ता है और टेक्स्ट रिकॉर्ड की आईडी लौटाता है"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
{{< psd/tize >}}
## Txt2Resource.AddTextRecord method

टेक्स्ट रिकॉर्ड को रिसोर्स में जोड़ता है और टेक्स्ट रिकॉर्ड का आईडी लौटाता है।

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| टेक्स्ट | String | रिकॉर्ड टेक्स्ट। |
| सीमाएँ | RectangleF | सीमाएँ। |

### रिटर्न वैल्यू

रिसोर्स के लिए टेक्स्ट रिकॉर्ड की आईडी लौटाता है

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | अज्ञात Txt2 रिसोर्स संस्करण। |

## उदाहरण

निम्नलिखित कोड नए ITextStyle गुणों के समर्थन को दर्शाता है।

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

// मान जांचें
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

### देखें भी

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


