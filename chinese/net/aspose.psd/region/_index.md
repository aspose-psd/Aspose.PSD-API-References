---
title: Region
second_title: Aspose.PSD for .NET API 参考
description: 描述由矩形和路径组成的图形形状的内部这个类不能被继承
type: docs
weight: 5240
url: /zh/net/aspose.psd/region/
---
## Region class

描述由矩形和路径组成的图形形状的内部。这个类不能被继承。

```csharp
public sealed class Region
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Region](region#constructor)() | 初始化一个新的[`Region`](../region)。 |
| [Region](region#constructor_1)(GraphicsPath) | 使用指定的[`GraphicsPath`](../graphicspath)初始化一个新的[`Region`](../region)。 |
| [Region](region#constructor_2)(Rectangle) | 从指定的[`Rectangle`](../rectangle)结构初始化一个新的[`Region`](../region)。 |
| [Region](region#constructor_3)(RectangleF) | 从指定的[`RectangleF`](../rectanglef)结构初始化一个新的[`Region`](../region)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement#complement)(GraphicsPath) | 更新此[`Region`](../region)以包含不相交的指定[`GraphicsPath`](../graphicspath)部分用这个[`Region`](../region)。 |
| [Complement](../../aspose.psd/region/complement#complement_1)(Rectangle) | 更新此[`Region`](../region)以包含指定的[`Rectangle`](../rectangle)结构中不包含的部分与此[`Region`](../region)相交。 |
| [Complement](../../aspose.psd/region/complement#complement_2)(RectangleF) | 更新此[`Region`](../region)以包含指定的[`RectangleF`](../rectanglef)结构中不包含的部分与此[`Region`](../region)相交。 |
| [Complement](../../aspose.psd/region/complement#complement_3)(Region) | 更新此[`Region`](../region)以包含不相交的指定[`Region`](../region)部分用这个[`Region`](../region)。 |
| [DeepClone](../../aspose.psd/region/deepclone)() | 创建此[`Region`](../region)的精确深层副本。 |
| [Equals](../../aspose.psd/region/equals#equals)(Region, Graphics) | 测试指定的[`Region`](../region)是否与指定绘图表面上的此[`Region`](../region)相同. |
| [Exclude](../../aspose.psd/region/exclude#exclude)(GraphicsPath) | 更新此[`Region`](../region)以仅包含其内部不与指定的GraphicsPath。 |
| [Exclude](../../aspose.psd/region/exclude#exclude_1)(Rectangle) | 更新此[`Region`](../region)以仅包含其内部不与指定的Rectangle结构。 |
| [Exclude](../../aspose.psd/region/exclude#exclude_2)(RectangleF) | 更新此[`Region`](../region)以仅包含其内部不与指定的RectangleF结构。 |
| [Exclude](../../aspose.psd/region/exclude#exclude_3)(Region) | 更新此[`Region`](../region)以仅包含其内部不与指定的PSD相交的部分。地区。 |
| [Intersect](../../aspose.psd/region/intersect#intersect)(GraphicsPath) | 将此[`Region`](../region)更新为自身与指定[`GraphicsPath`](../graphicspath)的交集。 |
| [Intersect](../../aspose.psd/region/intersect#intersect_1)(Rectangle) | 将此[`Region`](../region)更新为自身与指定[`Rectangle`](../rectangle)结构的交集。 |
| [Intersect](../../aspose.psd/region/intersect#intersect_2)(RectangleF) | 将此[`Region`](../region)更新为自身与指定[`RectangleF`](../rectanglef)结构的交集。 |
| [Intersect](../../aspose.psd/region/intersect#intersect_3)(Region) | 将此[`Region`](../region)更新为自身与指定[`Region`](../region)的交集。 |
| [IsEmpty](../../aspose.psd/region/isempty)(Graphics) | 测试此[`Region`](../region)在指定绘图表面上是否有一个空的内部。 |
| [IsInfinite](../../aspose.psd/region/isinfinite)(Graphics) | 测试此[`Region`](../region)在指定绘图表面上是否具有无限内部。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible)(Point) | 测试指定的[`Point`](../point)结构是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_2)(PointF) | 测试指定的[`PointF`](../pointf)结构是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_4)(Rectangle) | 测试指定[`Rectangle`](../rectangle)结构的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_6)(RectangleF) | 测试指定[`RectangleF`](../rectanglef)结构的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_11)(float, float) | 测试指定点是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_1)(Point, Graphics) | 测试指定的[`Point`](../point)结构是否包含在使用指定[`Graphics`](../graphics)。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_3)(PointF, Graphics) | 测试指定的[`PointF`](../pointf)结构是否包含在使用指定[`Graphics`](../graphics)。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_5)(Rectangle, Graphics) | 测试指定[`Rectangle`](../rectangle)结构的任何部分是否包含在此[`Region`](../region)中使用指定的[`Graphics`](../graphics)绘制。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_7)(RectangleF, Graphics) | 测试指定[`RectangleF`](../rectanglef)结构的任何部分是否包含在此[`Region`](../region)中使用指定的[`Graphics`](../graphics)绘制。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_12)(float, float, Graphics) | 使用指定的Graphics@绘制时，测试指定点是否包含在此[`Region`](../region)中@. |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_8)(int, int, Graphics) | 在使用指定的Graphics绘制时，测试指定的点是否包含在此[`Region`](../region) 对象中目的。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_13)(float, float, float, float) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_9)(int, int, int, int) | 测试指定矩形的任何部分是否包含在此[`Region`](../region)中。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | 在使用指定的PSD绘制时，测试指定矩形的任何部分是否包含在此[`Region`](../region) 中.图形。 |
| [IsVisible](../../aspose.psd/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | 在使用指定的PSD绘制时，测试指定矩形的任何部分是否包含在此[`Region`](../region) 中.图形。 |
| [MakeEmpty](../../aspose.psd/region/makeempty)() | 将此[`Region`](../region)初始化为一个空的内部。 |
| [MakeInfinite](../../aspose.psd/region/makeinfinite)() | 将此[`Region`](../region)对象初始化为无限内部。 |
| [Transform](../../aspose.psd/region/transform)(Matrix) | 将此[`Region`](../region)转换为指定的[`Matrix`](../matrix)。 |
| [Translate](../../aspose.psd/region/translate#translate_1)(float, float) | 将此[`Region`](../region)的坐标偏移指定的量。 |
| [Translate](../../aspose.psd/region/translate#translate)(int, int) | 将此[`Region`](../region)的坐标偏移指定的量。 |
| [Union](../../aspose.psd/region/union#union)(GraphicsPath) | 将此[`Region`](../region)更新为自身和指定的[`GraphicsPath`](../graphicspath)的并集。 |
| [Union](../../aspose.psd/region/union#union_1)(Rectangle) | 将此[`Region`](../region)更新为自身与指定[`Rectangle`](../rectangle)结构的并集。 |
| [Union](../../aspose.psd/region/union#union_2)(RectangleF) | 将此[`Region`](../region)更新为自身与指定[`RectangleF`](../rectanglef)结构的并集。 |
| [Union](../../aspose.psd/region/union#union_3)(Region) | 将此[`Region`](../region)更新为自身与指定[`Region`](../region)的并集。 |
| [Xor](../../aspose.psd/region/xor#xor)(GraphicsPath) | 将此[`Region`](../region)更新为并集减去其自身与指定[`GraphicsPath`](../graphicspath)的交集. |
| [Xor](../../aspose.psd/region/xor#xor_1)(Rectangle) | 将此[`Region`](../region)更新为并集减去其自身与指定[`Rectangle`](../rectangle)的交集结构体。 |
| [Xor](../../aspose.psd/region/xor#xor_2)(RectangleF) | 将此[`Region`](../region)更新为并集减去其自身与指定[`RectangleF`](../rectanglef)的交集结构体。 |
| [Xor](../../aspose.psd/region/xor#xor_3)(Region) | 将此[`Region`](../region)更新为并集减去其自身与指定[`Region`](../region)的交集. |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
