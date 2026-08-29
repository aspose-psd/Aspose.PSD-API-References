---
title: "类 CustomLineCap"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.CustomLineCap 类。封装自定义用户定义的线帽"
type: docs
weight: 710
url: /zh/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

封装自定义用户定义的线帽。

```csharp
public class CustomLineCap
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | 使用指定的轮廓和填充初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | 使用指定的轮廓和填充，从指定的现有 [`LineCap`](../linecap/) 枚举初始化 `CustomLineCap` 类的新实例。 |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | 初始化一个新的 `CustomLineCap` 类实例，使用指定的现有 [`LineCap`](../linecap/) 枚举，并指定轮廓、填充和内嵌。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | 获取或设置此 `CustomLineCap` 所基于的 [`LineCap`](../linecap/) 枚举。 |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | 获取或设置帽子与线之间的距离。 |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | 获取或设置定义自定义帽填充的对象。 |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | 获取或设置决定组成此 `CustomLineCap` 对象的线段如何连接的 [`LineJoin`](../linejoin/) 枚举。 |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | 获取或设置定义自定义帽轮廓的对象。 |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | 获取或设置相对于 Pen 对象宽度，对此 `CustomLineCap` 类对象进行缩放的量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | 获取用于开始和结束构成此自定义帽的线段的帽子。 |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | 设置用于开始和结束构成此自定义帽的线段的帽子。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


