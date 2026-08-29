---
title: "类 CurveShape"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Shapes.CurveShape 类。表示曲线样条形状"
type: docs
weight: 5980
url: /zh/net/aspose.psd.shapes/curveshape/
---
{{< psd/tize >}}
## CurveShape class

表示曲线样条形状。

```csharp
public sealed class CurveShape : PolygonShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | 初始化 `CurveShape` 类的新实例。 |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | 初始化 `CurveShape` 类的新实例。使用默认张力 0.5。 |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | 初始化 `CurveShape` 类的新实例。使用默认张力 0.5。 |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | 初始化 `CurveShape` 类的新实例。 |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | 初始化 `CurveShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | 获取形状的中心。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 获取形状的结束点。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 获取指示形状是否具有段的值。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置指示形状是否闭合的值。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | 获取形状段。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 获取形状的起始点。 |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | 获取或设置曲线张力。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 另请参阅

* class [PolygonShape](../polygonshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


