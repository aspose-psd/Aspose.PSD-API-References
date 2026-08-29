---
title: "Graphics.DrawCurve"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Trace une spline cardinal à travers un tableau spécifié de structures PointF. Cette méthode utilise une tension par défaut de 0.5"
type: docs
weight: 210
url: /fr/net/aspose.psd/graphics/drawcurve/
---
{{< psd/tize >}}
## DrawCurve(Pen, PointF[]) {#drawcurve}

Trace une spline cardinal à travers un tableau spécifié de structures [`PointF`](../../pointf/). Cette méthode utilise une tension par défaut de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de structures [`PointF`](../../pointf/) qui définissent la spline. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Trace une spline cardinal à travers un tableau spécifié de structures [`PointF`](../../pointf/) en utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de structures [`PointF`](../../pointf/) qui représentent les points définissant la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Trace une spline cardinal à travers un tableau spécifié de structures [`PointF`](../../pointf/). Le dessin commence avec un décalage depuis le début du tableau. Cette méthode utilise une tension par défaut de 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de structures [`PointF`](../../pointf/) qui définissent la spline. |
| offset | Int32 | Décalage du premier élément du tableau du paramètre *points* jusqu'au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Trace une spline cardinal à travers un tableau spécifié de structures [`PointF`](../../pointf/) en utilisant une tension spécifiée. Le dessin commence avec un décalage depuis le début du tableau.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de structures [`PointF`](../../pointf/) qui définissent la spline. |
| offset | Int32 | Décalage du premier élément du tableau du paramètre *points* jusqu'au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Trace une spline cardinal à travers un tableau spécifié de structures [`Point`](../../point/).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de structures [`Point`](../../point/) qui définissent la spline. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Trace une spline cardinal à travers un tableau spécifié de structures [`Point`](../../point/) en utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de structures [`Point`](../../point/) qui définissent la spline. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Trace une spline cardinal à travers un tableau spécifié de structures [`Point`](../../point/) en utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de structures [`Point`](../../point/) qui définissent la spline. |
| offset | Int32 | Décalage du premier élément du tableau du paramètre *points* jusqu'au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


