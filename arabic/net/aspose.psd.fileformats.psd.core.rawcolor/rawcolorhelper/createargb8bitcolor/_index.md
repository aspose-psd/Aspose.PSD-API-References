---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RawColorHelper. تُنشئ لون ARGB بعمق 8‑بت لكل قناة"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

ينشئ لون ARGB بثمانية بت لكل قناة.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| a | بايت | قيمة مكوّن ألفا (0-255). |
| r | بايت | قيمة مكوّن الأحمر (0-255). |
| g | بايت | قيمة مكوّن الأخضر (0-255). |
| b | بايت | قيمة مكوّن الأزرق (0-255). |

### قيمة الإرجاع

مثال جديد [`RawColor`](../../rawcolor/) يمثل لون ARGB.

## ملاحظات

يتم حزم مكوّنات اللون في عدد صحيح 32‑بت بالترتيب: ألفا (البتات 24-31)، الأحمر (البتات 16-23)، الأخضر (البتات 8-15)، والأزرق (البتات 0-7).

### انظر أيضًا

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

ينشئ لون ARGB بثمانية بت لكل قناة من Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| drawingColor | لون | لون System.Drawing |

### قيمة الإرجاع

مثال جديد [`RawColor`](../../rawcolor/) يمثل لون ARGB.

## ملاحظات

يتم حزم مكوّنات اللون في عدد صحيح 32‑بت بالترتيب: ألفا (البتات 24-31)، الأحمر (البتات 16-23)، الأخضر (البتات 8-15)، والأزرق (البتات 0-7).

### انظر أيضًا

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


