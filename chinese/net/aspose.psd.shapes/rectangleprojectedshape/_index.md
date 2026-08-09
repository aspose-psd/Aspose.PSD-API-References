---
title: "类 RectangleProjectedShape"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.Shapes.RectangleProjectedShape 类。表示一种投射到矩形上并转向特定方向的形状。该形状由四个点指定，这些点可以在空间中旋转，保持相同的边长且相邻边之间保持 90 度。"
type: docs
weight: 6020
url: /zh/net/aspose.psd.shapes/rectangleprojectedshape/
---
{{< psd/tize >}}
## RectangleProjectedShape class

表示一种投射在矩形上并旋转至特定方向的形状。由四个点指定，这些点可以在空间中旋转，保持相同的边长且相邻边之间保持 90 度。

```csharp
public abstract class RectangleProjectedShape : Shape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor)() | 初始化 `RectangleProjectedShape` 类的新实例。 |
| [RectangleProjectedShape](rectangleprojectedshape/#constructor_1)(RectangleF) | 初始化 `RectangleProjectedShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | 获取形状的中心。 |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | 获取指示形状是否具有段的值。 |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | 获取左下矩形点。 |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | 获取左上矩形点。 |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 获取矩形高度。 |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 获取矩形的宽度。 |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | 获取矩形右下角点。 |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | 获取矩形右上角点。 |
| abstract [Segments](../../aspose.psd/shape/segments/) { get; } | 获取形状段。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | 将指定的变换应用于形状。 |

### 另请参阅

* class [Shape](../../aspose.psd/shape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


