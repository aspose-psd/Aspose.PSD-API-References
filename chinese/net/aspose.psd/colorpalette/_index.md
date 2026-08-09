---
title: "类 ColorPalette"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ColorPalette 类。定义组成调色板的颜色数组。颜色为 32 位 ARGB 颜色。不可继承"
type: docs
weight: 370
url: /zh/net/aspose.psd/colorpalette/
---
{{< psd/tize >}}
## ColorPalette class

定义组成调色板的颜色数组。这些颜色为 32 位 ARGB 颜色。不可继承。

```csharp
public sealed class ColorPalette : IColorPalette
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | 初始化 `ColorPalette` 类的新实例，且 IsCompactPalette 为 false。 |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | 初始化 `ColorPalette` 类的新实例，且 IsCompactPalette 为 false。 |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | 初始化 `ColorPalette` 类的新实例。 |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | 初始化 `ColorPalette` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 获取 32 位 ARGB 结构的数组。 |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | 获取 [`Color`](../color/) 结构的数组。 |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | 获取条目计数。 |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | 获取或设置指示是否使用紧凑调色板的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | 复制调色板。 |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | 复制调色板。 |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | 按索引获取调色板颜色。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 获取最近颜色的索引。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 获取最近颜色的索引。 |

### 另请参阅

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


