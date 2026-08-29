---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "RawColorHelper विधि। प्रत्येक चैनल पर 8bit ARGB रंग बनाती है।"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

प्रति चैनल 8-बिट ARGB रंग बनाता है।

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | बाइट | अल्फा घटक मान (0-255)। |
| r | बाइट | लाल घटक मान (0-255)। |
| g | बाइट | हरा घटक मान (0-255)। |
| b | बाइट | नीला घटक मान (0-255)। |

### रिटर्न वैल्यू

एक नया [`RawColor`](../../rawcolor/) इंस्टेंस जो ARGB रंग का प्रतिनिधित्व करता है।

## टिप्पणियाँ

रंग घटकों को 32-बिट पूर्णांक में इस क्रम में पैक किया जाता है: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), और blue (bits 0-7)।

### देखें भी

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Drawing.Color से प्रति चैनल 8-बिट ARGB रंग बनाता है।

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| drawingColor | रंग | यह System.Drawing Color |

### रिटर्न वैल्यू

एक नया [`RawColor`](../../rawcolor/) इंस्टेंस जो ARGB रंग का प्रतिनिधित्व करता है।

## टिप्पणियाँ

रंग घटकों को 32-बिट पूर्णांक में इस क्रम में पैक किया जाता है: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), और blue (bits 0-7)।

### देखें भी

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


