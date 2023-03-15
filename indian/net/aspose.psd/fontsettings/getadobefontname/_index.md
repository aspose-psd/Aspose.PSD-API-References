---
title: FontSettings.GetAdobeFontName
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. फ़न्ट परवर के नम से एडब फ़न्ट नम प्रप्त करत है
type: docs
weight: 30
url: /hi/net/aspose.psd/fontsettings/getadobefontname/
---
## FontSettings.GetAdobeFontName method

फ़ॉन्ट परिवार के नाम से एडोब फ़ॉन्ट नाम प्राप्त करता है।

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontFamilyName | String | फ़ॉन्ट परिवार का नाम। |

### प्रतिलाभ की मात्रा

फ़ॉन्ट परिवार के नाम से एडोब फ़ॉन्ट नाम।

### उदाहरण

निम्नलिखित कोड भाग शैली में फ़ॉन्ट नाम बदलने की क्षमता प्रदर्शित करता है।

```csharp
[C#]

string outputFilePng = "result_fontEditTest.png";
string outputFilePsd = "fontEditTest.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = new PsdImage(500, 500))
{
    FillLayer backgroundFillLayer = FillLayer.CreateInstance(FillType.Color);
    ((IColorFillSettings)backgroundFillLayer.FillSettings).Color = Color.White;
    image.AddLayer(backgroundFillLayer);

    TextLayer textLayer = image.AddTextLayer("Text 1", new Rectangle(10, 35, image.Width, 35));

    ITextPortion firstPortion = textLayer.TextData.Items[0];
    firstPortion.Style.FontSize = 24;
    firstPortion.Style.FontName = FontSettings.GetAdobeFontName("Comic Sans MS");

    var secondPortion = textLayer.TextData.ProducePortion();
    secondPortion.Text = "Text 2";
    secondPortion.Paragraph.Apply(firstPortion.Paragraph);
    secondPortion.Style.Apply(firstPortion.Style);
    secondPortion.Style.FontName = FontSettings.GetAdobeFontName("Arial");

    textLayer.TextData.AddPortion(secondPortion);
    textLayer.TextData.UpdateLayerData();

    image.Save(outputFilePng, new PngOptions());
    image.Save(outputFilePsd);
}

using (var image = (PsdImage)Image.Load(outputFilePsd))
{
    TextLayer textLayer = (TextLayer)image.Layers[2];

    string adobeFontName1 = FontSettings.GetAdobeFontName("Comic Sans MS");
    string adobeFontName2 = FontSettings.GetAdobeFontName("Arial");

    AssertAreEqual(adobeFontName1, textLayer.TextData.Items[0].Style.FontName);
    AssertAreEqual(adobeFontName2, textLayer.TextData.Items[1].Style.FontName);
}
```

### यह सभी देखें

* class [FontSettings](../)
* नाम स्थान [Aspose.PSD](../../fontsettings/)
* सभा [Aspose.PSD](../../../)


