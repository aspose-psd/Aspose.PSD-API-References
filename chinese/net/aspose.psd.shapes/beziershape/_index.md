---
title: "类 BezierShape"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Shapes.BezierShape 类。表示贝塞尔样条"
type: docs
weight: 5970
url: /zh/net/aspose.psd.shapes/beziershape/
---
{{< psd/tize >}}
## BezierShape class

表示贝塞尔样条。

```csharp
public sealed class BezierShape : PolygonShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BezierShape](beziershape/#constructor)() | 初始化 `BezierShape` 类的新实例。 |
| [BezierShape](beziershape/#constructor_1)(PointF[]) | 初始化 `BezierShape` 类的新实例。 |
| [BezierShape](beziershape/#constructor_2)(PointF[], bool) | 初始化 `BezierShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/beziershape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/beziershape/center/) { get; } | 获取形状的中心。 |
| override [EndPoint](../../aspose.psd.shapes/beziershape/endpoint/) { get; } | 获取形状的结束点。 |
| override [HasSegments](../../aspose.psd.shapes/beziershape/hassegments/) { get; } | 获取指示形状是否具有段的值。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置指示形状是否闭合的值。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.psd.shapes/beziershape/segments/) { get; } | 获取形状段。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 获取形状的起始点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/beziershape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 另请参阅

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


