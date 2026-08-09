---
title: "Structure SizeF"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.SizeF. Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle"
type: docs
weight: 6060
url: /fr/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle.

```csharp
public struct SizeF
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Initialise une nouvelle instance de la structure `SizeF` à partir du [`PointF`](../pointf/) spécifié. |
| [SizeF](sizef/#constructor_1)(SizeF) | Initialise une nouvelle instance de la structure `SizeF` à partir du `SizeF` spécifié. |
| [SizeF](sizef/#constructor_2)(float, float) | Initialise une nouvelle instance de la structure `SizeF` à partir des dimensions spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Obtient une nouvelle instance de la structure `SizeF` dont les valeurs [`Width`](./width/) et [`Height`](./height/) sont définies à zéro. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Obtient ou définit le composant vertical de ce `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Obtient une valeur indiquant si ce `SizeF` a une largeur et une hauteur nulles. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Obtient ou définit le composant horizontal de ce `SizeF`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Ajoute la largeur et la hauteur d’une structure `SizeF` à la largeur et à la hauteur d’une autre structure `SizeF`. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Soustrait la largeur et la hauteur d’une structure `SizeF` de la largeur et de la hauteur d’une autre structure `SizeF`. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Teste si l’objet spécifié est un `SizeF` avec les mêmes dimensions que ce `SizeF`. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Renvoie un code de hachage pour cette structure [`Size`](../size/). |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Convertit un `SizeF` en [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Convertit un `SizeF` en une structure [`Size`](../size/) avec des valeurs de taille tronquées. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Crée une chaîne lisible par l’homme qui représente ce `SizeF`. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Ajoute la largeur et la hauteur d’une structure `SizeF` à la largeur et à la hauteur d’une autre structure `SizeF`. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Teste si deux structures `SizeF` sont égales. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Convertit le `SizeF` spécifié en [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Teste si deux structures `SizeF` sont différentes. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Soustrait la largeur et la hauteur d’une structure `SizeF` de la largeur et de la hauteur d’une autre structure `SizeF`. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


