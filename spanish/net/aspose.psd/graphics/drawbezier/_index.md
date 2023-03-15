---
title: Graphics.DrawBezier
second_title: Referencia de API de Aspose.PSD para .NET
description: Graphics método. Dibuja una spline de Bézier definida por cuatro pares ordenados de coordenadas que representan puntos.
type: docs
weight: 170
url: /es/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Dibuja una spline de Bézier definida por cuatro pares ordenados de coordenadas que representan puntos.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de la curva. |
| x1 | Single | La coordenada x del punto inicial de la curva. |
| y1 | Single | La coordenada y del punto inicial de la curva. |
| x2 | Single | La coordenada x del primer punto de control de la curva. |
| y2 | Single | La coordenada y del primer punto de control de la curva. |
| x3 | Single | La coordenada x del segundo punto de control de la curva. |
| y3 | Single | La coordenada y del segundo punto de control de la curva. |
| x4 | Single | La coordenada x del punto final de la curva. |
| y4 | Single | La coordenada y del punto final de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Dibuja una spline de Bézier definida por cuatro[`PointF`](../../pointf/) estructuras.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de la curva. |
| pt1 | PointF | [`PointF`](../../pointf/) estructura que representa el punto inicial de la curva. |
| pt2 | PointF | [`PointF`](../../pointf/) estructura que representa el primer punto de control de la curva. |
| pt3 | PointF | [`PointF`](../../pointf/) estructura que representa el segundo punto de control de la curva. |
| pt4 | PointF | [`PointF`](../../pointf/) estructura que representa el punto final de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Dibuja una spline de Bézier definida por cuatro[`Point`](../../point/) estructuras.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) estructura que determina el color, el ancho y el estilo de la curva. |
| pt1 | Point | [`Point`](../../point/) estructura que representa el punto inicial de la curva. |
| pt2 | Point | [`Point`](../../point/) estructura que representa el primer punto de control de la curva. |
| pt3 | Point | [`Point`](../../point/) estructura que representa el segundo punto de control de la curva. |
| pt4 | Point | [`Point`](../../point/) estructura que representa el punto final de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)


