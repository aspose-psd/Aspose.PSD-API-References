---
title: Struct Point
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Point 结构. 表示定义二维平面中的点的有序整数 x 和 y 坐标对
type: docs
weight: 5260
url: /zh/net/aspose.psd/point/
---
## Point structure

表示定义二维平面中的点的有序整数 x 和 y 坐标对。

```csharp
public struct Point
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Point](point/#constructor_1)(int) | 初始化一个新的实例`Point`使用由整数值指定的坐标的结构. |
| [Point](point/#constructor)(Size) | 初始化一个新的实例`Point`结构从[`Size`](../size/)结构. |
| [Point](point/#constructor_2)(int, int) | 初始化一个新的实例`Point`具有指定坐标的结构. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | 获取一个新的实例`Point`具有的结构[`X`](./x/)和[`Y`](./y/)值设置为零. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | 获取一个值，指示是否这`Point`是空的. |
| [X](../../aspose.psd/point/x/) { get; set; } | 获取或设置此的 x 坐标`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | 获取或设置 this 的 y 坐标`Point` . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | 添加指定的[`Size`](../size/)到指定的`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | 转换指定的[`PointF`](../pointf/)到一个`Point`通过四舍五入的值[`PointF`](../pointf/)到下一个更高的整数值。 |
| static [Round](../../aspose.psd/point/round/)(PointF) | 转换指定的[`PointF`](../pointf/)到一个`Point`通过四舍五入对象`Point`值到最接近的整数. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | 返回指定的相减结果[`Size`](../size/)从指定的`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | 转换指定的[`PointF`](../pointf/)到一个`Point`通过截断的值`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | 指定是否这`Point`包含与指定相同的坐标Object . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | 返回一个散列码`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | 翻译这个`Point`由指定的`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | 翻译这个`Point`按指定数量. |
| override [ToString](../../aspose.psd/point/tostring/)() | 转换这个`Point`到人类可读的字符串. |
| [operator +](../../aspose.psd/point/op_addition/) | 翻译一个`Point`通过给定的[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | 比较两个`Point`对象。结果指定的值是否[`X`](./x/)和[`Y`](./y/)两者的属性`Point`对象是平等的。 |
| [explicit operator](../../aspose.psd/point/op_explicit/) | 转换指定的`Point`结构为[`Size`](../size/)结构. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | 转换指定的`Point`结构到[`PointF`](../pointf/)结构. |
| [operator !=](../../aspose.psd/point/op_inequality/) | 比较两个`Point`对象。结果指定的值是否[`X`](./x/)或者[`Y`](./y/)两者的属性`Point`对象不相等. |
| [operator -](../../aspose.psd/point/op_subtraction/) | 翻译一个`Point`由给定的负[`Size`](../size/) . |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


