---
title: "结构体 Rectangle"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Rectangle 结构体。存储一组表示矩形位置和大小的四个整数。"
type: docs
weight: 5840
url: /zh/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

存储表示矩形位置和大小的四个整数。

```csharp
public struct Rectangle
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | 使用指定的位置和大小初始化 `Rectangle` 结构的新实例。 |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | 使用指定的位置和大小初始化 `Rectangle` 结构的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | 获取一个 `Rectangle` 结构的新实例，其 [`X`](./x/)、[`Y`](./y/)、[`Width`](./width/) 和 [`Height`](./height/) 值均为零。 |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | 获取或设置此 `Rectangle` 结构的 y 坐标，该坐标为 [`Y`](./y/) 和 [`Height`](./height/) 属性值的和。 |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | 获取或设置此 `Rectangle` 结构的高度。 |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | 获取一个值，指示此 `Rectangle` 的所有数值属性是否为零。 |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | 获取或设置此 `Rectangle` 结构左边缘的 x 坐标。 |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的坐标。 |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | 获取或设置此 `Rectangle` 结构的 x 坐标，该坐标为 [`X`](./x/) 和 [`Width`](./width/) 属性值的和。 |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | 获取或设置此 `Rectangle` 的大小。 |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | 获取或设置此 `Rectangle` 结构顶部边缘的 y 坐标。 |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | 获取或设置此 `Rectangle` 结构的宽度。 |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 x 坐标。 |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | 获取或设置此 `Rectangle` 结构左上角的 y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 结构转换为 `Rectangle` 结构，方法是将 [`RectangleF`](../rectanglef/) 的值向上取整到下一个整数值。 |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | 使用指定的边缘位置创建一个 `Rectangle` 结构。 |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | 根据指定的两个点创建一个新的 `Rectangle`。创建的 `Rectangle` 的两个垂直边将等于传入的 *point1* 和 *point2*。这些通常是相对的顶点。 |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | 创建并返回指定 `Rectangle` 结构的膨胀副本。副本按指定的量进行膨胀。原始 `Rectangle` 结构保持不变。 |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | 返回一个第三个 `Rectangle` 结构，表示两个其他 `Rectangle` 结构的交集。如果没有交集，则返回一个空的 `Rectangle`。 |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 转换为 `Rectangle`，方法是将 [`RectangleF`](../rectanglef/) 的值四舍五入到最近的整数。 |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | 将指定的 [`RectangleF`](../rectanglef/) 转换为 `Rectangle`，方法是截断 [`RectangleF`](../rectanglef/) 的值。 |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | 获取一个包含两个 `Rectangle` 结构并集的 `Rectangle` 结构。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | 确定指定的点是否位于此 `Rectangle` 结构内部。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | 确定由 *rect* 表示的矩形区域是否完全包含在此 `Rectangle` 结构中。 |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | 确定指定的点是否位于此 `Rectangle` 结构内部。 |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | 测试 *obj* 是否为具有与此 `Rectangle` 结构相同位置和大小的 `Rectangle` 结构。 |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | 返回此 `Rectangle` 结构的哈希码。 |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | 按指定的量膨胀此 `Rectangle`。 |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | 按指定的量膨胀此 `Rectangle`。 |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | 用此 `Rectangle` 与指定 `Rectangle` 的交集替换此 `Rectangle`。 |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | 确定此矩形是否与 *rect* 相交。 |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | 通过使宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | 按指定的量调整此矩形的位置。 |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | 按指定的量调整此矩形的位置。 |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | 将此 `Rectangle` 的属性转换为可读的字符串。 |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | 测试两个 `Rectangle` 结构的位置和大小是否相等。 |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | 测试两个 `Rectangle` 结构的位置或大小是否不同。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


