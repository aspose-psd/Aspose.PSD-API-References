---
title: Matrix.Matrix
second_title: Referencia de API de Aspose.PSD para .NET
description: Matrix constructor. Inicializa una nueva instancia de la clase Matrix como matriz de identidad.
type: docs
weight: 10
url: /es/net/aspose.psd/matrix/matrix/
---
## Matrix() {#constructor}

Inicializa una nueva instancia de la clase Matrix como matriz de identidad.

```csharp
public Matrix()
```

### Ver también

* class [Matrix](../)
* espacio de nombres [Aspose.PSD](../../matrix/)
* asamblea [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Inicializa una nueva instancia del[`Matrix`](../) clase.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| m11 | Single | m00 M11 Escala X |
| m12 | Single | m10 M12 Cortante Y |
| m21 | Single | m01 M21 Cortante X |
| m22 | Single | m11 M22 Escala Y |
| m31 | Single | m02 M31 Traducir X |
| m32 | Single | m12 M32 Trasladar Y |

### Ver también

* class [Matrix](../)
* espacio de nombres [Aspose.PSD](../../matrix/)
* asamblea [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Inicializa una nueva instancia del[`Matrix`](../) clase a la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../rectanglef/) estructura que representa el rectángulo a transformar. |
| plgpts | PointF[] | Una matriz de tres[`PointF`](../../pointf/)estructuras que representan los puntos de un paralelogramo en el que se van a transformar las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo está implícita en las tres primeras esquinas. |

### Ver también

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* espacio de nombres [Aspose.PSD](../../matrix/)
* asamblea [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Inicializa una nueva instancia del[`Matrix`](../) clase a la transformación geométrica definida por el rectángulo especificado y la matriz de puntos.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | A[`Rectangle`](../../rectangle/) estructura que representa el rectángulo a transformar. |
| plgpts | Point[] | Una matriz de tres[`Point`](../../point/)estructuras que representan los puntos de un paralelogramo en el que se van a transformar las esquinas superior izquierda, superior derecha e inferior izquierda del rectángulo. La esquina inferior derecha del paralelogramo está implícita en las tres primeras esquinas. |

### Ver también

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* espacio de nombres [Aspose.PSD](../../matrix/)
* asamblea [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Hace una copia del[`Matrix`](../) clase.

```csharp
public Matrix(Matrix origin)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| origin | Matrix | Una matriz base para hacer frente |

### Ver también

* class [Matrix](../)
* espacio de nombres [Aspose.PSD](../../matrix/)
* asamblea [Aspose.PSD](../../../)


