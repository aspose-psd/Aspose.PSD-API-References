---
title: Struct SizeF
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.SizeF 结构. 存储一对有序的浮点数通常是矩形的宽度和高度
type: docs
weight: 5560
url: /zh/net/aspose.psd/sizef/
---
## SizeF structure

存储一对有序的浮点数，通常是矩形的宽度和高度。

```csharp
public struct SizeF
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | 初始化一个新的实例`SizeF`从指定的结构[`PointF`](../pointf/) . |
| [SizeF](sizef/#constructor_1)(SizeF) | 初始化一个新的实例`SizeF`从指定的结构`SizeF` . |
| [SizeF](sizef/#constructor_2)(float, float) | 初始化一个新的实例`SizeF`指定尺寸的结构. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | 获取一个新的实例`SizeF`具有的结构[`Width`](./width/)和[`Height`](./height/)值设置为零. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | 获取或设置此的垂直分量`SizeF` . |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | 获取一个值，指示是否这`SizeF`宽度和高度为零. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | 获取或设置这个的水平分量`SizeF` . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | 加一个宽高`SizeF`结构到另一个的宽度和高度`SizeF`结构. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | 宽高减一`SizeF`另一个结构的宽度和高度`SizeF`结构. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | 测试指定对象是否是`SizeF`与此尺寸相同`SizeF` . |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | 返回一个散列码[`Size`](../size/)结构. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | 转换一个`SizeF`到一个[`PointF`](../pointf/) . |
| [ToSize](../../aspose.psd/sizef/tosize/)() | 转换一个`SizeF`到一个[`Size`](../size/)具有截断大小值的结构. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | 创建一个人类可读的字符串来表示这个`SizeF` . |
| [operator +](../../aspose.psd/sizef/op_addition/) | 加一个宽高`SizeF`结构到另一个的宽度和高度`SizeF`结构. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | 测试是否两个`SizeF`结构相等. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | 转换指定的`SizeF`到一个[`PointF`](../pointf/) . |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | 测试是否两个`SizeF`结构不同. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | 宽高减一`SizeF`另一个结构的宽度和高度`SizeF`结构. |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


