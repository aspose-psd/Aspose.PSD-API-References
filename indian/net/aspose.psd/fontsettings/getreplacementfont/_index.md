---
title: FontSettings.GetReplacementFont
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. सबसे उपयुक्त प्रतस्थपन फ़न्ट प्रप्त करत है यद सभ प्रतस्थपनं क अनुमत नहं है त पहले अनुमत और उपलब्ध फ़न्ट वपस कर दय जएग
type: docs
weight: 70
url: /hi/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है। यदि सभी प्रतिस्थापनों की अनुमति नहीं है तो पहले अनुमत और उपलब्ध फ़ॉन्ट वापस कर दिया जाएगा।

```csharp
public static string GetReplacementFont(string fontName)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | फ़ॉन्ट का नाम। |

### प्रतिलाभ की मात्रा

प्रतिस्थापित फ़ॉन्ट का नाम

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


