---
title: "结构体 Size"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Size 结构体。表示尺寸"
type: docs
weight: 6050
url: /zh/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

表示大小。

```csharp
public struct Size
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Size](size/#constructor)(Point) | 从指定的 [`Point`](../point/) 初始化 `Size` 结构的新实例。 |
| [Size](size/#constructor_1)(int, int) | 从指定的尺寸初始化 `Size` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | 获取一个 `Size` 结构的新实例，其 [`Width`](./width/) 和 [`Height`](./height/) 值设为零。 |
| [Height](../../aspose.psd/size/height/) { get; set; } | 获取或设置此 `Size` 的垂直分量。 |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | 获取一个值，指示此 `Size` 的宽度和高度是否为 0。 |
| [Width](../../aspose.psd/size/width/) { get; set; } | 获取或设置此 `Size` 的水平分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | 将一个 `Size` 结构的宽度和高度加到另一个 `Size` 结构的宽度和高度上。 |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 通过将 `Size` 结构的值向上取整到下一个更高的整数，将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构。 |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 通过将 [`SizeF`](../sizef/) 结构的值四舍五入到最近的整数，将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构。 |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 通过将 [`SizeF`](../sizef/) 结构的值截断到下一个更低的整数，将指定的 [`SizeF`](../sizef/) 结构转换为 `Size` 结构。 |
| override [Equals](../../aspose.psd/size/equals/)(object) | 测试指定的对象是否为与此 `Size` 具有相同尺寸的 `Size`。 |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | 返回此 `Size` 结构的哈希码。 |
| override [ToString](../../aspose.psd/size/tostring/)() | 创建一个可读的字符串来表示此 `Size`。 |
| [operator +](../../aspose.psd/size/op_addition/) | 将一个 `Size` 结构的宽度和高度加到另一个 `Size` 结构的宽度和高度上。 |
| [operator ==](../../aspose.psd/size/op_equality/) | 测试两个 `Size` 结构是否相等。 |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 将指定的 `Size` 转换为 [`Point`](../point/)。 |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 将指定的 `Size` 转换为 [`SizeF`](../sizef/)。 |
| [operator !=](../../aspose.psd/size/op_inequality/) | 测试两个 `Size` 结构是否不同。 |
| [operator -](../../aspose.psd/size/op_subtraction/) | 从另一个 `Size` 结构的宽度和高度中减去一个 `Size` 结构的宽度和高度。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


