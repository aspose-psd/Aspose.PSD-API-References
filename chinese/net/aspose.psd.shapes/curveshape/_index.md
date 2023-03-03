---
title: Class CurveShape
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.Shapes.CurveShape 班级. 表示曲线样条形状
type: docs
weight: 5480
url: /zh/net/aspose.psd.shapes/curveshape/
---
## CurveShape class

表示曲线样条形状。

```csharp
public sealed class CurveShape : PolygonShape
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [CurveShape](curveshape/#constructor)() | 初始化一个新的实例`CurveShape`类. |
| [CurveShape](curveshape/#constructor_1)(PointF[]) | 初始化一个新的实例`CurveShape`班级。使用默认张力 0.5. |
| [CurveShape](curveshape/#constructor_2)(PointF[], bool) | 初始化一个新的实例`CurveShape`班级。使用默认张力 0.5. |
| [CurveShape](curveshape/#constructor_3)(PointF[], float) | 初始化一个新的实例`CurveShape`类. |
| [CurveShape](curveshape/#constructor_4)(PointF[], float, bool) | 初始化一个新的实例`CurveShape`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/curveshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/curveshape/center/) { get; } | 获取形状的中心。 |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | 获取结束形状点。 |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | 获取一个值，表示形状是否有段。 |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置一个表示形状是否闭合的值。 |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.psd.shapes/curveshape/segments/) { get; } | 获取形状段。 |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | 获取起始形状点。 |
| [Tension](../../aspose.psd.shapes/curveshape/tension/) { get; set; } | 获取或设置曲线张力。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/curveshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 也可以看看

* class [PolygonShape](../polygonshape/)
* 命名空间 [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* 部件 [Aspose.PSD](../../)


