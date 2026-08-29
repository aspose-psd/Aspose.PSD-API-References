---
title: "Graphics.FillPie"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Graphics. Rellena el interior de un sector de pastel definido por una elipse especificada por una estructura RectangleF y dos líneas radiales."
type: docs
weight: 380
url: /es/net/aspose.psd/graphics/fillpie/
---
{{< psd/tize >}}
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Rellena el interior de un sector de pastel definido por una elipse especificada por una estructura [`RectangleF`](../../rectanglef/) y dos líneas radiales.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) que determina las características del relleno. |
| rect | Rectangle | Estructura [`Rectangle`](../../rectangle/) que representa el rectángulo delimitador que define la elipse de la cual proviene el sector de pastel. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado del sector de pastel. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el segundo lado de la sección de pastel. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El *brush* es nulo. |

### Ver también

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Rellena el interior de un sector de pastel definido por una elipse especificada por una estructura [`RectangleF`](../../rectanglef/) y dos líneas radiales.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) que determina las características del relleno. |
| rect | RectangleF | Estructura [`RectangleF`](../../rectanglef/) que representa el rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado del sector de pastel. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el segundo lado de la sección de pastel. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El *brush* es nulo. |

### Ver también

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) que determina las características del relleno. |
| x | Single | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | Single | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | Single | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | Single | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | Single | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado del sector de pastel. |
| sweepAngle | Single | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el segundo lado de la sección de pastel. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El *brush* es nulo. |

### Ver también

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Rellena el interior de una porción de pastel definida por una elipse especificada por un par de coordenadas, un ancho, una altura y dos líneas radiales.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) que determina las características del relleno. |
| x | Int32 | La coordenada x de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| y | Int32 | La coordenada y de la esquina superior izquierda del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| width | Int32 | Ancho del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| height | Int32 | Altura del rectángulo delimitador que define la elipse de la cual proviene la sección de pastel. |
| startAngle | Int32 | Ángulo en grados medido en sentido horario desde el eje x hasta el primer lado del sector de pastel. |
| sweepAngle | Int32 | Ángulo en grados medido en sentido horario desde el parámetro *startAngle* hasta el segundo lado de la sección de pastel. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El *brush* es nulo. |

### Ver también

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


