---
title: "结构体 CmykColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.CmykColor 结构体。像素的 CMYK 颜色"
type: docs
weight: 270
url: /zh/net/aspose.psd/cmykcolor/
---
{{< psd/tize >}}
## CmykColor structure

像素的 CMYK 颜色。

```csharp
public struct CmykColor
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/cmykcolor/empty/) { get; } | 获取空值。 |
| [C](../../aspose.psd/cmykcolor/c/) { get; } | 获取此 [`Color`](../color/) 结构的青色分量值。 |
| [IsEmpty](../../aspose.psd/cmykcolor/isempty/) { get; } | 获取一个值，指示此 [`Color`](../color/) 结构是否未初始化。 |
| [K](../../aspose.psd/cmykcolor/k/) { get; } | 获取此 [`Color`](../color/) 结构的黑色分量值。 |
| [M](../../aspose.psd/cmykcolor/m/) { get; } | 获取此 [`Color`](../color/) 结构的品红分量值。 |
| [Y](../../aspose.psd/cmykcolor/y/) { get; } | 获取此 [`Color`](../color/) 结构的黄色分量值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromParams](../../aspose.psd/cmykcolor/fromparams/)(int, int, int, int) | 从 32 位青色、品红、黄色和黑色值创建一个 `CmykColor` 结构。此方法已弃用。请使用更有效的 [`FromComponents`](../cmykcolorhelper/fromcomponents/)。 |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk)(int) | 从 32 位 ARGB 转换为 CMYKColor。此方法已弃用。请使用更有效的 [`ToCmyk`](../cmykcolorhelper/tocmyk/)。 |
| override [Equals](../../aspose.psd/cmykcolor/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| override [GetHashCode](../../aspose.psd/cmykcolor/gethashcode/)() | 获取哈希码。 |
| [ToValue](../../aspose.psd/cmykcolor/tovalue/)() | 获取值。 |
| static [ToArgb32](../../aspose.psd/cmykcolor/toargb32/)(CmykColor[]) | 使用默认配置文件的 ICC 转换，将 CMYKColor 转换为 32 位 ARGB 颜色。此方法已弃用。请使用更有效的 [`ToArgb32`](../cmykcolorhelper/toargb32/)。 |
| static [ToCmyk](../../aspose.psd/cmykcolor/tocmyk/#tocmyk_1)(int[]) | 将 32 位 ARGB 颜色转换为 CMYKColor。此方法已弃用。请使用更有效的 [`ToCmyk`](../cmykcolorhelper/tocmyk/)。 |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor)(CmykColor) | 将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgb`](../cmykcolorhelper/toargb/)。 |
| static [ToColor](../../aspose.psd/cmykcolor/tocolor/#tocolor_1)(CmykColor[]) | 使用默认配置文件的 ICC 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgb`](../cmykcolorhelper/toargb/)。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc)(CmykColor) | 使用默认配置文件的 ICC 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_2)(CmykColor[]) | 使用默认配置文件的 ICC 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_1)(CmykColor, Stream, Stream) | 使用 ICC 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)。 |
| static [ToColorIcc](../../aspose.psd/cmykcolor/tocoloricc/#tocoloricc_3)(CmykColor[], Stream, Stream) | 使用 ICC 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 [`ToArgbIcc`](../cmykcolorhelper/toargbicc/)。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


