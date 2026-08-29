---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GraphicsPath-Methode. Wendet eine Verzerrungstransformation an, die durch ein Rechteck und ein Parallelogramm definiert ist, auf diesen GraphicsPath."
type: docs
weight: 180
url: /de/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf dieses [`GraphicsPath`](../) an.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Ein Array von [`PointF`](../../pointf/)-Strukturen, die ein Parallelogramm definieren, zu dem das durch *srcRect* definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | Ein [`RectangleF`](../../rectanglef/), der das Rechteck darstellt, das in das durch *destPoints* definierte Parallelogramm transformiert wird. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf dieses [`GraphicsPath`](../) an.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Ein Array von [`PointF`](../../pointf/)-Strukturen, die ein Parallelogramm definieren, zu dem das durch *srcRect* definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | Ein [`RectangleF`](../../rectanglef/), der das Rechteck darstellt, das in das durch *destPoints* definierte Parallelogramm transformiert wird. |
| matrix | Matrix | Eine [`Matrix`](../../matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf dieses [`GraphicsPath`](../) an.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Ein Array von [`PointF`](../../pointf/)-Strukturen, das ein Parallelogramm definiert, zu dem das durch *srcRect* definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | Ein [`RectangleF`](../../rectanglef/), der das Rechteck darstellt, das in das durch *destPoints* definierte Parallelogramm transformiert wird. |
| matrix | Matrix | Eine [`Matrix`](../../matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | Eine [`WarpMode`](../../warpmode/)-Aufzählung, die angibt, ob diese Verzerrungsoperation den Perspektiv- oder den bilinearen Modus verwendet. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Wendet eine Verzerrungstransformation, definiert durch ein Rechteck und ein Parallelogramm, auf dieses [`GraphicsPath`](../) an.

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | PointF[] | Ein Array von [`PointF`](../../pointf/)-Strukturen, die ein Parallelogramm definieren, zu dem das durch *srcRect* definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | RectangleF | Ein [`RectangleF`](../../rectanglef/), der das Rechteck darstellt, das in das durch *destPoints* definierte Parallelogramm transformiert wird. |
| matrix | Matrix | Eine [`Matrix`](../../matrix/), die eine geometrische Transformation angibt, die auf den Pfad angewendet werden soll. |
| warpMode | WarpMode | Eine [`WarpMode`](../../warpmode/)-Aufzählung, die angibt, ob diese Verzerrungsoperation den Perspektiv- oder den bilinearen Modus verwendet. |
| flatness | Single | Ein Wert von 0 bis 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie in den [`Flatten`](../flatten/)-Methoden. |

### Siehe auch

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


