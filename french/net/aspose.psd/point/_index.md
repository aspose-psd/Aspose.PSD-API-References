---
title: "Structure Point"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.Point struct. Représente une paire ordonnée d'entiers x et y qui définit un point dans un plan bidimensionnel"
type: docs
weight: 5760
url: /fr/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan bidimensionnel.

```csharp
public struct Point
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Point](point/#constructor_1)(int) | Initialise une nouvelle instance de la structure `Point` en utilisant des coordonnées spécifiées par une valeur entière. |
| [Point](point/#constructor)(Size) | Initialise une nouvelle instance de la structure `Point` à partir de la structure [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | Initialise une nouvelle instance de la structure `Point` avec les coordonnées spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Obtient une nouvelle instance de la structure `Point` dont les valeurs [`X`](./x/) et [`Y`](./y/) sont définies à zéro. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Obtient une valeur indiquant si ce `Point` est vide. |
| [X](../../aspose.psd/point/x/) { get; set; } | Obtient ou définit la coordonnée x de ce `Point`. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Obtient ou définit la coordonnée y de ce `Point`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Ajoute le [`Size`](../size/) spécifié au `Point` spécifié. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Convertit le [`PointF`](../pointf/) spécifié en `Point` en arrondissant les valeurs du [`PointF`](../pointf/) à la valeur entière supérieure suivante. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Convertit le [`PointF`](../pointf/) spécifié en objet `Point` en arrondissant les valeurs du `Point` à l'entier le plus proche. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Renvoie le résultat de la soustraction du [`Size`](../size/) spécifié du `Point` spécifié. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Convertit le [`PointF`](../pointf/) spécifié en `Point` en tronquant les valeurs du `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Spécifie si ce `Point` contient les mêmes coordonnées que l'Objet spécifié. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Renvoie un code de hachage pour ce `Point`. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Déplace ce `Point` selon le `Point` spécifié. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Déplace ce `Point` du montant spécifié. |
| override [ToString](../../aspose.psd/point/tostring/)() | Convertit ce `Point` en une chaîne lisible par l'homme. |
| [operator +](../../aspose.psd/point/op_addition/) | Déplace un `Point` d'un [`Size`](../size/) donné. |
| [operator ==](../../aspose.psd/point/op_equality/) | Compare deux objets `Point`. Le résultat indique si les valeurs des propriétés [`X`](./x/) et [`Y`](./y/) des deux objets `Point` sont égales. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Convertit la structure `Point` spécifiée en une structure [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Convertit la structure `Point` spécifiée en la structure [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | Compare deux objets `Point`. Le résultat indique si les valeurs des propriétés [`X`](./x/) ou [`Y`](./y/) des deux objets `Point` sont différentes. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Translater un `Point` par le négatif d'un [`Size`](../size/) donné. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


