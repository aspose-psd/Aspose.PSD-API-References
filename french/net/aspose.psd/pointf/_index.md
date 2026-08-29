---
title: "Structure PointF"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.PointF. Représente une paire ordonnée de x et y en virgule flottante qui définit un point dans un plan bidimensionnel."
type: docs
weight: 5770
url: /fr/net/aspose.psd/pointf/
---
{{< psd/tize >}}
## PointF structure

Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan bidimensionnel.

```csharp
public struct PointF
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PointF](pointf/)(float, float) | Initialise une nouvelle instance de la structure `PointF` avec les coordonnées spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/pointf/empty/) { get; } | Obtient une nouvelle instance de la structure `PointF` dont les valeurs [`X`](./x/) et [`Y`](./y/) sont définies à zéro. |
| [IsEmpty](../../aspose.psd/pointf/isempty/) { get; } | Obtient une valeur indiquant si ce `PointF` est vide. |
| [X](../../aspose.psd/pointf/x/) { get; set; } | Obtient ou définit la coordonnée x de ce `PointF`. |
| [Y](../../aspose.psd/pointf/y/) { get; set; } | Obtient ou définit la coordonnée y de ce `PointF`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Add](../../aspose.psd/pointf/add/#add)(PointF, Size) | Déplace le `PointF` donné de la [`Size`](../size/) spécifiée. |
| static [Add](../../aspose.psd/pointf/add/#add_1)(PointF, SizeF) | Déplace le `PointF` donné de la [`SizeF`](../sizef/) spécifiée. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract)(PointF, Size) | Déplace le `PointF` du négatif d'une taille spécifiée. |
| static [Subtract](../../aspose.psd/pointf/subtract/#subtract_1)(PointF, SizeF) | Déplace le `PointF` du négatif d'une taille spécifiée. |
| override [Equals](../../aspose.psd/pointf/equals/)(object) | Spécifie si ce `PointF` contient les mêmes coordonnées que l'objet spécifié. |
| override [GetHashCode](../../aspose.psd/pointf/gethashcode/)() | Renvoie un code de hachage pour cette structure `PointF`. |
| override [ToString](../../aspose.psd/pointf/tostring/)() | Convertit ce `PointF` en une chaîne lisible par l'homme. |
| [operator +](../../aspose.psd/pointf/op_addition/#op_addition) | Déplace le `PointF` d'une [`Size`](../size/) donnée. (2 opérateurs) |
| [operator ==](../../aspose.psd/pointf/op_equality/) | Compare deux structures `PointF`. Le résultat spécifie si les valeurs des propriétés [`X`](./x/) et [`Y`](./y/) des deux structures `PointF` sont égales. |
| [operator !=](../../aspose.psd/pointf/op_inequality/) | Détermine si les coordonnées des points spécifiés ne sont pas égales. |
| [operator -](../../aspose.psd/pointf/op_subtraction/#op_subtraction) | Déplace le `PointF` du négatif d'une [`Size`](../size/) donnée. (2 opérateurs) |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


