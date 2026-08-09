---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RawColorHelper. تنشئ لون ARGB بعمق 16 بت لكل قناة."
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

ينشئ لون ARGB بستة عشر بت لكل قناة.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| a | UInt16 | قيمة مكوّن ألفا (0-65535). |
| r | UInt16 | قيمة مكوّن الأحمر (0-65535). |
| g | UInt16 | قيمة مكوّن الأخضر (0-65535). |
| b | UInt16 | قيمة مكوّن الأزرق (0-65535). |

### قيمة الإرجاع

مثال جديد [`RawColor`](../../rawcolor/) يمثل لون ARGB.

## ملاحظات

مكوّنات اللون مُعبأة في عدد صحيح 64‑بت بالترتيب التالي: ألفا (بتات 48-63)، الأحمر (بتات 32-47)، الأخضر (بتات 16-31)، والأزرق (بتات 0-15).

### انظر أيضًا

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


