---
title: "GraphicsPath.Warp"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método GraphicsPath. Aplica una transformación de deformación definida por un rectángulo y un paralelogramo a este GraphicsPath"
type: docs
weight: 180
url: /es/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | Una matriz de estructuras [`PointF`](../../pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por *srcRect*. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por *destPoints*. |

### Ver también

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | Una matriz de estructuras [`PointF`](../../pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por *srcRect*. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por *destPoints*. |
| matrix | Matrix | Una [`Matrix`](../../matrix/) que especifica una transformación geométrica para aplicar a la ruta. |

### Ver también

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | Una matriz de estructuras [`PointF`](../../pointf/) que define un paralelogramo al que se transforma el rectángulo definido por *srcRect*. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por *destPoints*. |
| matrix | Matrix | Una [`Matrix`](../../matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | WarpMode | Una enumeración [`WarpMode`](../../warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |

### Ver también

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Aplica una transformación de deformación, definida por un rectángulo y un paralelogramo, a este [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destPoints | PointF[] | Una matriz de estructuras [`PointF`](../../pointf/) que definen un paralelogramo al que se transforma el rectángulo definido por *srcRect*. La matriz puede contener tres o cuatro elementos. Si la matriz contiene tres elementos, la esquina inferior derecha del paralelogramo se deduce de los tres primeros puntos. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) que representa el rectángulo que se transforma al paralelogramo definido por *destPoints*. |
| matrix | Matrix | Una [`Matrix`](../../matrix/) que especifica una transformación geométrica para aplicar a la ruta. |
| warpMode | WarpMode | Una enumeración [`WarpMode`](../../warpmode/) que especifica si esta operación de deformación usa modo perspectiva o bilineal. |
| flatness | Single | Un valor de 0 a 1 que especifica cuán plana es la ruta resultante. Para más información, consulte los métodos [`Flatten`](../flatten/). |

### Ver también

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


