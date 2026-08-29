---
title: "结构体 SizeF"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.SizeF 结构体。存储一对有序的浮点数，通常表示矩形的宽度和高度。"
type: docs
weight: 6060
url: /zh/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

存储一对有序的浮点数，通常表示矩形的宽度和高度。

```csharp
public struct SizeF
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | 从指定的 [`PointF`](../pointf/) 初始化 `SizeF` 结构的新实例。 |
| [SizeF](sizef/#constructor_1)(SizeF) | 从指定的 `SizeF` 初始化 `SizeF` 结构的新实例。 |
| [SizeF](sizef/#constructor_2)(float, float) | 从指定的尺寸初始化 `SizeF` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | 获取一个 `SizeF` 结构的新实例，其 [`Width`](./width/) 和 [`Height`](./height/) 值设为零。 |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | 获取或设置此 `SizeF` 的垂直分量。 |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | 获取一个值，指示此 `SizeF` 的宽度和高度是否为零。 |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | 获取或设置此 `SizeF` 的水平分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | 将一个 `SizeF` 结构的宽度和高度添加到另一个 `SizeF` 结构的宽度和高度。 |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | 从另一个 `SizeF` 结构的宽度和高度中减去一个 `SizeF` 结构的宽度和高度。 |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 测试指定的对象是否为具有与此 `SizeF` 相同尺寸的 `SizeF`。 |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | 返回此 [`Size`](../size/) 结构的哈希码。 |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | 将 `SizeF` 转换为 [`PointF`](../pointf/)。 |
| [ToSize](../../aspose.psd/sizef/tosize/)() | 将 `SizeF` 转换为具有截断尺寸值的 [`Size`](../size/) 结构。 |
| override [ToString](../../aspose.psd/sizef/tostring/)() | 创建一个可读的字符串，表示此 `SizeF`。 |
| [operator +](../../aspose.psd/sizef/op_addition/) | 将一个 `SizeF` 结构的宽度和高度添加到另一个 `SizeF` 结构的宽度和高度。 |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 测试两个 `SizeF` 结构是否相等。 |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 将指定的 `SizeF` 转换为 [`PointF`](../pointf/)。 |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 测试两个 `SizeF` 结构是否不同。 |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | 从另一个 `SizeF` 结构的宽度和高度中减去一个 `SizeF` 结构的宽度和高度。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


