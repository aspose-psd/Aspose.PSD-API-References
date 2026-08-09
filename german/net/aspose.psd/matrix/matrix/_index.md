---
title: "Matrix.Matrix"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Matrix-Konstruktor. Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix"
type: docs
weight: 10
url: /de/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Initialisiert eine neue Instanz der Matrix-Klasse als Einheitsmatrix.

```csharp
public Matrix()
```

### Siehe auch

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Initialisiert eine neue Instanz der [`Matrix`](../)-Klasse.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m11 | Single | m00 M11 Skalierung X |
| m12 | Single | m10 M12 Scheren Y |
| m21 | Single | m01 M21 Scheren X |
| m22 | Single | m11 M22 Skalierung Y |
| m31 | Single | m02 M31 Übersetzen X |
| m32 | Single | m12 M32 Übersetzen Y |

### Siehe auch

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initialisiert eine neue Instanz der [`Matrix`](../)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | RectangleF | Eine [`RectangleF`](../../rectanglef/)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | PointF[] | Ein Array von drei [`PointF`](../../pointf/)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Siehe auch

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initialisiert eine neue Instanz der [`Matrix`](../)-Klasse mit der geometrischen Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Eine [`Rectangle`](../../rectangle/)-Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | Point[] | Ein Array von drei [`Point`](../../point/)-Strukturen, das die Punkte eines Parallelogramms darstellt, zu dem die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden sollen. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Erstellt eine Kopie der [`Matrix`](../)-Klasse.

```csharp
public Matrix(Matrix origin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | Matrix | Eine Basismatrix zum Kopieren |

### Siehe auch

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


