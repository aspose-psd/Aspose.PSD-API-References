---
title: "Blend 类"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Blend 类。定义混合模式。此类不可被继承"
type: docs
weight: 110
url: /zh/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

定义混合模式。此类不可继承。

```csharp
public sealed class Blend
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Blend](blend/#constructor)() | 初始化 `Blend` 类的新实例。factor 和 blend 数组中的元素数量将等于 1。 |
| [Blend](blend/#constructor_1)(int) | 使用指定的因子和位置数量初始化 `Blend` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | 获取或设置渐变的混合因子数组。 |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | 获取或设置渐变的混合位置数组。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | 测试指定的对象是否为 `Blend` 类且等同于此 `Blend` 类。 |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | 返回此实例的哈希码。 |

## 备注

典型的 Blend 类用法是为画笔定义混合模式。因此应仔细初始化混合属性。不允许空数组。如果 blend 因子或位置数组为空或长度不一致，画笔将抛出相应的异常。如果位置数组中有两个或更多元素，则第一个元素应为 0，最后一个元素应为 1。

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


