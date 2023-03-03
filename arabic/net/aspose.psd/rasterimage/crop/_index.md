---
title: RasterImage.Crop
second_title: Aspose.PSD لمرجع .NET API
description: RasterImage طريقة. يقطع المستطيل المحدد .
type: docs
weight: 240
url: /ar/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

يقطع المستطيل المحدد .

```csharp
public virtual void Crop(Rectangle rectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rectangle | Rectangle | المستطيل. |

### أمثلة

يوضح مثال الكود التالي كيفية اقتصاص صورة وحفظها.

```csharp
[C#]

// تنفيذ طريقة القص الصحيحة لملفات PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* مساحة الاسم [Aspose.PSD](../../rasterimage/)
* المجسم [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

اقتصاص الصورة مع التحولات .

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| leftShift | Int32 | التحول الأيسر. |
| rightShift | Int32 | التحول الصحيح. |
| topShift | Int32 | التحول الأعلى. |
| bottomShift | Int32 | التحول السفلي. |

### أنظر أيضا

* class [RasterImage](../)
* مساحة الاسم [Aspose.PSD](../../rasterimage/)
* المجسم [Aspose.PSD](../../../)


