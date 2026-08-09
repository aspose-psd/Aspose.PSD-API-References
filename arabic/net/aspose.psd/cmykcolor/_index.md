---
title: "الهيكل CmykColor"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الهيكل Aspose.PSD.CmykColor. لون CMYK للبكسل"
type: docs
weight: 270
url: /ar/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

لون CMYK للبكسل.

```csharp
public struct CmykColor
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | يحصل على الفارغ. |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | يحصل على قيمة المكوّن السماوي لهذا الهيكل [`Color`](../color/). |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بنية [`Color`](../color/) هذه غير مهيأة. |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | يحصل على قيمة المكوّن الأسود لهذه بنية [`Color`](../color/). |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | يحصل على قيمة المكوّن الأرجواني لهذه بنية [`Color`](../color/). |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | يحصل على قيمة المكوّن الأصفر لهذه بنية [`Color`](../color/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | ينشئ بنية `CmykColor` من قيم السِّما، الأرجواني، الأصفر والأسود 32-بت. هذه الطريقة مهجورة. يرجى استخدام [`FromComponents`](../cmykcolorhelper/fromcomponents/) الأكثر فاعلية. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | التحويل من ARGB 32-بت إلى CMYKColor. هذه الطريقة مهجورة. يرجى استخدام [`ToCmyk`](../cmykcolorhelper/tocmyk/) الأكثر فاعلية. |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذا المثيل. |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | الحصول على رمز التجزئة. |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | القيمة إلى. |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | التحويل من CMYKColor إلى لون ARGB 32-بت باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام [`ToArgb32`](../cmykcolorhelper/toargb32/) الأكثر فاعلية. |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | التحويل من لون ARGB 32-بت إلى CMYKColor. هذه الطريقة مهجورة. يرجى استخدام [`ToCmyk`](../cmykcolorhelper/tocmyk/) الأكثر فاعلية. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | التحويل من CMYKColor إلى Color. هذه الطريقة مهجورة. يرجى استخدام [`ToArgb`](../cmykcolorhelper/toargb/) الأكثر فاعلية. |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام [`ToArgb`](../cmykcolorhelper/toargb/) الأكثر فاعلية. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) الأكثر فاعلية. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | التحويل من CMYKColor إلى Color باستخدام تحويل icc مع ملفات تعريف افتراضية. هذه الطريقة مهجورة. يرجى استخدام [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) الأكثر فاعلية. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | التحويل من CMYKColor إلى Color باستخدام تحويل icc. هذه الطريقة مهجورة. يرجى استخدام [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) الأكثر فاعلية. |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | التحويل من CMYKColor إلى Color باستخدام تحويل icc. هذه الطريقة مهجورة. يرجى استخدام [`ToArgbIcc`](../cmykcolorhelper/toargbicc/) الأكثر فاعلية. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


