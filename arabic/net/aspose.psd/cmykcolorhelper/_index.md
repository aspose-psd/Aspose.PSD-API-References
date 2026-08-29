---
title: "الفئة CmykColorHelper"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.CmykColorHelper. طرق مساعدة للعمل مع لون CMYK الممثل كقيمة عدد صحيح 32‑bit موقع. توفر واجهة برمجة تطبيقات مشابهة للهيكل CmykColor. إنها أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الساكنة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل CmykColor المهجور"
type: docs
weight: 280
url: /ar/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

طرق مساعدة للعمل مع لون CMYK الممثل كقيمة عدد صحيح 32‑bit موقع. توفر واجهة برمجة تطبيقات مشابهة للهيكل [`CmykColor`](../cmykcolor/). إنها أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الساكنة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل المهجور [`CmykColor`](../cmykcolor/).

```csharp
public static class CmykColorHelper
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | ينشئ CMYK من قيم سيان، ماجنتا، أصفر وأسود 32‑bit. |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | يحصل على قيمة المكوّن السيان. |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | يحصل على قيمة المكوّن الأسود. |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | يحصل على قيمة المكوّن الماجنتا. |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | يحصل على قيمة المكوّن الأصفر. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | التحويل من لون CMYK إلى لون ARGB. |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | التحويل من لون CMYK إلى لون ARGB باستخدام تحويل Icc مع ملف تعريف مخصص. |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | التحويل من ألوان CMYK إلى ألوان ARGB باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | التحويل من لون ARGB إلى لون CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | التحويل من لون ARGB إلى لون CMYK. |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | التحويل من ألوان ARGB إلى ألوان CMYK. |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | يحوّل RGB إلى CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف افتراضية. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | التحويل من لون ARGB إلى لون CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | التحويل من ألوان ARGB إلى ألوان CMYK باستخدام تحويل Icc مع ملفات تعريف مخصصة. |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | يقوم بتحويل RGB إلى CMYK باستخدام ملفات تعريف ICC مخصصة. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


