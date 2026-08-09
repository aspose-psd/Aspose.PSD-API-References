---
title: "الفئة ColorPalette"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.ColorPalette. تُعرّف مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32‑بت. غير قابلة للوراثة"
type: docs
weight: 370
url: /ar/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32-بت. غير قابل للوراثة.

```csharp
public sealed class ColorPalette : IColorPalette
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | يُنشئ مثيلاً جديداً من الفئة `ColorPalette` وتكون الخاصية IsCompactPalette غير صحيحة. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | يُنشئ مثيلاً جديداً من الفئة `ColorPalette` وتكون الخاصية IsCompactPalette غير صحيحة. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | يُنشئ مثيلاً جديداً من الفئة `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | يُنشئ مثيلاً جديداً من الفئة `ColorPalette`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | يحصل على مصفوفة من هياكل ARGB 32‑بت. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | يحصل على مصفوفة من هياكل [`Color`](../color/). |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | يحصل على عدد الإدخالات. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | ينسخ لوحة الألوان. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | ينسخ لوحة الألوان. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | يحصل على لون لوحة ARGB 32‑بت حسب الفهرس. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | يحصل على لون لوحة الألوان حسب الفهرس. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | يحصل على فهرس أقرب لون. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | يحصل على فهرس أقرب لون. |

### انظر أيضًا

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


