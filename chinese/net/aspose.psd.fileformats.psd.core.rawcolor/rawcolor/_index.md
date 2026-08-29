---
title: "类 RawColor"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor 类。Raw Color 类用于存储任意通道数、任意颜色模式和任意位深的颜色。请注意，一些内部类在将 RawColor 转换为其原生格式时可能会出现问题，因此如果 API 为您提供 CMYK 颜色，使用提供的格式更可靠。此外，在某些情况下 Raw Color 也可以被转换。"
type: docs
weight: 1650
url: /zh/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

Raw Color Class 用于存储任意通道数、任意颜色模式和任意位深的颜色。请注意，某些内部类在将 RawColor 转换为其本机格式时可能会出现问题，因此如果 API 为您提供 CMYK 颜色，使用提供的格式更可靠。此外，在某些情况下也可以转换 Raw Color。

```csharp
public sealed class RawColor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | 初始化 `RawColor` 类的新实例。 |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | 使用预定义的颜色模式，从像素数据格式初始化 `RawColor` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | 颜色应遵循的模式。 |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | 获取颜色的组成部分。每个组成部分是独立的通道，如果使用不常见的配色方案，最好分别处理每个通道。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | 在可能的情况下，以 int 形式获取颜色。 |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | 在可能的情况下，以 long 形式获取颜色。 |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | 获取 Raw Color 的位深。例如，ARGB 颜色每通道/组件 8 位时位深为 32 位；完整的 ARGB 颜色每通道/组件 16 位时位深为 64 位。位深是各通道位深之和。如果不同通道的位深不同，也可以实现。 |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | 获取颜色模式的名称。颜色模式名称由通道/组件的名称组合而成。 |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | 获取当前对象的哈希码。 |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | 如果可能，从 int 参数为所有通道设置数据。 |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | 如果可能，从 int 参数为所有通道设置数据。 |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | 实现运算符 !=。 |

## 示例

以下代码演示了使用 RawColor 类而不是已废弃的 Color 结构的支持。

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


