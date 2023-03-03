---
title: Struct Size
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Size structure. Représente la taille.
type: docs
weight: 5550
url: /fr/net/aspose.psd/size/
---
## Size structure

Représente la taille.

```csharp
public struct Size
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Size](size/#constructor)(Point) | Initialise une nouvelle instance du`Size` structure du spécifié[`Point`](../point/) . |
| [Size](size/#constructor_1)(int, int) | Initialise une nouvelle instance du`Size` structure à partir des dimensions spécifiées. |

## Propriétés

| Nom | La description |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Obtient une nouvelle instance du`Size` structure qui a[`Width`](./width/) et[`Height`](./height/) valeurs mises à zéro. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Obtient ou définit la composante verticale de cette`Size` . |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Obtient une valeur indiquant si cela`Size` a une largeur et une hauteur de 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Obtient ou définit la composante horizontale de cette`Size` . |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Ajoute la largeur et la hauteur d'un`Size` structure à la largeur et à la hauteur d'une autre`Size`structure. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Convertit le spécifié[`SizeF`](../sizef/) structurer à un`Size` structure en arrondissant les valeurs des`Size` structure aux valeurs entières immédiatement supérieures. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Convertit le spécifié[`SizeF`](../sizef/) structurer à un`Size` structure en arrondissant les valeurs des[`SizeF`](../sizef/) structure aux valeurs entières les plus proches. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Soustrait la largeur et la hauteur d'un`Size` structure de la largeur et de la hauteur d'une autre`Size`structure. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Convertit le spécifié[`SizeF`](../sizef/) structurer à un`Size` structure en tronquant les valeurs des[`SizeF`](../sizef/) structure aux valeurs entières inférieures suivantes. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Teste pour voir si l'objet spécifié est un`Size` avec les mêmes dimensions que celui-ci`Size` . |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Renvoie un code de hachage pour cela`Size`structure. |
| override [ToString](../../aspose.psd/size/tostring/)() | Crée une chaîne lisible par l'homme qui représente ce`Size` . |
| [operator +](../../aspose.psd/size/op_addition/) | Ajoute la largeur et la hauteur d'un`Size` structure à la largeur et à la hauteur d'une autre`Size`structure. |
| [operator ==](../../aspose.psd/size/op_equality/) | Teste si deux`Size` les structures sont égales. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Convertit le spécifié`Size` à un[`Point`](../point/) . |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Convertit le spécifié`Size` à un[`SizeF`](../sizef/) . |
| [operator !=](../../aspose.psd/size/op_inequality/) | Teste si deux`Size` les structures sont différentes. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Soustrait la largeur et la hauteur d'un`Size` structure de la largeur et de la hauteur d'une autre`Size`structure. |

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


