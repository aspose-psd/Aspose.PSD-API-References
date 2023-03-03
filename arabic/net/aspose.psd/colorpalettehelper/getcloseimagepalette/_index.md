---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD لمرجع .NET API
description: ColorPaletteHelper طريقة. الحصول على لوحة ألوان من الصورة النقطية palletizes image في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة  سيتم استخدامها بدلاً من إجراء الحسابات.
type: docs
weight: 60
url: /ar/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* مساحة الاسم [Aspose.PSD](../../colorpalettehelper/)
* المجسم [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* مساحة الاسم [Aspose.PSD](../../colorpalettehelper/)
* المجسم [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |
| useImagePalette | Boolean | إذا تم ضبطه ، فسيستخدم لوحة الصور الخاصة به إذا كان ذلك متاحًا |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* مساحة الاسم [Aspose.PSD](../../colorpalettehelper/)
* المجسم [Aspose.PSD](../../../)


