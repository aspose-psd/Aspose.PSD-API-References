---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ColorPaletteHelper. تحصل على لوحة ألوان من صورة نقطية تقوم بإنشاء لوحة ألوان للصورة إذا لم تكن لديها واحدة. في حال وجود لوحة ألوان سيتم استخدامها بدلاً من إجراء الحسابات"
type: docs
weight: 60
url: /ar/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة للصور. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | RasterImage | صورة نقطية. |
| entriesCount | Int32 | عدد المدخلات المطلوب. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *image* وتحتوي على *entriesCount* مدخلًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة للصور. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | RasterImage | صورة نقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد المدخلات المطلوب. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *image* وتحتوي على *entriesCount* مدخلًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة ألوان للصورة) في حال عدم وجود لوحة للصور. إذا كانت اللوحة موجودة سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | RasterImage | صورة نقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد المدخلات المطلوب. |
| useImagePalette | Boolean | إذا تم الضبط، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متوفرة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *image* وتحتوي على *entriesCount* مدخلًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


