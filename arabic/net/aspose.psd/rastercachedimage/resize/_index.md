---
title: RasterCachedImage.Resize
second_title: Aspose.PSD لمرجع .NET API
description: RasterCachedImage طريقة. تغيير حجم الصورة .
type: docs
weight: 120
url: /ar/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

تغيير حجم الصورة .

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* مساحة الاسم [Aspose.PSD](../../rastercachedimage/)
* المجسم [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

تغيير حجم الصورة .

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير الحجم. |

### أنظر أيضا

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* مساحة الاسم [Aspose.PSD](../../rastercachedimage/)
* المجسم [Aspose.PSD](../../../)


