---
title: "FontSettings.GetAdobeFontName"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings मेथड। फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम प्राप्त करता है"
type: docs
weight: 40
url: /hi/net/aspose.psd/fontsettings/getadobefontname/
---
{{< psd/tize >}}
## FontSettings.GetAdobeFontName method

फ़ॉन्ट परिवार नाम के आधार पर Adobe फ़ॉन्ट नाम प्राप्त करता है।

```csharp
public static string GetAdobeFontName(string fontFamilyName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontFamilyName | String | फ़ॉन्ट परिवार का नाम। |

### रिटर्न वैल्यू

फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम।

## उदाहरण

निम्नलिखित कोड भाग शैली में फ़ॉन्ट नाम बदलने की क्षमता को दर्शाता है।

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

    TextLayer textLayer = image.AddTextLayer("Text 1", new Rectangle(10, 35, image.Width, 60));

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

### देखें भी

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


