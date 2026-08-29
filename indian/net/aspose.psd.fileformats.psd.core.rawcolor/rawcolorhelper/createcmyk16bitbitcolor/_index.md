---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RawColorHelper मेथड। प्रत्येक चैनल पर 16bit CMYK रंग बनाता है।"
type: docs
weight: 40
url: /hi/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

प्रति चैनल 16-बिट CMYK रंग बनाता है।

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| c | UInt16 | सियान घटक मान (0-65535). |
| m | UInt16 | मैजेंटा घटक मान (0-65535). |
| y | UInt16 | पीला घटक मान (0-65535). |
| k | UInt16 | मुख्य (काली) घटक मान (0-65535)। |

### रिटर्न वैल्यू

एक नया [`RawColor`](../../rawcolor/) इंस्टेंस जो CMYK रंग का प्रतिनिधित्व करता है।

## टिप्पणियाँ

रंग घटकों को 64-बिट पूर्णांक में इस क्रम में पैक किया जाता है: cyan (bits 48-63), magenta (bits 32-47), yellow (bits 16-31), और key/black (bits 0-15)।

### देखें भी

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


