---
title: "التعداد ResizeType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.ResizeType. يحدد نوع التحجيم."
type: docs
weight: 5870
url: /ar/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

يحدد نوع تغيير الحجم.

```csharp
public enum ResizeType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لا يتم الحفاظ على البكسلات أثناء عملية التحجيم. |
| LeftTopToLeftTop | `1` | النقطة اليسرى العليا للصورة الجديدة ستتطابق مع النقطة اليسرى العليا للصورة الأصلية. سيُجرى القص إذا لزم الأمر. |
| RightTopToRightTop | `2` | النقطة اليمنى العليا للصورة الجديدة ستتطابق مع النقطة اليمنى العليا للصورة الأصلية. سيُجرى القص إذا لزم الأمر. |
| RightBottomToRightBottom | `3` | النقطة اليمنى السفلية للصورة الجديدة ستتطابق مع النقطة اليمنى السفلية للصورة الأصلية. سيُجرى القص إذا لزم الأمر. |
| LeftBottomToLeftBottom | `4` | النقطة اليسرى السفلية للصورة الجديدة ستتطابق مع النقطة اليسرى السفلية للصورة الأصلية. سيتم القص إذا لزم الأمر. |
| CenterToCenter | `5` | مركز الصورة الجديدة سيتطابق مع مركز الصورة الأصلية. سيتم القص إذا لزم الأمر. |
| LanczosResample | `6` | إعادة العينة باستخدام خوارزمية لانكوز مع a=3. |
| NearestNeighbourResample | `7` | إعادة العينة باستخدام خوارزمية أقرب جار. |
| AdaptiveResample | `8` | إعادة العينة باستخدام خوارزمية تكيفية تعتمد على دالة كسرية موزونة وممزوجة وخوارزميات استيفاء لانكوز3. |
| BilinearResample | `9` | إعادة العينة باستخدام استيفاء ثنائي الخطية. يُسمح بتمهيد الصورة مسبقًا لإزالة الضوضاء قبل إعادة العينة، عند الحاجة. |
| HighQualityResample | `10` | إعادة العينة عالية الجودة |
| CatmullRom | `11` | طريقة الاستيفاء المكعب Catmull-Rom. |
| CubicConvolution | `12` | طريقة الاستيفاء المكعب Cubic Convolution |
| CubicBSpline | `13` | طريقة الاستيفاء المكعب CubicBSpline |
| Mitchell | `14` | طريقة الاستيفاء المكعب Mitchell |
| SinC | `15` | طريقة الاستيفاء المكعب Sinc (Lanczos3) |
| Bell | `16` | طريقة الاستيفاء Bell |

## أمثلة

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

الكود التالي يوضح كيفية تغيير حجم صورة باستخدام نوع تغيير حجم جديد CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


