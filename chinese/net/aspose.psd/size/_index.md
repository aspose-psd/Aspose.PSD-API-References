---
title: Struct Size
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Size 结构. 代表尺寸
type: docs
weight: 5550
url: /zh/net/aspose.psd/size/
---
## Size structure

代表尺寸。

```csharp
public struct Size
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Size](size/#constructor)(Point) | 初始化一个新的实例`Size`从指定的结构[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | 初始化一个新的实例`Size`指定尺寸的结构. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | 获取一个新的实例`Size`具有的结构[`Width`](./width/)和[`Height`](./height/)值设置为零. |
| [Height](../../aspose.psd/size/height/) { get; set; } | 获取或设置此的垂直分量`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | 获取一个值，指示是否这`Size`宽度和高度为 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | 获取或设置这个的水平分量`Size` . |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | 加一个宽高`Size`结构到另一个的宽度和高度`Size`结构. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | 转换指定的[`SizeF`](../sizef/)结构为`Size`通过四舍五入的值结构`Size`结构到下一个更高的整数值. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | 转换指定的[`SizeF`](../sizef/)结构为`Size`通过四舍五入的值结构[`SizeF`](../sizef/)结构到最接近的整数值. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | 宽高减一`Size`另一个结构的宽度和高度`Size`结构. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | 转换指定的[`SizeF`](../sizef/)结构为`Size`通过截断的值结构[`SizeF`](../sizef/)结构到下一个较低的整数值. |
| override [Equals](../../aspose.psd/size/equals/)(object) | 测试指定对象是否是`Size`与此尺寸相同`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | 返回一个散列码`Size`结构. |
| override [ToString](../../aspose.psd/size/tostring/)() | 创建一个人类可读的字符串来表示这个`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | 加一个宽高`Size`结构到另一个的宽度和高度`Size`结构. |
| [operator ==](../../aspose.psd/size/op_equality/) | 测试是否两个`Size`结构相等. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | 转换指定的`Size`到一个[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | 转换指定的`Size`到一个[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | 测试是否两个`Size`结构不同. |
| [operator -](../../aspose.psd/size/op_subtraction/) | 宽高减一`Size`另一个结构的宽度和高度`Size`结构. |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


