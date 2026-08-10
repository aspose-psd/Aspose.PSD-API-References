---
title: "FontSettings.GetFontReplacements"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings मेथड। फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है।"
type: docs
weight: 60
url: /hi/net/aspose.psd/fontsettings/getfontreplacements/
---
{{< psd/tize >}}
## FontSettings.GetFontReplacements method

फ़ॉन्ट नाम के द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है।

```csharp
public static string[] GetFontReplacements(string fontName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | फ़ॉन्ट का नाम। |

### रिटर्न वैल्यू

प्रदान किए गए फ़ॉन्ट्स के लिए प्रतिस्थापन नामों की एरे

## उदाहरण

निम्नलिखित कोड प्रोग्रामेटिक रूप से फ़ॉन्ट को सीमित करने की क्षमता दर्शाता है।

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### देखें भी

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


