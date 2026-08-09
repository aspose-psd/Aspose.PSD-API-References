---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode GraphicsPath. Applique une transformation de déformation définie par un rectangle et un parallélogramme à ce GraphicsPath"
type: docs
weight: 180
url: /fr/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | Un tableau de structures [`PointF`](../../pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par *srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) qui représente le rectangle transformé en parallélogramme défini par *destPoints*. |

### Voir aussi

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | Un tableau de structures [`PointF`](../../pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par *srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) qui représente le rectangle transformé en parallélogramme défini par *destPoints*. |
| matrix | Matrix | Une [`Matrix`](../../matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |

### Voir aussi

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | Un tableau de structures [`PointF`](../../pointf/) qui définit un parallélogramme vers lequel le rectangle défini par *srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) qui représente le rectangle transformé en parallélogramme défini par *destPoints*. |
| matrix | Matrix | Une [`Matrix`](../../matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | WarpMode | Une énumération [`WarpMode`](../../warpmode/) qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |

### Voir aussi

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| destPoints | PointF[] | Un tableau de structures [`PointF`](../../pointf/) qui définissent un parallélogramme vers lequel le rectangle défini par *srcRect* est transformé. Le tableau peut contenir trois ou quatre éléments. Si le tableau contient trois éléments, le coin inférieur droit du parallélogramme est implicite à partir des trois premiers points. |
| srcRect | RectangleF | Un [`RectangleF`](../../rectanglef/) qui représente le rectangle transformé en parallélogramme défini par *destPoints*. |
| matrix | Matrix | Une [`Matrix`](../../matrix/) qui spécifie une transformation géométrique à appliquer au chemin. |
| warpMode | WarpMode | Une énumération [`WarpMode`](../../warpmode/) qui spécifie si cette opération de déformation utilise le mode perspective ou bilinéaire. |
| flatness | Single | Une valeur comprise entre 0 et 1 qui spécifie le degré d’aplatissement du chemin résultant. Pour plus d’informations, consultez les méthodes [`Flatten`](../flatten/). |

### Voir aussi

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


