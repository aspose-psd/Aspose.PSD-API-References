---
title: GraphicsPath.Warp
second_title: Aspose.PSD für .NET-API-Referenz
description: GraphicsPath methode. Wendet eine durch ein Rechteck und ein Parallelogramm definierte WarpTransformation darauf anGraphicsPath .
type: docs
weight: 180
url: /de/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect*wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect*wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect*wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) Enumeration, die angibt, ob dieser Warp-Vorgang den perspektivischen oder den bilinearen Modus verwendet. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Wendet eine durch ein Rechteck und ein Parallelogramm definierte Warp-Transformation darauf an[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Eine Reihe von[`PointF`](../../pointf/) Strukturen, die ein Parallelogramm definieren, zu dem das Rechteck definiert ist*srcRect*wird transformiert. Das Array kann entweder drei oder vier Elemente enthalten. Wenn das Array drei Elemente enthält, wird die untere rechte Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) das das Rechteck darstellt, das in das durch definierte Parallelogramm transformiert wird*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) Enumeration, die angibt, ob dieser Warp-Vorgang den perspektivischen oder den bilinearen Modus verwendet. |
| flatness | Single | Ein Wert zwischen 0 und 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie unter[`Flatten`](../flatten/) Methoden. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)


