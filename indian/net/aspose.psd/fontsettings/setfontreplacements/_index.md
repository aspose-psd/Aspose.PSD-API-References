---
title: FontSettings.SetFontReplacements
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FontSettings तरक. फ़न्ट प्रतस्थपन सूच सेट करत है यद फन्ट क अनुमत नहं है त प्रतस्थपन ढूंढ जएग सूच में पहले वले फन्ट क पहले उपयग कय जएग यद यह भ हट दय गय है त सूच से अगले फ़न्ट क चयन कय जएग सस्टम डफ़ल्ट फ़न्ट क उपयग करने क प्रयस करें भले ह इसक अनुमत न ह
type: docs
weight: 110
url: /hi/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फॉन्ट की अनुमति नहीं है तो प्रतिस्थापन ढूंढा जाएगा। सूची में पहले वाले फॉन्ट का पहले उपयोग किया जाएगा। यदि यह भी हटा दिया गया है, तो सूची से अगले फ़ॉन्ट का चयन किया जाएगा। सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने का प्रयास करें, भले ही इसकी अनुमति न हो।

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontToReplace | String | बदलने के लिए फ़ॉन्ट। |
| fontNames | String[] | समानता के क्रम में प्रतिस्थापन फ़ॉन्ट नाम। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | फ़ॉन्ट सरणी और फ़ॉन्ट अंतर सरणी की लंबाई बराबर होनी चाहिए |

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


