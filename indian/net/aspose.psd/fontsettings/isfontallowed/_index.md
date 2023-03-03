---
title: FontSettings.IsFontAllowed
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. नर्धरत करत है क क्य फ़न्ट क अनुमत है नर्दष्ट फ़न्ट नम.
type: docs
weight: 80
url: /hi/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

निर्धारित करता है कि क्या [फ़ॉन्ट की अनुमति है] [निर्दिष्ट फ़ॉन्ट नाम].

```csharp
public static bool IsFontAllowed(string fontName)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | फ़ॉन्ट का नाम। |

### प्रतिलाभ की मात्रा

`सत्य` अगर [फ़ॉन्ट की अनुमति है] [निर्दिष्ट फ़ॉन्ट नाम]; अन्यथा,`असत्य` .

### उदाहरण

निम्न कोड उपयोग करने वाले फोंट को प्रोग्रामेटिक रूप से सीमित करने की क्षमता प्रदर्शित करता है।

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
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

### यह सभी देखें

* class [FontSettings](../)
* नाम स्थान [Aspose.PSD](../../fontsettings/)
* सभा [Aspose.PSD](../../../)


