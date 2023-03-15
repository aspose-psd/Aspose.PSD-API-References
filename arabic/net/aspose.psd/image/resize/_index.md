---
title: Image.Resize
second_title: Aspose.PSD لمرجع .NET API
description: Image طريقة. تغيير حجم الصورة .
type: docs
weight: 190
url: /ar/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

تغيير حجم الصورة .

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد . |
| newHeight | Int32 | الارتفاع الجديد . |
| resizeType | ResizeType | نوع تغيير الحجم . |

### أنظر أيضا

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم .

```csharp
public void Resize(int newWidth, int newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد . |
| newHeight | Int32 | الارتفاع الجديد . |

### أمثلة

يوضح المثال التالي كيفية تغيير حجم صورة PSD والنتيجة التي نحصل عليها بواسطة Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

تغيير حجم الصورة .

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير الحجم. |

### أنظر أيضا

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* مساحة الاسم [Aspose.PSD](../../image/)
* المجسم [Aspose.PSD](../../../)


