---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RawColorHelper. تنشئ لون CMYK بعمق 16 بت لكل قناة."
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

ينشئ لون CMYK بعمق 16 بت لكل قناة.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| c | UInt16 | قيمة مكوّن السماوي (0-65535). |
| m | UInt16 | قيمة مكوّن الأرجواني (0-65535). |
| y | UInt16 | قيمة مكوّن الأصفر (0-65535). |
| k | UInt16 | قيمة مكوّن المفتاح (الأسود) (0-65535). |

### قيمة الإرجاع

مثال جديد [`RawColor`](../../rawcolor/) يمثل لون CMYK.

## ملاحظات

يتم حزم مكوّنات اللون في عدد صحيح 64‑بت بالترتيب: السماوي (البتات 48-63)، الأرجواني (البتات 32-47)، الأصفر (البتات 16-31)، والمفتاح/الأسود (البتات 0-15).

### انظر أيضًا

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


