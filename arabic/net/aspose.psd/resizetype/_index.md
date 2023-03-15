---
title: Enum ResizeType
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ResizeType تعداد. يحدد نوع تغيير الحجم.
type: docs
weight: 5370
url: /ar/net/aspose.psd/resizetype/
---
## ResizeType enumeration

يحدد نوع تغيير الحجم.

```csharp
public enum ResizeType
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| None | `0` | لا يتم الاحتفاظ بالبكسل أثناء عملية تغيير الحجم. |
| LeftTopToLeftTop | `1` | ستتزامن النقطة العلوية اليسرى للصورة الجديدة مع النقطة العلوية اليسرى للصورة الأصلية. سيحدث المحاصيل إذا لزم الأمر. |
| RightTopToRightTop | `2` | ستتزامن النقطة العلوية اليمنى للصورة الجديدة مع النقطة العلوية اليمنى للصورة الأصلية. سيحدث المحاصيل إذا لزم الأمر. |
| RightBottomToRightBottom | `3` | ستتزامن النقطة السفلية اليمنى للصورة الجديدة مع النقطة السفلية اليمنى للصورة الأصلية. سيحدث المحاصيل إذا لزم الأمر. |
| LeftBottomToLeftBottom | `4` | ستتزامن النقطة السفلية اليسرى للصورة الجديدة مع النقطة السفلية اليسرى للصورة الأصلية. سيحدث المحاصيل إذا لزم الأمر. |
| CenterToCenter | `5` | سيتزامن مركز الصورة الجديدة مع مركز الصورة الأصلية. سيحدث المحاصيل إذا لزم الأمر. |
| LanczosResample | `6` | إعادة تشكيل العينة باستخدام خوارزمية lanczos مع = 3. |
| NearestNeighbourResample | `7` | إعادة تشكيل العينة باستخدام أقرب خوارزمية مجاورة. |
| AdaptiveResample | `8` | إعادة تشكيل العينة باستخدام الخوارزمية التكيفية بناءً على الوظيفة المنطقية الموزونة والمختلطة وخوارزميات الاستيفاء lanczos3. |
| BilinearResample | `9` | إعادة تشكيل العينة باستخدام الاستيفاء ثنائي الخطوط. يُسمح بالترشيح المسبق للصور لإزالة الضوضاء قبل إعادة التشكيل ، عند الحاجة |
| HighQualityResample | `10` | جودة عالية resample |
| CatmullRom | `11` | طريقة الاستيفاء المكعب Catmull-Rom . |
| CubicConvolution | `12` | طريقة الاستيفاء التكعيبية الملتوية |
| CubicBSpline | `13` | طريقة الاستيفاء التكعيبي في خط التكعيب |
| Mitchell | `14` | طريقة الاستيفاء مكعب ميتشل |
| SinC | `15` | طريقة الاستيفاء التكعيبي Sinc (Lanczos3 ) |
| Bell | `16` | طريقة الاستيفاء بيل |

### أمثلة

يوضح الكود التالي كيفية تغيير حجم صورة باستخدام نوع تغيير حجم SinC جديد.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

يوضح الكود التالي كيفية تغيير حجم الصورة باستخدام نوع Bell جديد لتغيير الحجم.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

يوضح الكود التالي كيفية تغيير حجم الصورة بنوع Mitchell الجديد لتغيير الحجم.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

يوضح الكود التالي كيفية تغيير حجم الصورة بنوع تغيير حجم CatmullRom الجديد.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

يوضح الكود التالي كيفية تغيير حجم صورة بنوع جديد لتغيير حجم خط CubicBS.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

يوضح الكود التالي كيفية تغيير حجم صورة بنوع جديد لتغيير حجم CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


