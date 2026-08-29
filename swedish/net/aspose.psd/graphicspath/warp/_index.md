---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GraphicsPath-metoden. Tillämpar en warp‑transformering definierad av en rektangel och ett parallellogram på detta GraphicsPath"
type: docs
weight: 180
url: /sv/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En array av [`PointF`](../../pointf/)-strukturer som definierar ett parallellogram till vilket rektangeln som definieras av *srcRect* transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antas det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | RectangleF | En [`RectangleF`](../../rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av *destPoints*. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En array av [`PointF`](../../pointf/)-strukturer som definierar ett parallellogram till vilket rektangeln som definieras av *srcRect* transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antas det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | RectangleF | En [`RectangleF`](../../rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av *destPoints*. |
| matrix | Matrix | En [`Matrix`](../../matrix/) som specificerar en geometrisk transformering att tillämpa på vägen. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En array av [`PointF`](../../pointf/)-strukturer som definierar ett parallellogram till vilket rektangeln som definieras av *srcRect* transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antas det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | RectangleF | En [`RectangleF`](../../rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av *destPoints*. |
| matrix | Matrix | En [`Matrix`](../../matrix/) som specificerar en geometrisk transformering att tillämpa på vägen. |
| warpMode | WarpMode | En [`WarpMode`](../../warpmode/)-enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Tillämpar en warp‑transformering, definierad av en rektangel och ett parallellogram, på detta [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| destPoints | PointF[] | En array av [`PointF`](../../pointf/)-strukturer som definierar ett parallellogram till vilket rektangeln som definieras av *srcRect* transformeras. Arrayen kan innehålla antingen tre eller fyra element. Om arrayen innehåller tre element, antas det nedre högra hörnet av parallellogrammet av de första tre punkterna. |
| srcRect | RectangleF | En [`RectangleF`](../../rectanglef/) som representerar rektangeln som transformeras till parallellogrammet definierat av *destPoints*. |
| matrix | Matrix | En [`Matrix`](../../matrix/) som specificerar en geometrisk transformering att tillämpa på vägen. |
| warpMode | WarpMode | En [`WarpMode`](../../warpmode/)-enumeration som specificerar om denna warp‑operation använder perspektiv‑ eller bilineärt läge. |
| flatness | Single | Ett värde från 0 till 1 som specificerar hur platt den resulterande vägen är. För mer information, se [`Flatten`](../flatten/)-metoderna. |

### Se även

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


