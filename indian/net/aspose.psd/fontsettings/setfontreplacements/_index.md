---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings मेथड। फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमति नहीं है तो प्रतिस्थापन खोजा जाएगा। सूची में पहला फ़ॉन्ट सबसे पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है तो सूची से अगला फ़ॉन्ट चुना जाएगा। यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमति नहीं हैं तो अनुमति प्राप्त फ़ॉन्ट सूची से पहला अनुमति प्राप्त फ़ॉन्ट उपयोग किया जाएगा। यदि कोई अनुमति प्राप्त और उपलब्ध फ़ॉन्ट नहीं है तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने की कोशिश करेगी, भले ही वह अनुमति न हो।"
type: docs
weight: 130
url: /hi/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमत नहीं है तो प्रतिस्थापन खोजा जाएगा। सूची में पहला फ़ॉन्ट पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है, तो सूची से अगला फ़ॉन्ट चुना जाएगा। यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमत नहीं हैं, तो अनुमत फ़ॉन्ट सूची से पहला अनुमत फ़ॉन्ट उपयोग किया जाएगा। यदि कोई अनुमत और उपलब्ध फ़ॉन्ट नहीं है, तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने का प्रयास करेगी, भले ही वह अनुमत न हो।

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontToReplace | String | प्रतिस्थापित करने के लिए फ़ॉन्ट। |
| fontNames | String[] | समानता के क्रम में प्रतिस्थापन फ़ॉन्ट नाम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | फ़ॉन्ट एरे और फ़ॉन्ट अंतर एरे की लंबाई समान होनी चाहिए |

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


