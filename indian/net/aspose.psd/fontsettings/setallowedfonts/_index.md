---
title: FontSettings.SetAllowedFonts
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. फंट क सूच द्वर उपयग करने वले फ़न्ट क प्रतबंधत करत है कृपय प्रतबंध से पहले वस्तवक फ़न्ट नमं क जंच करें प्रतबंध हटने के लए अनुमत फ़न्ट सूच क शून्य पर सेट करें
type: docs
weight: 100
url: /hi/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

फोंट की सूची द्वारा उपयोग करने वाले फ़ॉन्ट को प्रतिबंधित करता है। कृपया प्रतिबंध से पहले वास्तविक फ़ॉन्ट नामों की जांच करें प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को शून्य पर सेट करें

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontList | String[] | फ़ॉन्ट सूची। |

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


