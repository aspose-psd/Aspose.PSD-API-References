---
title: "Image.Resize"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Image. تعيد تحجيم الصورة"
type: docs
weight: 200
url: /ar/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

يعيد تحجيم الصورة.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### انظر أيضًا

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

يعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي.

```csharp
public void Resize(int newWidth, int newHeight)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |

## أمثلة

يوضح المثال التالي كيفية تحجيم صورة PSD والنتيجة التي نحصل عليها باستخدام Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

يعيد تحجيم الصورة.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات تغيير الحجم. |

### انظر أيضًا

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


