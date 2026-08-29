---
title: "Graphics.DrawArc"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Graphics. Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura."
type: docs
weight: 170
url: /es/net/aspose.psd/graphics/drawarc/
---
{{< psd/tize >}}
## DrawArc(Pen, float, float, float, float, float, float) {#drawarc_3}

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

```csharp
public void DrawArc(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo del arco. |
| x | Single | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | Single | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | Single | Ancho del rectángulo que define la elipse. |
| height | Single | Altura del rectángulo que define la elipse. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el punto final del arco. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, RectangleF, float, float) {#drawarc_1}

Dibuja un arco que representa una porción de una elipse especificada por una estructura [`RectangleF`](../../rectanglef/).

```csharp
public void DrawArc(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo del arco. |
| rect | RectangleF | Estructura [`RectangleF`](../../rectanglef/) que define los límites de la elipse. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el punto final del arco. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo |

### Ver también

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, int, int, int, int, int, int) {#drawarc_2}

Dibuja un arco que representa una porción de una elipse especificada por un par de coordenadas, un ancho y una altura.

```csharp
public void DrawArc(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo del arco. |
| x | Int32 | La coordenada x de la esquina superior izquierda del rectángulo que define la elipse. |
| y | Int32 | La coordenada y de la esquina superior izquierda del rectángulo que define la elipse. |
| width | Int32 | Ancho del rectángulo que define la elipse. |
| height | Int32 | Altura del rectángulo que define la elipse. |
| startAngle | Int32 | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | Int32 | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el punto final del arco. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawArc(Pen, Rectangle, float, float) {#drawarc}

Dibuja un arco que representa una porción de una elipse especificada por una estructura [`Rectangle`](../../rectangle/).

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) que determina el color, el ancho y el estilo del arco. |
| rect | Rectangle | Estructura [`RectangleF`](../../rectanglef/) que define los límites de la elipse. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el punto inicial del arco. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el punto final del arco. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *pen* es nulo. |

### Ver también

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


