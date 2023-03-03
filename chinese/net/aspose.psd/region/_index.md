---
title: Class Region
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Region 班级. 描述由矩形和路径组成的图形形状的内部此类不能被继承
type: docs
weight: 5360
url: /zh/net/aspose.psd/region/
---
## Region class

描述由矩形和路径组成的图形形状的内部。此类不能被继承。

```csharp
public sealed class Region
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Region](region/#constructor)() | 初始化一个新的`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | 初始化一个新的`Region`与指定的[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | 初始化一个新的`Region`从指定的[`Rectangle`](../rectangle/)结构. |
| [Region](region/#constructor_3)(RectangleF) | 初始化一个新的`Region`从指定的[`RectangleF`](../rectanglef/)结构. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | 更新这个`Region`包含指定的部分[`GraphicsPath`](../graphicspath/)与此不相交`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | 更新这个`Region`包含指定的部分[`Rectangle`](../rectangle/)与此不相交的结构`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | 更新这个`Region`包含指定的部分[`RectangleF`](../rectanglef/)与此不相交的结构`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | 更新这个`Region`包含指定的部分`Region`与此不相交`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | 创建一个精确的深拷贝`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | 测试是否指定`Region`与此相同`Region`在指定的绘图表面上. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | 更新这个`Region`仅包含其内部不与指定的相交的部分[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | 更新这个`Region`仅包含其内部不与指定的相交的部分[`Rectangle`](../rectangle/)结构. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | 更新这个`Region`仅包含其内部不与指定的相交的部分[`RectangleF`](../rectanglef/)结构. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | 更新这个`Region`仅包含其内部不与指定的相交的部分`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | 更新这个`Region`到自身与指定的交集[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | 更新这个`Region`到自身与指定的交集[`Rectangle`](../rectangle/)结构. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | 更新这个`Region`到自身与指定的交集[`RectangleF`](../rectanglef/)结构. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | 更新这个`Region`到自身与指定的交集`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | 测试这是否`Region`在指定的绘图表面上有一个空的内部。 |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | 测试这是否`Region`在指定的绘图表面上有一个无限的内部。 |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | 测试是否指定[`Point`](../point/)结构包含在这个`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | 测试是否指定[`PointF`](../pointf/)结构包含在这个`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | 测试指定的任何部分是否[`Rectangle`](../rectangle/)结构包含在这个`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | 测试指定的任何部分是否[`RectangleF`](../rectanglef/)结构包含在这个`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | 测试指定点是否包含在此`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | 测试是否指定[`Point`](../point/)结构包含在这个`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | 测试是否指定[`PointF`](../pointf/)结构包含在这个`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | 测试指定的任何部分是否[`Rectangle`](../rectangle/)结构包含在这个`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | 测试指定的任何部分是否[`RectangleF`](../rectanglef/)结构包含在这个`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | 测试指定点是否包含在此`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | 测试指定点是否包含在此`Region`使用指定的对象绘制时[`Graphics`](../graphics/)对象. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | 测试指定矩形的任何部分是否包含在此`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | 测试指定矩形的任何部分是否包含在此`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | 测试指定矩形的任何部分是否包含在此`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | 测试指定矩形的任何部分是否包含在此`Region`使用指定的绘制时[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | 初始化这个`Region`到一个空荡荡的内部。 |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | 初始化这个`Region`反对无限的内部. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | 转换这个`Region`由指定的[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | 偏移这个的坐标`Region`按指定数量. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | 偏移这个的坐标`Region`按指定数量. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | 更新这个`Region`自身与指定的联合[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | 更新这个`Region`自身与指定的联合[`Rectangle`](../rectangle/)结构. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | 更新这个`Region`自身与指定的联合[`RectangleF`](../rectanglef/)结构. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | 更新这个`Region`自身与指定的联合`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | 更新这个`Region`联合减去自身与指定的交集[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | 更新这个`Region`联合减去自身与指定的交集[`Rectangle`](../rectangle/)结构. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | 更新这个`Region`联合减去自身与指定的交集[`RectangleF`](../rectanglef/)结构. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | 更新这个`Region`联合减去自身与指定的交集`Region` . |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


