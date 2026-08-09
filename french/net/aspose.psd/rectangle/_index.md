---
title: "Structure Rectangle"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.Rectangle. Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle"
type: docs
weight: 5840
url: /fr/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Stocke un ensemble de quatre entiers qui représentent la position et la taille d’un rectangle.

```csharp
public struct Rectangle
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Initialise une nouvelle instance de la structure `Rectangle` avec la position et la taille spécifiées. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Initialise une nouvelle instance de la structure `Rectangle` avec la position et la taille spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Obtient une nouvelle instance de la structure `Rectangle` dont les valeurs [`X`](./x/), [`Y`](./y/), [`Width`](./width/) et [`Height`](./height/) sont définies à zéro. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Obtient ou définit la coordonnée y qui est la somme des valeurs des propriétés [`Y`](./y/) et [`Height`](./height/) de cette structure `Rectangle`. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Obtient ou définit la hauteur de cette structure `Rectangle`. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Obtient une valeur indiquant si toutes les propriétés numériques de ce `Rectangle` ont des valeurs égales à zéro. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Obtient ou définit la coordonnée x du bord gauche de cette structure `Rectangle`. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Obtient ou définit les coordonnées du coin supérieur gauche de cette structure `Rectangle`. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Obtient ou définit la coordonnée x qui est la somme des valeurs des propriétés [`X`](./x/) et [`Width`](./width/) de cette structure `Rectangle`. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Obtient ou définit la taille de ce `Rectangle`. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Obtient ou définit la coordonnée y du bord supérieur de cette structure `Rectangle`. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Obtient ou définit la largeur de cette structure `Rectangle`. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de cette structure `Rectangle`. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de cette structure `Rectangle`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Convertit la structure [`RectangleF`](../rectanglef/) spécifiée en une structure `Rectangle` en arrondissant les valeurs de [`RectangleF`](../rectanglef/) au prochain entier supérieur. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Crée une structure `Rectangle` avec les emplacements de bord spécifiés. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Crée un nouveau `Rectangle` à partir de deux points spécifiés. Les deux côtés verticaux du `Rectangle` créé seront égaux aux points *point1* et *point2* transmis. Ceux-ci sont généralement les sommets opposés. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Crée et renvoie une copie gonflée de la structure `Rectangle` spécifiée. La copie est gonflée du montant spécifié. La structure `Rectangle` originale reste inchangée. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Renvoie une troisième structure `Rectangle` qui représente l'intersection de deux autres structures `Rectangle`. S'il n'y a pas d'intersection, un `Rectangle` vide est renvoyé. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Convertit le [`RectangleF`](../rectanglef/) spécifié en un `Rectangle` en arrondissant les valeurs du [`RectangleF`](../rectanglef/) aux entiers les plus proches. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Convertit le [`RectangleF`](../rectanglef/) spécifié en un `Rectangle` en tronquant les valeurs du [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Obtient une structure `Rectangle` qui contient l'union de deux structures `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Détermine si le point spécifié est contenu dans cette structure `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Détermine si la région rectangulaire représentée par *rect* est entièrement contenue dans cette structure `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Détermine si le point spécifié est contenu dans cette structure `Rectangle`. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Teste si *obj* est une structure `Rectangle` avec la même position et la même taille que cette structure `Rectangle`. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Renvoie le code de hachage de cette structure `Rectangle`. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Gonfle ce `Rectangle` du montant spécifié. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Gonfle ce `Rectangle` du montant spécifié. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Remplace ce `Rectangle` par l'intersection de lui-même et du `Rectangle` spécifié. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Détermine si ce rectangle intersecte *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Normalise le rectangle en rendant sa largeur et sa hauteur positives, le côté gauche inférieur au côté droit et le haut inférieur au bas. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Ajuste la position de ce rectangle du montant spécifié. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Ajuste la position de ce rectangle du montant spécifié. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Convertit les attributs de ce `Rectangle` en une chaîne lisible par l'homme. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Teste si deux structures `Rectangle` ont la même position et la même taille. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Teste si deux structures `Rectangle` diffèrent par la position ou la taille. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


