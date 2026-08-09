---
title: "类 CmykColorHelper"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.CmykColorHelper 类。帮助方法用于处理以有符号 32 位整数值表示的 CMYK 颜色。提供与 CmykColor 结构相似的 API。由于 CMYK 颜色仅作为 Int32 而不是具有内部字段的结构呈现，因而更轻量。请在可能时优先使用此类的静态方法，而不是已弃用的 CmykColor 结构。"
type: docs
weight: 280
url: /zh/net/aspose.psd/cmykcolorhelper/
---
{{< psd/tize >}}
## CmykColorHelper class

帮助方法用于处理以有符号 32 位整数值表示的 CMYK 颜色。提供与 [`CmykColor`](../cmykcolor/) 结构相似的 API。由于 CMYK 颜色仅作为 Int32 而不是具有内部字段的结构呈现，因而更轻量。请在可能时优先使用此类的静态方法，而不是已弃用的 [`CmykColor`](../cmykcolor/) 结构。

```csharp
public static class CmykColorHelper
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromComponents](../../aspose.psd/cmykcolorhelper/fromcomponents/)(int, int, int, int) | 根据 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| static [GetC](../../aspose.psd/cmykcolorhelper/getc/)(int) | 获取青色分量值。 |
| static [GetK](../../aspose.psd/cmykcolorhelper/getk/)(int) | 获取黑色分量值。 |
| static [GetM](../../aspose.psd/cmykcolorhelper/getm/)(int) | 获取品红分量值。 |
| static [GetY](../../aspose.psd/cmykcolorhelper/gety/)(int) | 获取黄色分量值。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb)(int) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb](../../aspose.psd/cmykcolorhelper/toargb/#toargb_1)(int[]) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgb32](../../aspose.psd/cmykcolorhelper/toargb32/)(int[]) | CMYK 颜色到 ARGB 颜色的转换。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc)(int) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_2)(int[]) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_1)(int, Stream, Stream) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToArgbIcc](../../aspose.psd/cmykcolorhelper/toargbicc/#toargbicc_3)(int[], Stream, Stream) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk)(Color) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_2)(Color[]) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_1)(int) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmyk](../../aspose.psd/cmykcolorhelper/tocmyk/#tocmyk_3)(int[]) | ARGB 颜色到 CMYK 颜色的转换。 |
| static [ToCmykBytes](../../aspose.psd/cmykcolorhelper/tocmykbytes/)(int[], int, int) | 将 RGB 转换为 CMYK。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc)(Color) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_2)(Color[]) | 使用默认配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_1)(Color, Stream, Stream) | 使用自定义配置文件的 ICC 转换，将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIcc](../../aspose.psd/cmykcolorhelper/tocmykicc/#tocmykicc_3)(Color[], Stream, Stream) | 使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。 |
| static [ToCmykIccBytes](../../aspose.psd/cmykcolorhelper/tocmykiccbytes/)(int[], int, int, Stream, Stream) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


