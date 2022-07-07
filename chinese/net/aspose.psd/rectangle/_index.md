---
title: Rectangle
second_title: Aspose.PSD for .NET API 参考
description: 存储一组四个整数表示矩形的位置和大小
type: docs
weight: 5220
url: /zh/net/aspose.psd/rectangle/
---
## Rectangle structure

存储一组四个整数，表示矩形的位置和大小。

```csharp
public struct Rectangle
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | 用指定的位置和大小初始化[`Rectangle`](../rectangle)结构的新实例。 |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | 用指定的位置和大小初始化[`Rectangle`](../rectangle)结构的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | 获取具有[`X`](./x)的[`Rectangle`](../rectangle)结构的新实例，[`Y`](./y)、[`Width`](./width)和[`Height`](./height)值设置为零. |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | 获取或设置 y 坐标，它是[`Y`](./y)和PSD之和。此[`Rectangle`](../rectangle) 结构的 Rectangle.Height属性值。 |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的高度。 |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | 获取一个值，该值指示此[`Rectangle`](../rectangle)的所有数字属性是否具有零值。 |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左边缘的 x 坐标。 |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左上角的坐标。 |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | 获取或设置 x 坐标，它是[`X`](./x)和Rectangle之和此[`Rectangle`](../rectangle) 结构的.Width属性值。 |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)的大小。 |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的上边缘的 y 坐标。 |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构的宽度。 |
| [X](../../aspose.psd/rectangle/x) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左上角的 x 坐标。 |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | 获取或设置此[`Rectangle`](../rectangle)结构左上角的 y 坐标。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | 通过舍入[`RectangleF`](../rectanglef) 将指定的[`RectangleF`](../rectanglef)结构转换为[`Rectangle`](../rectangle)结构值到下一个更高的整数值。 |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | 创建具有指定边缘位置的[`Rectangle`](../rectangle)结构。 |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | 从指定的两个点创建一个新的[`Rectangle`](../rectangle)。创建的[`Rectangle`](../rectangle)的两个垂直将等于传递的*point1*和*point2*。这些通常是相反的顶点。 |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | 创建并返回指定[`Rectangle`](../rectangle)结构的膨胀副本。副本按指定的数量膨胀。原始的[`Rectangle`](../rectangle)结构保持不变。 |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | 返回第三个[`Rectangle`](../rectangle)结构，它表示两个其他[`Rectangle`](../rectangle)结构的交集。如果没有交集，则返回一个空的[`Rectangle`](../rectangle)。 |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | 通过舍入T将指定的[`RectangleF`](../rectanglef) 转换为[`Rectangle`](../rectangle):Aspose.PSD.RectangleF值到最接近的整数值。 |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | 通过截断T将指定的[`RectangleF`](../rectanglef) 转换为[`Rectangle`](../rectangle):Aspose.PSD.RectangleF值。 |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | 获取一个[`Rectangle`](../rectangle)结构，其中包含两个[`Rectangle`](../rectangle)结构的并集。 |
| [Contains](../../aspose.psd/rectangle/contains#contains)(Point) | 确定指定点是否包含在此[`Rectangle`](../rectangle)结构中。 |
| [Contains](../../aspose.psd/rectangle/contains#contains_1)(Rectangle) | 确定由*rect*表示的矩形区域是否完全包含在此[`Rectangle`](../rectangle)结构中。 |
| [Contains](../../aspose.psd/rectangle/contains#contains_2)(int, int) | 确定指定点是否包含在此[`Rectangle`](../rectangle)结构中。 |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | 测试*obj*是否是一个[`Rectangle`](../rectangle)结构，其位置和大小与T相同：Aspose.PSD.Rectangle结构。 |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | 返回此[`Rectangle`](../rectangle)结构的哈希码。 |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate)(Size) | 将此[`Rectangle`](../rectangle)膨胀指定的量。 |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate_1)(int, int) | 将此[`Rectangle`](../rectangle)膨胀指定的量。 |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | 将此[`Rectangle`](../rectangle)替换为自身与指定[`Rectangle`](../rectangle)的交集。 |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | 确定此矩形是否与*rect*相交。 |
| [Normalize](../../aspose.psd/rectangle/normalize)() | 标准化矩形，使其宽度和高度为正，左小于右，上小于下。 |
| [Offset](../../aspose.psd/rectangle/offset#offset)(Point) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.psd/rectangle/offset#offset_1)(int, int) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.psd/rectangle/tostring)() | 将此[`Rectangle`](../rectangle)的属性转换为人类可读的字符串。 |
| [operator ==](../../aspose.psd/rectangle/op_equality) | 测试两个[`Rectangle`](../rectangle)结构是否具有相同的位置和大小。 |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | 测试两个[`Rectangle`](../rectangle)结构的位置或大小是否不同。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
