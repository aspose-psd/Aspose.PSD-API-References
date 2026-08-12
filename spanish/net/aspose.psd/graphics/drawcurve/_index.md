---
title: "Graphics.DrawCurve"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Graphics. Dibuja una spline cardinal a través de una matriz especificada de estructuras PointF. Este método usa una tensión predeterminada de 0.5."
type: docs
weight: 210
url: /es/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../../pointf/). Este método usa una tensión predeterminada de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Matriz de estructuras [`PointF`](../../pointf/) que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../../pointf/) usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Matriz de estructuras [`PointF`](../../pointf/) que representan los puntos que definen la curva. |
| tensión | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../../pointf/). El dibujo comienza con un desplazamiento desde el inicio de la matriz. Este método usa una tensión predeterminada de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Matriz de estructuras [`PointF`](../../pointf/) que definen la spline. |
| desplazamiento | Int32 | Desplazamiento desde el primer elemento de la matriz del parámetro *points* hasta el punto inicial en la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial que se incluyen en la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`PointF`](../../pointf/) usando una tensión especificada. El dibujo comienza con un desplazamiento desde el inicio de la matriz.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Matriz de estructuras [`PointF`](../../pointf/) que definen la spline. |
| desplazamiento | Int32 | Desplazamiento desde el primer elemento de la matriz del parámetro *points* hasta el punto inicial en la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial que se incluyen en la curva. |
| tensión | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../../point/).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Matriz de estructuras [`Point`](../../point/) que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../../point/) usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Matriz de estructuras [`Point`](../../point/) que definen la spline. |
| tensión | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Dibuja una spline cardinal a través de una matriz especificada de estructuras [`Point`](../../point/) usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Matriz de estructuras [`Point`](../../point/) que definen la spline. |
| desplazamiento | Int32 | Desplazamiento desde el primer elemento de la matriz del parámetro *points* hasta el punto inicial en la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial que se incluyen en la curva. |
| tensión | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


