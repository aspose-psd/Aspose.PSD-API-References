---
title: GraphicsPath.Warp
second_title: Aspose.PSD voor .NET API-referentie
description: GraphicsPath methode. Past hierop een vervormingstransformatie toe gedefinieerd door een rechthoek en een parallellogramGraphicsPath .
type: docs
weight: 180
url: /nl/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | PointF[] | Een reeks van[`PointF`](../../pointf/) structuren die een parallellogram definiëren waaraan de rechthoek wordt gedefinieerd door*srcRect*wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechterbenedenhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) dat vertegenwoordigt de rechthoek die wordt getransformeerd naar het parallellogram gedefinieerd door*destPoints*. |

### Zie ook

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* naamruimte [Aspose.PSD](../../graphicspath/)
* montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | PointF[] | Een reeks van[`PointF`](../../pointf/) structuren die een parallellogram definiëren waaraan de rechthoek wordt gedefinieerd door*srcRect*wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechterbenedenhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) dat vertegenwoordigt de rechthoek die wordt getransformeerd naar het parallellogram gedefinieerd door*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |

### Zie ook

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* naamruimte [Aspose.PSD](../../graphicspath/)
* montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | PointF[] | Een reeks van[`PointF`](../../pointf/) structuren die een parallellogram definiëren waaraan de rechthoek wordt gedefinieerd door*srcRect*wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechterbenedenhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) dat vertegenwoordigt de rechthoek die wordt getransformeerd naar het parallellogram gedefinieerd door*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) opsomming die specificeert of deze warp-bewerking gebruikmaakt van perspectief of bilineaire modus. |

### Zie ook

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* naamruimte [Aspose.PSD](../../graphicspath/)
* montage [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Past hierop een vervormingstransformatie toe, gedefinieerd door een rechthoek en een parallellogram[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destPoints | PointF[] | Een reeks van[`PointF`](../../pointf/) structuren die een parallellogram definiëren waaraan de rechthoek wordt gedefinieerd door*srcRect*wordt getransformeerd. De array kan drie of vier elementen bevatten. Als de array drie elementen bevat, wordt de rechterbenedenhoek van het parallellogram geïmpliceerd door de eerste drie punten. |
| srcRect | RectangleF | A[`RectangleF`](../../rectanglef/) dat vertegenwoordigt de rechthoek die wordt getransformeerd naar het parallellogram gedefinieerd door*destPoints*. |
| matrix | Matrix | A[`Matrix`](../../matrix/) die een geometrische transformatie specificeert die op het pad moet worden toegepast. |
| warpMode | WarpMode | A[`WarpMode`](../../warpmode/) opsomming die specificeert of deze warp-bewerking gebruikmaakt van perspectief of bilineaire modus. |
| flatness | Single | Een waarde van 0 tot en met 1 die aangeeft hoe vlak het resulterende pad is. Voor meer informatie, zie de[`Flatten`](../flatten/) methoden. |

### Zie ook

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* naamruimte [Aspose.PSD](../../graphicspath/)
* montage [Aspose.PSD](../../../)


