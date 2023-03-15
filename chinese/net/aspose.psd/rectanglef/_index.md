---
title: Struct RectangleF
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.RectangleF 结构. 存储一组四个浮点数表示矩形的位置和大小
type: docs
weight: 5350
url: /zh/net/aspose.psd/rectanglef/
---
## RectangleF structure

存储一组四个浮点数，表示矩形的位置和大小。

```csharp
public struct RectangleF
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | 初始化一个新的实例`RectangleF`具有指定位置和大小的结构。 |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | 初始化一个新的实例`RectangleF`具有指定位置和大小的结构。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | 获取一个新的实例`RectangleF`具有的结构[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/)和[`Height`](./height/)值设置为零. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | 获取或设置 y 坐标，即[`Y`](./y/)和[`Height`](./height/)这个的`RectangleF`结构. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | 获取或设置此高度`RectangleF`结构. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | 获取一个值，表示是否[`Width`](./width/)或者[`Height`](./height/)这个的属性`RectangleF`值为零. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | 获取或设置此元素左边缘的 x 坐标`RectangleF`结构. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | 获取或设置此画面左上角的坐标`RectangleF`结构. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | 获取或设置 x 坐标，即[`X`](./x/)和[`Width`](./width/)这个的`RectangleF`结构. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | 获取或设置这个的大小`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | 获取或设置此图上边缘的y坐标`RectangleF`结构. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | 获取或设置宽度`RectangleF`结构. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | 获取或设置此画面左上角的 x 坐标`RectangleF`结构. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | 获取或设置此画面左上角的y坐标`RectangleF`结构. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | 创建一个`RectangleF`在指定位置具有左上角和右下角的结构. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | 创建一个新的[`Rectangle`](../rectangle/)从指定的两个点。创建的两个verticle[`Rectangle`](../rectangle/)将等于通过*point1*和*point2*.这些通常是相反的顶点。 |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | 创建并返回指定的膨胀副本`RectangleF`结构。副本膨胀了指定的量。原始矩形保持不变。 |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | 返回一个`RectangleF`表示两个矩形相交的结构。如果没有交集，且为空`RectangleF`返回. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | 创建最小的第三个矩形，该矩形可以包含两个构成并集的矩形。 |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | 确定指定点是否包含在此`RectangleF`结构. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | 判断所代表的矩形区域是否*rect*完全包含在这个`RectangleF`结构. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | 确定指定点是否包含在此`RectangleF`结构. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | 测试是否*obj*是一个`RectangleF`具有相同的位置和大小`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | 获取这个的哈希码`RectangleF`结构. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | 膨胀这个`RectangleF`按指定数量. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | 膨胀这个`RectangleF`指定数量的结构. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | 替换这个`RectangleF`自身与指定交集的结构`RectangleF`结构. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | 判断这个矩形是否与*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | 通过使矩形的宽度和高度为正、左侧小于右侧、顶部小于底部来规范化矩形。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | 按指定量调整此矩形的位置。 |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | 按指定量调整此矩形的位置。 |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | 转换这个的属性`RectangleF`到人类可读的字符串. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | 实现运算符 /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | 测试是否两个`RectangleF`结构具有相同的位置和大小。 |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | 转换指定的[`Rectangle`](../rectangle/)结构为`RectangleF`结构. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | 测试是否两个`RectangleF`结构的位置或大小不同。 |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | 实现运算符 *. |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


