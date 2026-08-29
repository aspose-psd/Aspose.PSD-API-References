---
title: "Matrix.Matrix"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Matrix-konstruktor. Initierar en ny instans av Matrix-klassen som identitetsmatrisen"
type: docs
weight: 10
url: /sv/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Initierar en ny instans av Matrix-klassen som identitetsmatris.

```csharp
public Matrix()
```

### Se även

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Initierar en ny instans av [`Matrix`](../)-klassen.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m11 | Single | m00 M11 Skala X |
| m12 | Single | m10 M12 Skjuv Y |
| m21 | Single | m01 M21 Skjuv X |
| m22 | Single | m11 M22 Skala Y |
| m31 | Single | m02 M31 Translatera X |
| m32 | Single | m12 M32 Translatera Y |

### Se även

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initierar en ny instans av klassen [`Matrix`](../) till den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | En [`RectangleF`](../../rectanglef/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | PointF[] | En array av tre [`PointF`](../../pointf/) strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### Se även

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initierar en ny instans av klassen [`Matrix`](../) till den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | En [`Rectangle`](../../rectangle/) struktur som representerar rektangeln som ska transformeras. |
| plgpts | Point[] | En array av tre [`Point`](../../point/) strukturer som representerar punkterna i ett parallellogram till vilket det övre vänstra, övre högra och nedre vänstra hörnet av rektangeln ska transformeras. Det nedre högra hörnet av parallellogrammet antas av de första tre hörnen. |

### Se även

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Skapar en kopia av klassen [`Matrix`](../).

```csharp
public Matrix(Matrix origin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| SeekOrigin | Matris | En basmatris för kopiering |

### Se även

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


