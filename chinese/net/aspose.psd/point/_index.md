---
title: "结构体 Point"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Point 结构体。表示整数 x 和 y 坐标的有序对，定义二维平面中的一点。"
type: docs
weight: 5760
url: /zh/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

表示整数 x、y 坐标的有序对，定义二维平面上的一点。

```csharp
public struct Point
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Point](point/#constructor_1)(int) | 使用整数值指定的坐标初始化 `Point` 结构的新实例。 |
| [Point](point/#constructor)(Size) | 从 [`Size`](../size/) 结构初始化 `Point` 结构的新实例。 |
| [Point](point/#constructor_2)(int, int) | 使用指定的坐标初始化 `Point` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | 获取一个 `Point` 结构的新实例，其 [`X`](./x/) 和 [`Y`](./y/) 值设为零。 |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | 获取一个值，指示此 `Point` 是否为空。 |
| [X](../../aspose.psd/point/x/) { get; set; } | 获取或设置此 `Point` 的 x 坐标。 |
| [Y](../../aspose.psd/point/y/) { get; set; } | 获取或设置此 `Point` 的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 将指定的 [`Size`](../size/) 添加到指定的 `Point`。 |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 通过将指定的 [`PointF`](../pointf/) 的值向上取整到下一个更高的整数，将其转换为 `Point`。 |
| static [Round](../../aspose.psd/point/round/)(PointF) | 通过将 `Point` 值四舍五入到最近的整数，将指定的 [`PointF`](../pointf/) 转换为 `Point` 对象。 |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 返回从指定的 `Point` 中减去指定的 [`Size`](../size/) 的结果。 |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 通过截断 `Point` 的值，将指定的 [`PointF`](../pointf/) 转换为 `Point`。 |
| override [Equals](../../aspose.psd/point/equals/)(object) | 指定此 `Point` 是否包含与指定对象相同的坐标。 |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | 返回此 `Point` 的哈希码。 |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | 通过指定的 `Point` 平移此 `Point`。 |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | 通过指定的量平移此 `Point`。 |
| override [ToString](../../aspose.psd/point/tostring/)() | 将此 `Point` 转换为可读的字符串。 |
| [operator +](../../aspose.psd/point/op_addition/) | 通过给定的 [`Size`](../size/) 平移 `Point`。 |
| [operator ==](../../aspose.psd/point/op_equality/) | 比较两个 `Point` 对象。结果指定两个 `Point` 对象的 [`X`](./x/) 和 [`Y`](./y/) 属性的值是否相等。 |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 将指定的 `Point` 结构转换为 [`Size`](../size/) 结构。 |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 将指定的 `Point` 结构转换为 [`PointF`](../pointf/) 结构。 |
| [operator !=](../../aspose.psd/point/op_inequality/) | 比较两个 `Point` 对象。结果指定两个 `Point` 对象的 [`X`](./x/) 或 [`Y`](./y/) 属性的值是否不相等。 |
| [operator -](../../aspose.psd/point/op_subtraction/) | 通过给定的 [`Size`](../size/) 的相反值平移 `Point`。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


