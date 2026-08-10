---
title: "एनम RenderQuality"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality एनम। यह वॉर्प की रेंडरिंग गुणवत्ता का वर्णन करता है"
type: docs
weight: 3990
url: /hi/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

यह वॉर्प की रेंडरिंग क्वालिटी को वर्णित करता है।

```csharp
public enum RenderQuality
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Turbo | `4` | सबसे तेज़ विकल्प, लेकिन गुणवत्ता घटती है। |
| VeryFast | `18` | यदि आपको यह तेज़ चाहिए, तो यह छोटे वक्रों के लिए उपयुक्त हो सकता है। |
| Fast | `35` | रेंडरिंग को तेज़ बनाने की अनुमति देता है, जबकि गुणवत्ता में थोड़ा गिरावट आती है। |
| Normal | `60` | अधिकांश वक्रों के लिए अनुशंसित मान |
| Good | `130` | मानक गुणवत्ता से अधिक, गति धीमी। मजबूत विकृतियों के लिए अनुशंसित। |
| Excellent | `260` | सबसे धीमा विकल्प। मजबूत विकृतियों और उच्च रेज़ोल्यूशन के लिए अनुशंसित। |

## उदाहरण

निम्नलिखित कोड WarpSettings.RenderQuality प्रॉपर्टी को दिखाता है जो वॉर्प विकृति को कॉन्फ़िगर करता है।

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // यह Smart Layer से WarpSettings प्राप्त करता है
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // यह वॉर्प प्रोसेसिंग क्षेत्र का आकार सेट करता है
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // यहाँ कोई त्रुटि नहीं होनी चाहिए
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### देखें भी

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


