---
title: Class ColorPalette
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.ColorPalette 班级. 定义构成调色板的颜色数组颜色是 32 位 ARGB 颜色不可继承.
type: docs
weight: 370
url: /zh/net/aspose.psd/colorpalette/
---
## ColorPalette class

定义构成调色板的颜色数组。颜色是 32 位 ARGB 颜色。不可继承.

```csharp
public sealed class ColorPalette : IColorPalette
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | 初始化一个新的实例`ColorPalette`类和 IsCompactPalette 是 false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | 初始化一个新的实例`ColorPalette`类和 IsCompactPalette 是 false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | 初始化一个新的实例`ColorPalette`类. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | 初始化一个新的实例`ColorPalette`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | 获取 32 位 ARGB 结构数组。 |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | 获取数组[`Color`](../color/)结构. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | 获取条目计数。 |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | 获取或设置一个值，指示是否使用紧凑调色板。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | 复制调色板。 |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | 复制调色板。 |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | 通过索引获取 32 位 ARGB 调色板颜色。 |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | 通过索引获取调色板颜色。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | 获取最近颜色的索引。 |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | 获取最近颜色的索引。 |

### 也可以看看

* interface [IColorPalette](../icolorpalette/)
* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


