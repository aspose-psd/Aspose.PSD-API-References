---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية GifOptions. تحصل أو تعين نسبة أبعاد بكسل GIF"
type: docs
weight: 90
url: /ar/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

يحصل أو يضبط نسبة أبعاد بكسل GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

نسبة أبعاد بكسل GIF.

## ملاحظات

نسبة أبعاد البكسل - عامل يُستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: النسبة = (نسبة أبعاد البكسل + 15) / 64 تُعرّف نسبة أبعاد البكسل بأنها ناتج قسمة عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - قيمة تُستخدم في الحساب.

### انظر أيضًا

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


