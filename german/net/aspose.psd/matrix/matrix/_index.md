---
title: Matrix.Matrix
second_title: Aspose.PSD für .NET-API-Referenz
description: Matrix constructeur. Initialisiert eine neue Instanz der MatrixKlasse als Identitätsmatrix.
type: docs
weight: 10
url: /de/net/aspose.psd/matrix/matrix/
---
## Matrix() {#constructor}

Initialisiert eine neue Instanz der Matrix-Klasse als Identitätsmatrix.

```csharp
public Matrix()
```

### Siehe auch

* class [Matrix](../)
* namensraum [Aspose.PSD](../../matrix/)
* Montage [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Initialisiert eine neue Instanz von[`Matrix`](../) Klasse.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| m11 | Single | m00 M11 Skala X |
| m12 | Single | m10 M12 Schere Y |
| m21 | Single | m01 M21 Schere X |
| m22 | Single | m11 M22 Skala Y |
| m31 | Single | m02 M31 X übersetzen |
| m32 | Single | m12 M32 Übersetzen Y |

### Siehe auch

* class [Matrix](../)
* namensraum [Aspose.PSD](../../matrix/)
* Montage [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initialisiert eine neue Instanz von[`Matrix`](../) Klasse in die geometrische Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../rectanglef/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | PointF[] | Eine Reihe von drei[`PointF`](../../pointf/)Strukturen, die die Punkte eines Parallelogramms darstellen, in die die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden soll. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Siehe auch

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namensraum [Aspose.PSD](../../matrix/)
* Montage [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initialisiert eine neue Instanz von[`Matrix`](../) Klasse in die geometrische Transformation, die durch das angegebene Rechteck und das Array von Punkten definiert ist.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | A[`Rectangle`](../../rectangle/) Struktur, die das zu transformierende Rechteck darstellt. |
| plgpts | Point[] | Eine Reihe von drei[`Point`](../../point/)Strukturen, die die Punkte eines Parallelogramms darstellen, in die die obere linke, obere rechte und untere linke Ecke des Rechtecks transformiert werden soll. Die untere rechte Ecke des Parallelogramms wird durch die ersten drei Ecken impliziert. |

### Siehe auch

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namensraum [Aspose.PSD](../../matrix/)
* Montage [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Erstellt eine Kopie der[`Matrix`](../) Klasse.

```csharp
public Matrix(Matrix origin)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | Matrix | Eine Basismatrix zur Bewältigung |

### Siehe auch

* class [Matrix](../)
* namensraum [Aspose.PSD](../../matrix/)
* Montage [Aspose.PSD](../../../)


