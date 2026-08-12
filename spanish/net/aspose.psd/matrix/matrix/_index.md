---
title: "Matrix.Matrix"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor Matrix. Inicializa una nueva instancia de la clase Matrix como la matriz identidad"
type: docs
weight: 10
url: /es/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Inicializa una nueva instancia de la clase Matrix como la matriz identidad.

```csharp
public Matrix()
```

### Ver también

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Inicializa una nueva instancia de la clase [`Matrix`](../).

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m11 | Single | m00 M11 Escala X |
| m12 | Single | m10 M12 Cizalladura Y |
| m21 | Single | m01 M21 Cizalladura X |
| m22 | Single | m11 M22 Escala Y |
| m31 | Single | m02 M31 Trasladar X |
| m32 | Single | m12 M32 Traducir Y |

### Ver también

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Inicializa una nueva instancia de la clase [`Matrix`](../) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | RectangleF | Una estructura [`RectangleF`](../../rectanglef/) que representa el rectángulo a transformar. |
| plgpts | PointF[] | Una matriz de tres estructuras [`PointF`](../../pointf/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Ver también

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Inicializa una nueva instancia de la clase [`Matrix`](../) para la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | Una estructura [`Rectangle`](../../rectangle/) que representa el rectángulo a transformar. |
| plgpts | Point[] | Una matriz de tres estructuras [`Point`](../../point/) que representa los puntos de un paralelogramo al que se transformarán las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo se deduce de las tres primeras esquinas. |

### Ver también

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Crea una copia de la clase [`Matrix`](../).

```csharp
public Matrix(Matrix origin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | Matrix | Una matriz base para copiar |

### Ver también

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


