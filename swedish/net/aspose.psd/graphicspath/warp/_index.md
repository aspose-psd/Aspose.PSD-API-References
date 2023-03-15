---
title: GraphicsPath.Warp
second_title: Aspose.PSD för .NET API-referens
description: GraphicsPath metod. Tillämpar en varptransform definierad av en rektangel och ett parallellogram på dettaGraphicsPath .
type: docs
weight: 180
url: /sv/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En uppställning av[`PointF`](../../pointf/) strukturer som definierar ett parallellogram till vilket rektangeln definieras av*srcRect*förvandlas. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antyds det nedre högra hörnet av parallellogrammet av de tre första punkterna. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) som representerar rektangeln som omvandlas till parallellogrammet som definieras av*destPoints*. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En uppställning av[`PointF`](../../pointf/) strukturer som definierar ett parallellogram till vilket rektangeln definieras av*srcRect*förvandlas. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antyds det nedre högra hörnet av parallellogrammet av de tre första punkterna. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) som representerar rektangeln som omvandlas till parallellogrammet som definieras av*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) som anger en geometrisk transformation som ska tillämpas på banan. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En uppställning av[`PointF`](../../pointf/) strukturer som definierar ett parallellogram till vilket rektangeln definieras av*srcRect*förvandlas. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antyds det nedre högra hörnet av parallellogrammet av de tre första punkterna. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) som representerar rektangeln som omvandlas till parallellogrammet som definieras av*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) som anger en geometrisk transformation som ska tillämpas på banan. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) uppräkning som anger om denna förvrängningsoperation använder perspektiv eller bilinjärt läge. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Tillämpar en varptransform, definierad av en rektangel och ett parallellogram, på detta[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En uppställning av[`PointF`](../../pointf/) strukturer som definierar ett parallellogram till vilket rektangeln definieras av*srcRect*förvandlas. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antyds det nedre högra hörnet av parallellogrammet av de tre första punkterna. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) som representerar rektangeln som omvandlas till parallellogrammet som definieras av*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) som anger en geometrisk transformation som ska tillämpas på banan. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) uppräkning som anger om denna förvrängningsoperation använder perspektiv eller bilinjärt läge. |
| flatness | Single | Ett värde från 0 till 1 som anger hur platt den resulterande vägen är. För mer information, se[`Flatten`](../flatten/) metoder. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)


