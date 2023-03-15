---
title: FontSettings.ClearFontReplacements
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. सभ फ़न्ट प्रतस्थपन सफ़ करत है
type: docs
weight: 20
url: /hi/net/aspose.psd/fontsettings/clearfontreplacements/
---
## FontSettings.ClearFontReplacements method

सभी फ़ॉन्ट प्रतिस्थापन साफ़ करता है

```csharp
public static void ClearFontReplacements()
```

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


