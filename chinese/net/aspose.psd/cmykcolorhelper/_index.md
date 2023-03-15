---
title: Class CmykColorHelper
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.CmykColorHelper 班级. 辅助方法使用 CMYK 颜色作为带符号的 32 位整数值 提供与CmykColorstruct. 它更轻量级因为 CMYK 颜色以 Int32 形式呈现而不是具有内部字段的结构 请尽可能使用此类的静态方法而不是 deprecated CmykColor结构.
type: docs
weight: 280
url: /zh/net/aspose.psd/cmykcolorhelper/
---
## CmykColorHelper class

辅助方法使用 CMYK 颜色作为带符号的 32 位整数值。 提供与[`CmykColor`](../cmykcolor/)struct. 它更轻量级，因为 CMYK 颜色以 Int32 形式呈现，而不是具有内部字段的结构。 请尽可能使用此类的静态方法，而不是 deprecated [`CmykColor`](../cmykcolor/)结构.

```csharp
public static class CmykColorHelper
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 从 32 位青色、品红色、黄色和黑色值创建 CMYK。 |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | 获取青色分量值。 |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | 获取黑色分量值。 |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | 获取洋红色分量值。 |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | 获取黄色分量值。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | 从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | 使用带有默认配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | 使用带默认配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | 使用带有自定义配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | 使用带有自定义配置文件的 Icc 转换从 CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | 从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | 将 RGB 转换为 CMYK. |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | 使用带默认配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | 使用带默认配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | 使用带有自定义配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | 使用带有自定义配置文件的 Icc 转换从 ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


