---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings मेथड। निर्धारित करता है कि निर्दिष्ट फ़ॉन्ट नाम के लिए फ़ॉन्ट अनुमति है या नहीं"
type: docs
weight: 90
url: /hi/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

निर्धारित करता है कि क्या [is font allowed] [निर्दिष्ट फ़ॉन्ट नाम]।

```csharp
public static bool IsFontAllowed(string fontName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontName | String | फ़ॉन्ट का नाम। |

### रिटर्न वैल्यू

`true` यदि [is font allowed] [the specified font name]; अन्यथा, `false`.

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


