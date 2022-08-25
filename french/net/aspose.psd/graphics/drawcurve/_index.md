---
title: DrawCurve
second_title: Référence de l'API Aspose.PSD pour .NET
description: Dessine une spline cardinale à travers un tableau spécifié dePointFaspose.psd/pointf structures. Cette méthode utilise une tension par défaut de 05.
type: docs
weight: 200
url: /fr/net/aspose.psd/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../../pointf) structures. Cette méthode utilise une tension par défaut de 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de[`PointF`](../../pointf) structures qui définissent la spline. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../../pointf) structures utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de[`PointF`](../../pointf) structures qui représentent les points qui définissent la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../../pointf) structures. Le dessin commence décalé depuis le début du tableau. Cette méthode utilise une tension par défaut de 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de[`PointF`](../../pointf) structures qui définissent la spline. |
| offset | Int32 | Décalage par rapport au premier élément du tableau du*points* paramètre au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Dessine une spline cardinale à travers un tableau spécifié de[`PointF`](../../pointf) structures utilisant une tension spécifiée. Le dessin commence décalé par rapport au début du tableau.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | PointF[] | Tableau de[`PointF`](../../pointf) structures qui définissent la spline. |
| offset | Int32 | Décalage par rapport au premier élément du tableau du*points* paramètre au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../../point) structures.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de[`Point`](../../point) structures qui définissent la spline. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../../point) structures utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de[`Point`](../../point) structures qui définissent la spline. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Dessine une spline cardinale à travers un tableau spécifié de[`Point`](../../point) structures utilisant une tension spécifiée.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) qui détermine la couleur, la largeur et la hauteur de la courbe. |
| points | Point[] | Tableau de[`Point`](../../point) structures qui définissent la spline. |
| offset | Int32 | Décalage par rapport au premier élément du tableau du*points* paramètre au point de départ de la courbe. |
| numberOfSegments | Int32 | Nombre de segments après le point de départ à inclure dans la courbe. |
| tension | Single | Valeur supérieure ou égale à 0.0F qui spécifie la tension de la courbe. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *points* est nul. |

### Voir également

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* espace de noms [Aspose.PSD](../../graphics)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
