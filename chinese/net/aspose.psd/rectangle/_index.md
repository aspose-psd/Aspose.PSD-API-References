---
title: Rectangle
second_title: Aspose.PSD for .NET API 参考
description: 存储一组四个整数表示矩形的位置和大小
type: docs
weight: 5270
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
| [Rectangle](rectangle#constructor)(Point, Size) | 初始化[`Rectangle`](../rectangle)具有指定位置和大小的结构。 |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | 初始化[`Rectangle`](../rectangle)具有指定位置和大小的结构。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty) { get; } | 获取一个新的实例[`Rectangle`](../rectangle)具有的结构[`X`](./x) ,[`Y`](./y) ,[`Width`](./width)和[`Height`](./height)值设置为零。 |
| [Bottom](../../aspose.psd/rectangle/bottom) { get; set; } | 获取或设置 y 坐标，它是[`Y`](./y)和[`Height`](./height)this 的属性值[`Rectangle`](../rectangle)结构. |
| [Height](../../aspose.psd/rectangle/height) { get; set; } | 获取或设置 this 的高度[`Rectangle`](../rectangle)结构. |
| [IsEmpty](../../aspose.psd/rectangle/isempty) { get; } | 获取一个值，该值指示此的所有数字属性是否[`Rectangle`](../rectangle)值为零。 |
| [Left](../../aspose.psd/rectangle/left) { get; set; } | 获取或设置 this 的左边缘的 x 坐标[`Rectangle`](../rectangle)结构. |
| [Location](../../aspose.psd/rectangle/location) { get; set; } | 获取或设置this的左上角坐标[`Rectangle`](../rectangle)结构. |
| [Right](../../aspose.psd/rectangle/right) { get; set; } | 获取或设置 x 坐标，它是[`X`](./x)和[`Width`](./width)this 的属性值[`Rectangle`](../rectangle)结构. |
| [Size](../../aspose.psd/rectangle/size) { get; set; } | 获取或设置 this 的大小[`Rectangle`](../rectangle) . |
| [Top](../../aspose.psd/rectangle/top) { get; set; } | 获取或设置此顶部边缘的 y 坐标[`Rectangle`](../rectangle)结构. |
| [Width](../../aspose.psd/rectangle/width) { get; set; } | 获取或设置 this 的宽度[`Rectangle`](../rectangle)结构. |
| [X](../../aspose.psd/rectangle/x) { get; set; } | 获取或设置此对象左上角的x坐标[`Rectangle`](../rectangle)结构. |
| [Y](../../aspose.psd/rectangle/y) { get; set; } | 获取或设置这个左上角的y坐标[`Rectangle`](../rectangle)结构. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling)(RectangleF) | 转换指定的[`RectangleF`](../rectanglef)结构为[`Rectangle`](../rectangle)通过四舍五入的结构[`RectangleF`](../rectanglef)值到下一个更高的整数值。 |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom)(int, int, int, int) | 创建一个[`Rectangle`](../rectangle)具有指定边缘位置的结构。 |
| static [FromPoints](../../aspose.psd/rectangle/frompoints)(Point, Point) | 创建一个新的[`Rectangle`](../rectangle)从指定的两点。创建的两个垂直[`Rectangle`](../rectangle)将等于通过*point1*和*point2*.这些通常是相反的顶点。 |
| static [Inflate](../../aspose.psd/rectangle/inflate)(Rectangle, int, int) | 创建并返回指定的膨胀副本[`Rectangle`](../rectangle)结构体。副本按指定的数量膨胀。原本的[`Rectangle`](../rectangle)结构保持不变。 |
| static [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle, Rectangle) | 返回第三个[`Rectangle`](../rectangle)表示两个其他交集的结构[`Rectangle`](../rectangle)结构。如果没有交叉点，则为空[`Rectangle`](../rectangle)被退回。 |
| static [Round](../../aspose.psd/rectangle/round)(RectangleF) | 转换指定的[`RectangleF`](../rectanglef)到一个[`Rectangle`](../rectangle)通过四舍五入[`RectangleF`](../rectanglef)值到最接近的整数值。 |
| static [Truncate](../../aspose.psd/rectangle/truncate)(RectangleF) | 转换指定的[`RectangleF`](../rectanglef)到一个[`Rectangle`](../rectangle)通过截断[`RectangleF`](../rectanglef)值. |
| static [Union](../../aspose.psd/rectangle/union)(Rectangle, Rectangle) | 得到一个[`Rectangle`](../rectangle)包含两个并集的结构[`Rectangle`](../rectangle)结构. |
| [Contains](../../aspose.psd/rectangle/contains#contains)(Point) | 确定指定点是否包含在此范围内[`Rectangle`](../rectangle)结构. |
| [Contains](../../aspose.psd/rectangle/contains#contains_1)(Rectangle) | 确定矩形区域是否由*rect*完全包含在这个[`Rectangle`](../rectangle)结构. |
| [Contains](../../aspose.psd/rectangle/contains#contains_2)(int, int) | 确定指定点是否包含在此范围内[`Rectangle`](../rectangle)结构. |
| override [Equals](../../aspose.psd/rectangle/equals)(object) | 测试是否*obj*是一个[`Rectangle`](../rectangle)具有相同位置和大小的结构[`Rectangle`](../rectangle)结构. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode)() | 返回此哈希码[`Rectangle`](../rectangle)结构. |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate)(Size) | 膨胀这个[`Rectangle`](../rectangle)按指定数量。 |
| [Inflate](../../aspose.psd/rectangle/inflate#inflate_1)(int, int) | 膨胀这个[`Rectangle`](../rectangle)按指定数量。 |
| [Intersect](../../aspose.psd/rectangle/intersect)(Rectangle) | 替换这个[`Rectangle`](../rectangle)与自身和指定的交集[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith)(Rectangle) | 确定此矩形是否与*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize)() | 通过使矩形的宽度和高度为正值、left 小于 right 和 top 小于 bottom 来规范化矩形。 |
| [Offset](../../aspose.psd/rectangle/offset#offset)(Point) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.psd/rectangle/offset#offset_1)(int, int) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.psd/rectangle/tostring)() | 转换 this 的属性[`Rectangle`](../rectangle)到一个人类可读的字符串。 |
| [operator ==](../../aspose.psd/rectangle/op_equality) | 测试是否两个[`Rectangle`](../rectangle)结构具有相同的位置和大小。 |
| [operator !=](../../aspose.psd/rectangle/op_inequality) | 测试是否两个[`Rectangle`](../rectangle)结构的位置或大小不同。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
