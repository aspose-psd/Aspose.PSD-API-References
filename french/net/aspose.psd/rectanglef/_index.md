---
title: "Structure RectangleF"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.RectangleF. Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle."
type: docs
weight: 5850
url: /fr/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle.

```csharp
public struct RectangleF
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Initialise une nouvelle instance de la structure `RectangleF` avec la position et la taille spécifiées. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Initialise une nouvelle instance de la structure `RectangleF` avec la position et la taille spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Obtient une nouvelle instance de la structure `RectangleF` dont les valeurs [`X`](./x/), [`Y`](./y/), [`Width`](./width/) et [`Height`](./height/) sont réglées à zéro. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Obtient ou définit la coordonnée y qui est la somme de [`Y`](./y/) et de [`Height`](./height/) de cette structure `RectangleF`. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Obtient ou définit la hauteur de cette structure `RectangleF`. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Obtient une valeur indiquant si la propriété [`Width`](./width/) ou [`Height`](./height/) de ce `RectangleF` a une valeur de zéro. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Obtient ou définit la coordonnée x du bord gauche de cette structure `RectangleF`. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `RectangleF`. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Obtient ou définit la coordonnée x qui est la somme de [`X`](./x/) et de [`Width`](./width/) de cette structure `RectangleF`. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Obtient ou définit la taille de ce `RectangleF`. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Obtient ou définit la coordonnée y du bord supérieur de cette structure `RectangleF`. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Obtient ou définit la largeur de cette structure `RectangleF`. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `RectangleF`. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `RectangleF`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Crée une structure `RectangleF` avec le coin supérieur gauche et le coin inférieur droit aux emplacements spécifiés. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Crée un nouveau [`Rectangle`](../rectangle/) à partir de deux points spécifiés. Deux sommets du [`Rectangle`](../rectangle/) créé seront égaux aux points *point1* et *point2* passés. Ce seront généralement les sommets opposés. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Crée et renvoie une copie gonflée de la structure `RectangleF` spécifiée. La copie est gonflée du montant spécifié. Le rectangle original reste inchangé. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Renvoie une structure `RectangleF` qui représente l'intersection de deux rectangles. S'il n'y a pas d'intersection, un `RectangleF` vide est renvoyé. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Crée le troisième rectangle le plus petit possible pouvant contenir les deux rectangles qui forment une union. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Détermine si le point spécifié est contenu dans cette structure `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Détermine si la région rectangulaire représentée par *rect* est entièrement contenue dans cette structure `RectangleF`. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Détermine si le point spécifié est contenu dans cette structure `RectangleF`. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Teste si *obj* est un `RectangleF` avec la même position et la même taille que ce `RectangleF`. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Obtient le code de hachage de cette structure `RectangleF`. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Gonfle ce `RectangleF` du montant spécifié. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Gonfle cette structure `RectangleF` du montant spécifié. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Remplace cette structure `RectangleF` par l'intersection d'elle-même et de la structure `RectangleF` spécifiée. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Détermine si ce rectangle intersecte *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Ajuste la position de ce rectangle du montant spécifié. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Ajuste la position de ce rectangle du montant spécifié. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Convertit les attributs de ce `RectangleF` en une chaîne lisible. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Implémente l'opérateur /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Teste si deux structures `RectangleF` ont la même position et la même taille. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Convertit la structure [`Rectangle`](../rectangle/) spécifiée en une structure `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Teste si deux structures `RectangleF` diffèrent de position ou de taille. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Implémente l'opérateur *. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


