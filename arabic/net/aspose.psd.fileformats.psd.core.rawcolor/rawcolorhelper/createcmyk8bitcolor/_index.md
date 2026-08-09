---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RawColorHelper. تنشئ لون CMYK بعمق 8 بت لكل قناة."
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

ينشئ لون CMYK بعمق 8 بت لكل قناة.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| c | بايت | قيمة مكوّن السماوي (0-255). |
| m | بايت | قيمة مكوّن الأرجواني (0-255). |
| y | بايت | قيمة مكوّن الأصفر (0-255). |
| k | بايت | قيمة مكوّن المفتاح (الأسود) (0-255). |

### قيمة الإرجاع

مثال جديد [`RawColor`](../../rawcolor/) يمثل لون CMYK.

## ملاحظات

مكوّنات اللون مُعبأة في عدد صحيح 32‑بت بالترتيب التالي: السماوي (بتات 24-31)، الأرجواني (بتات 16-23)، الأصفر (بتات 8-15)، والمفتاح/الأسود (بتات 0-7).

### انظر أيضًا

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


