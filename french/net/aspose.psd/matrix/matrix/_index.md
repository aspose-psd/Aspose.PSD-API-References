---
title: "Matrix.Matrix"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur Matrix. Initialise une nouvelle instance de la classe Matrix comme la matrice identité"
type: docs
weight: 10
url: /fr/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Initialise une nouvelle instance de la classe Matrix comme matrice identité.

```csharp
public Matrix()
```

### Voir aussi

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Initialise une nouvelle instance de la classe [`Matrix`](../).

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| m11 | Single | m00 M11 Échelle X |
| m12 | Single | m10 M12 Cisaillement Y |
| m21 | Single | m01 M21 Cisaillement X |
| m22 | Single | m11 M22 Échelle Y |
| m31 | Single | m02 M31 Translation X |
| m32 | Single | m12 M32 Translate Y |

### Voir aussi

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Initialise une nouvelle instance de la classe [`Matrix`](../) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | RectangleF | Une structure [`RectangleF`](../../rectanglef/) qui représente le rectangle à transformer. |
| plgpts | PointF[] | Un tableau de trois structures [`PointF`](../../pointf/) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Voir aussi

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Initialise une nouvelle instance de la classe [`Matrix`](../) pour la transformation géométrique définie par le rectangle spécifié et le tableau de points.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Une structure [`Rectangle`](../../rectangle/) qui représente le rectangle à transformer. |
| plgpts | Point[] | Un tableau de trois structures [`Point`](../../point/) qui représente les points d'un parallélogramme vers lequel les coins supérieur gauche, supérieur droit et inférieur gauche du rectangle doivent être transformés. Le coin inférieur droit du parallélogramme est implicite à partir des trois premiers coins. |

### Voir aussi

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

Crée une copie de la classe [`Matrix`](../).

```csharp
public Matrix(Matrix origin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| origin | Matrix | Une matrice de base pour la copie. |

### Voir aussi

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


