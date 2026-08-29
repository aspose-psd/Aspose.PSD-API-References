---
title: "Structure Size"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Structure Aspose.PSD.Size. Représente la taille"
type: docs
weight: 6050
url: /fr/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Représente la taille.

```csharp
public struct Size
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Size](size/#constructor)(Point) | Initialise une nouvelle instance de la structure `Size` à partir du [`Point`](../point/) spécifié. |
| [Size](size/#constructor_1)(int, int) | Initialise une nouvelle instance de la structure `Size` à partir des dimensions spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Obtient une nouvelle instance de la structure `Size` dont les valeurs [`Width`](./width/) et [`Height`](./height/) sont définies à zéro. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Obtient ou définit le composant vertical de ce `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Obtient une valeur indiquant si ce `Size` a une largeur et une hauteur de 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Obtient ou définit le composant horizontal de ce `Size`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Ajoute la largeur et la hauteur d'une structure `Size` à la largeur et la hauteur d'une autre structure `Size`. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Convertit la structure [`SizeF`](../sizef/) spécifiée en une structure `Size` en arrondissant les valeurs de la structure `Size` à l'entier supérieur le plus proche. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Convertit la structure [`SizeF`](../sizef/) spécifiée en une structure `Size` en arrondissant les valeurs de la structure [`SizeF`](../sizef/) à l'entier le plus proche. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Soustrait la largeur et la hauteur d'une structure `Size` de la largeur et la hauteur d'une autre structure `Size`. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Convertit la structure [`SizeF`](../sizef/) spécifiée en une structure `Size` en tronquant les valeurs de la structure [`SizeF`](../sizef/) à l'entier inférieur suivant. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Teste si l'objet spécifié est un `Size` avec les mêmes dimensions que ce `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Renvoie un code de hachage pour cette structure `Size`. |
| override [ToString](../../aspose.psd/size/tostring/)() | Crée une chaîne lisible par l'homme qui représente ce `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | Ajoute la largeur et la hauteur d'une structure `Size` à la largeur et la hauteur d'une autre structure `Size`. |
| [operator ==](../../aspose.psd/size/op_equality/) | Teste si deux structures `Size` sont égales. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Convertit le `Size` spécifié en un [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Convertit le `Size` spécifié en un [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Teste si deux structures `Size` sont différentes. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Soustrait la largeur et la hauteur d'une structure `Size` de la largeur et la hauteur d'une autre structure `Size`. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


