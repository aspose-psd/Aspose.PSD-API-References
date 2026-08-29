---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة RasterCachedImage. تغيير حجم الصورة"
type: docs
weight: 120
url: /ar/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

يعيد تحجيم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

يعيد تحجيم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات تغيير الحجم. |

### انظر أيضًا

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


