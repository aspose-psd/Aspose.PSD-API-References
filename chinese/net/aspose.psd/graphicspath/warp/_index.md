---
title: GraphicsPath.Warp
second_title: Aspose.PSD for .NET API 参考
description: GraphicsPath 方法. 将由矩形和平行四边形定义的扭曲变换应用于此GraphicsPath .
type: docs
weight: 180
url: /zh/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 的数组[`PointF`](../../pointf/)定义平行四边形的结构，由*srcRect*被转化。该数组可以包含三个或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点表示。 |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/)表示转换为由定义的平行四边形的矩形*destPoints*. |

### 也可以看看

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* 命名空间 [Aspose.PSD](../../graphicspath/)
* 部件 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 的数组[`PointF`](../../pointf/)定义平行四边形的结构，由*srcRect*被转化。该数组可以包含三个或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点表示。 |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/)表示转换为由定义的平行四边形的矩形*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/)指定要应用于路径的几何变换。 |

### 也可以看看

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 命名空间 [Aspose.PSD](../../graphicspath/)
* 部件 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 的数组[`PointF`](../../pointf/)定义平行四边形的结构，由*srcRect*被转化。该数组可以包含三个或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点表示。 |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/)表示转换为由定义的平行四边形的矩形*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/)指定要应用于路径的几何变换。 |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/)指定此扭曲操作是使用透视模式还是双线性模式的枚举。 |

### 也可以看看

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* 命名空间 [Aspose.PSD](../../graphicspath/)
* 部件 [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 的数组[`PointF`](../../pointf/)定义平行四边形的结构，由*srcRect*被转化。该数组可以包含三个或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点表示。 |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/)表示转换为由定义的平行四边形的矩形*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/)指定要应用于路径的几何变换。 |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/)指定此扭曲操作是使用透视模式还是双线性模式的枚举。 |
| flatness | Single | 一个从 0 到 1 的值，指定结果路径的平坦程度。有关详细信息，请参阅[`Flatten`](../flatten/)方法。 |

### 也可以看看

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* 命名空间 [Aspose.PSD](../../graphicspath/)
* 部件 [Aspose.PSD](../../../)


