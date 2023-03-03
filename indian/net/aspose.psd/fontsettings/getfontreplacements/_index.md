---
title: FontSettings.GetFontReplacements
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. फ़न्ट नम द्वर फ़न्ट प्रतस्थपन सरण प्रप्त करत है
type: docs
weight: 50
url: /hi/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन सरणी प्राप्त करता है

```csharp
public static string[] GetFontReplacements(string fontName)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | String | फ़ॉन्ट का नाम। |

### प्रतिलाभ की मात्रा

प्रदान किए गए फोंट के लिए प्रतिस्थापन के नामों की सरणी

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


