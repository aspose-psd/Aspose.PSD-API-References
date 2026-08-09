---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة CmykColorHelper. تقوم بتحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة"
type: docs
weight: 120
url: /ar/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

يقوم بتحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | Int32[] | ألوان RGB المقدمة كقيم صحيحة 32‑بت. |
| startIndex | Int32 | فهرس البدء للون RGB. |
| الطول | Int32 | عدد بكسلات RGB التي سيتم تحويلها. |
| rgbIccStream | Stream | دفق ملف تعريف RGB. |
| cmykIccStream | Stream | دفق ملف تعريف CMYK. |

### قيمة الإرجاع

ألوان CMYK المقدمة كمصفوفة بايت.

### انظر أيضًا

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


