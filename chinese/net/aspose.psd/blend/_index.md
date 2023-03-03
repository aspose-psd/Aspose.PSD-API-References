---
title: Class Blend
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Blend 班级. 定义混合模式此类不能被继承
type: docs
weight: 110
url: /zh/net/aspose.psd/blend/
---
## Blend class

定义混合模式。此类不能被继承。

```csharp
public sealed class Blend
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Blend](blend/#constructor)() | 初始化一个新的实例`Blend`班级。因子和混合数组中的元素数将等于 1. |
| [Blend](blend/#constructor_1)(int) | 初始化一个新的实例`Blend`具有指定数量的因子和位置的类。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | 获取或设置渐变的混合因子数组。 |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | 获取或设置渐变的混合位置数组。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | 测试指定对象是否是`Blend`类，相当于这个`Blend`类. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | 返回此实例的哈希码。 |

### 评论

典型的混合类用法是定义画笔的混合模式。因此混合属性应该仔细初始化。 Null 数组是不允许的。如果混合因子或位置数组为空或它们的长度不相同，画笔将抛出适当的异常。 如果位置数组中有两个或更多元素，则第一个元素应为 0，最后一个元素应为 1.

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


