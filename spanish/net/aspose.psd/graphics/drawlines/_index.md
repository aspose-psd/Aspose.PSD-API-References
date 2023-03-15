---
title: Graphics.DrawLines
second_title: Referencia de API de Aspose.PSD para .NET
description: Graphics método. Dibuja una serie de segmentos de línea que conectan una matriz dePoint estructuras.
type: docs
weight: 260
url: /es/net/aspose.psd/graphics/drawlines/
---
## DrawLines(Pen, Point[]) {#drawlines_1}

Dibuja una serie de segmentos de línea que conectan una matriz de[`Point`](../../point/) estructuras.

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | Point[] | Gama de[`Point`](../../point/) estructuras que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | El*points* matriz contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Dibuja una serie de segmentos de línea que conectan una matriz de[`PointF`](../../pointf/) estructuras.

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | PointF[] | Gama de[`PointF`](../../pointf/) estructuras que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | El*points* matriz contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)


