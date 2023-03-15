---
title: Txt2Resource.AddTextRecord
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Txt2Resource तरक. टेक्स्ट रकर्ड क रसर्स में जड़त है और टेक्स्ट रकर्ड क आईड लटत है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

टेक्स्ट रिकॉर्ड को रिसोर्स में जोड़ता है और टेक्स्ट रिकॉर्ड की आईडी लौटाता है।

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | String | रिकॉर्ड पाठ। |
| bounds | RectangleF | सीमा। |

### प्रतिलाभ की मात्रा

रिसोर्स के लिए टेक्स्ट रिकॉर्ड की आईडी लौटाता है

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | अज्ञात Txt2 संसाधन संस्करण। |

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

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* सभा [Aspose.PSD](../../../)


