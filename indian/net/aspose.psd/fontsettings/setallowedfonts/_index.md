---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings method. फ़ॉन्ट को फ़ॉन्ट सूची द्वारा प्रतिबंधित करता है। प्रतिबंध लगाने से पहले वास्तविक फ़ॉन्ट नाम जांचें। प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null पर सेट करें।"
type: docs
weight: 120
url: /hi/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

फ़ॉन्ट को फ़ॉन्टों की सूची द्वारा प्रतिबंधित करता है। प्रतिबंध से पहले वास्तविक फ़ॉन्ट नाम जाँचें। प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null सेट करें।

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontList | String[] | फ़ॉन्ट सूची। |

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


