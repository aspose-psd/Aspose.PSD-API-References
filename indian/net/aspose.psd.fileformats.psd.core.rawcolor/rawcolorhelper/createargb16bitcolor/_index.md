---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RawColorHelper मेथड। प्रत्येक चैनल पर 16bit ARGB रंग बनाता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

प्रति चैनल 16-बिट ARGB रंग बनाता है।

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | UInt16 | अल्फा घटक मान (0-65535). |
| r | UInt16 | लाल घटक मान (0-65535). |
| g | UInt16 | हरा घटक मान (0-65535). |
| b | UInt16 | नीला घटक मान (0-65535). |

### रिटर्न वैल्यू

एक नया [`RawColor`](../../rawcolor/) इंस्टेंस जो ARGB रंग का प्रतिनिधित्व करता है।

## टिप्पणियाँ

रंग घटकों को 64-बिट पूर्णांक में इस क्रम में पैक किया जाता है: अल्फा (bits 48-63), लाल (bits 32-47), हरा (bits 16-31), और नीला (bits 0-15).

### देखें भी

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


