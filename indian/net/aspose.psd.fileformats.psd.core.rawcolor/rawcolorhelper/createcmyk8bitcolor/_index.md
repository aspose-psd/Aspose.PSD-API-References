---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RawColorHelper मेथड। प्रत्येक चैनल पर 8bit CMYK रंग बनाता है।"
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

प्रति चैनल 8-बिट CMYK रंग बनाता है।

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | बाइट | सियान घटक मान (0-255). |
| m | बाइट | मैजेंटा घटक मान (0-255). |
| y | बाइट | पीला घटक मान (0-255). |
| k | बाइट | की (काला) घटक मान (0-255). |

### रिटर्न वैल्यू

एक नया [`RawColor`](../../rawcolor/) इंस्टेंस जो CMYK रंग का प्रतिनिधित्व करता है।

## टिप्पणियाँ

रंग घटकों को 32-बिट पूर्णांक में इस क्रम में पैक किया जाता है: सियान (bits 24-31), मैजेंटा (bits 16-23), पीला (bits 8-15), और की/काला (bits 0-7).

### देखें भी

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


