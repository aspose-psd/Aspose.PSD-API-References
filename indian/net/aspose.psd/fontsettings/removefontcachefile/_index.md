---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FontSettings मेथड। फ़ॉन्ट कैश फ़ाइल को हटाता है"
type: docs
weight: 100
url: /hi/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

फ़ॉन्ट कैश फ़ाइल को हटाता है।

```csharp
public static void RemoveFontCacheFile()
```

## उदाहरण

निम्नलिखित कोड लोड किए गए फ़ॉन्ट्स की कैश फ़ाइल को हटाने के मेथड को दर्शाता है।

```csharp
[C#]

string src = "SimpleText.psd";

FontSettings.RemoveFontCacheFile();

using (var psdImage = (PsdImage)Image.Load(src))
{
    foreach (var layer in psdImage.Layers)
    {
        if (layer is TextLayer textLayer)
        {
            textLayer.GetFonts();
        }
    }
}
```

### देखें भी

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


