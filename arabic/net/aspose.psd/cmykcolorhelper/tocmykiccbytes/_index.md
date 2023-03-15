---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD لمرجع .NET API
description: CmykColorHelper طريقة. يحول RGB إلى CMYK باستخدام ملفات تعريف ICC المخصصة.
type: docs
weight: 120
url: /ar/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

يحول RGB إلى CMYK باستخدام ملفات تعريف ICC المخصصة.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pixels | Int32[] | يتم تقديم ألوان RGB كقيم عدد صحيح 32 بت. |
| startIndex | Int32 | مؤشر البداية للون RGB. |
| length | Int32 | عدد وحدات بكسل RGB المراد تحويلها. |
| rgbIccStream | Stream | دفق ملف تعريف RGB. |
| cmykIccStream | Stream | دفق ملف تعريف CMYK. |

### قيمة الإرجاع

يتم تقديم ألوان CMYK كمصفوفة بايت.

### أنظر أيضا

* class [CmykColorHelper](../)
* مساحة الاسم [Aspose.PSD](../../cmykcolorhelper/)
* المجسم [Aspose.PSD](../../../)


