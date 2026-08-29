---
title: "Graphics.DrawLines"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Graphics. Dibuja una serie de segmentos de línea que conectan una matriz de estructuras Point"
type: docs
weight: 270
url: /es/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | Point[] | Matriz de estructuras [`Point`](../../point/) que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | La matriz *points* contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Dibuja una serie de segmentos de línea que conectan una matriz de estructuras [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo de los segmentos de línea. |
| points | PointF[] | Matriz de estructuras [`PointF`](../../pointf/) que representan los puntos a conectar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |
| ArgumentException | La matriz *points* contiene menos de 2 puntos. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


