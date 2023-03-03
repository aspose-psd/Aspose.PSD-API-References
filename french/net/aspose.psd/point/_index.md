---
title: Struct Point
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Point structure. Représente une paire ordonnée de coordonnées x et y entières qui définissent un point dans un plan bidimensionnel.
type: docs
weight: 5260
url: /fr/net/aspose.psd/point/
---
## Point structure

Représente une paire ordonnée de coordonnées x et y entières qui définissent un point dans un plan bidimensionnel.

```csharp
public struct Point
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initialise une nouvelle instance du`Point` structure utilisant des coordonnées spécifiées par une valeur entière. |
| [Point](point/#constructor)(Size) | Initialise une nouvelle instance du`Point` structure de la[`Size`](../size/)structure. |
| [Point](point/#constructor_2)(int, int) | Initialise une nouvelle instance du`Point` structure avec les coordonnées spécifiées. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Obtient une nouvelle instance du`Point` structure qui a[`X`](./x/) et[`Y`](./y/) valeurs mises à zéro. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Obtient une valeur indiquant si cela`Point` est vide. |
| [X](../../aspose.psd/point/x/) { get; set; } | Obtient ou définit la coordonnée x de ce`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Obtient ou définit la coordonnée y de ce`Point` . |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Ajoute le spécifié[`Size`](../size/) au spécifié`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Convertit le spécifié[`PointF`](../pointf/) à un`Point` en arrondissant les valeurs de[`PointF`](../pointf/) aux valeurs entières supérieures suivantes. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Convertit le spécifié[`PointF`](../pointf/) à un`Point` objet en arrondissant le`Point` valeurs à l'entier le plus proche. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Renvoie le résultat de la soustraction spécifiée[`Size`](../size/) à partir du spécifié`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Convertit le spécifié[`PointF`](../pointf/) à un`Point` en tronquant les valeurs des`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Spécifie si cela`Point` contient les mêmes coordonnées que le spécifiéObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Renvoie un code de hachage pour cela`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Traduit ceci`Point` par le spécifié`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Traduit ceci`Point`par le montant spécifié. |
| override [ToString](../../aspose.psd/point/tostring/)() | Convertit ceci`Point` en une chaîne lisible par l'homme. |
| [operator +](../../aspose.psd/point/op_addition/) | Traduit un`Point` par un donné[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Compare deux`Point` objets. Le résultat indique si les valeurs des[`X`](./x/) et[`Y`](./y/) propriétés des deux`Point` les objets sont égaux. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Convertit le spécifié`Point` structurer à un[`Size`](../size/)structure. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Convertit le spécifié`Point` structuré à la[`PointF`](../pointf/)structure. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Compare deux`Point` objets. Le résultat indique si les valeurs des[`X`](./x/) ou[`Y`](./y/) propriétés des deux`Point` les objets sont inégaux. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Traduit un`Point` par le négatif d'une donnée[`Size`](../size/) . |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


