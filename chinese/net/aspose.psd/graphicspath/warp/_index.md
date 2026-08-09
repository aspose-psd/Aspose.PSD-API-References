---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD for .NET API 参考"
description: "GraphicsPath 方法。将由矩形和平行四边形定义的扭曲变换应用于此 GraphicsPath。"
type: docs
weight: 180
url: /zh/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个由 [`PointF`](../../pointf/) 结构组成的数组，这些结构定义了一个平行四边形，矩形（由 *srcRect* 定义）将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| srcRect | RectangleF | 一个 [`RectangleF`](../../rectanglef/) ，表示被转换为由 *destPoints* 定义的平行四边形的矩形。 |

### 另请参阅

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个由 [`PointF`](../../pointf/) 结构组成的数组，这些结构定义了一个平行四边形，矩形（由 *srcRect* 定义）将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| srcRect | RectangleF | 一个 [`RectangleF`](../../rectanglef/) ，表示被转换为由 *destPoints* 定义的平行四边形的矩形。 |
| matrix | Matrix | 一个 [`Matrix`](../../matrix/)，指定要应用于路径的几何变换。 |

### 另请参阅

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个由 [`PointF`](../../pointf/) 结构组成的数组，这些结构定义了一个平行四边形，矩形（由 *srcRect* 定义）将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| srcRect | RectangleF | 一个 [`RectangleF`](../../rectanglef/) ，表示被转换为由 *destPoints* 定义的平行四边形的矩形。 |
| matrix | Matrix | 一个 [`Matrix`](../../matrix/)，指定要应用于路径的几何变换。 |
| warpMode | WarpMode | 一个 [`WarpMode`](../../warpmode/) 枚举，指定此扭曲操作是使用透视模式还是双线性模式。 |

### 另请参阅

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

将由矩形和平行四边形定义的扭曲变换应用于此 [`GraphicsPath`](../)。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destPoints | PointF[] | 一个由 [`PointF`](../../pointf/) 结构组成的数组，这些结构定义了一个平行四边形，矩形（由 *srcRect* 定义）将被转换到该平行四边形。数组可以包含三或四个元素。如果数组包含三个元素，则平行四边形的右下角由前三个点暗示。 |
| srcRect | RectangleF | 一个 [`RectangleF`](../../rectanglef/) ，表示被转换为由 *destPoints* 定义的平行四边形的矩形。 |
| matrix | Matrix | 一个 [`Matrix`](../../matrix/)，指定要应用于路径的几何变换。 |
| warpMode | WarpMode | 一个 [`WarpMode`](../../warpmode/) 枚举，指定此扭曲操作是使用透视模式还是双线性模式。 |
| flatness | Single | 一个介于 0 到 1 之间的值，指定结果路径的平坦程度。有关更多信息，请参阅 [`Flatten`](../flatten/) 方法。 |

### 另请参阅

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


