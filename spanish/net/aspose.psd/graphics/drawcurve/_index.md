---
title: Graphics.DrawCurve
second_title: Referencia de API de Aspose.PSD para .NET
description: Graphics método. Dibuja una spline cardinal a través de una matriz específica dePointF estructuras Este método utiliza una tensión predeterminada de 0.5.
type: docs
weight: 200
url: /es/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf/) estructuras Este método utiliza una tensión predeterminada de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf/) estructuras que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf/) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf/) estructuras que representan los puntos que definen la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf/) estructuras El dibujo comienza desplazado desde el principio de la matriz. Este método utiliza una tensión predeterminada de 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf/) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Dibuja una spline cardinal a través de una matriz específica de[`PointF`](../../pointf/) estructuras usando una tensión específica. El dibujo comienza desplazado desde el principio de la matriz.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | PointF[] | Gama de[`PointF`](../../pointf/) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point/) estructuras.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point/) estructuras que definen la spline. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point/) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point/) estructuras que definen la spline. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Dibuja una spline cardinal a través de una matriz específica de[`Point`](../../point/) estructuras usando una tensión especificada.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y la altura de la curva. |
| points | Point[] | Gama de[`Point`](../../point/) estructuras que definen la spline. |
| offset | Int32 | Desplazamiento desde el primer elemento en la matriz de la*points* parámetro al punto inicial de la curva. |
| numberOfSegments | Int32 | Número de segmentos después del punto inicial para incluir en la curva. |
| tension | Single | Valor mayor o igual a 0.0F que especifica la tensión de la curva. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. -o- *points* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)


