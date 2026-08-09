---
title: "Classe Blend"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Blend. Définit un motif de fusion. Cette classe ne peut pas être héritée"
type: docs
weight: 110
url: /fr/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Définit un motif de mélange. Cette classe ne peut pas être héritée.

```csharp
public sealed class Blend
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Blend](blend/#constructor)() | Initialise une nouvelle instance de la classe `Blend`. Le nombre d'éléments dans les tableaux des facteurs et des fusions sera égal à 1. |
| [Blend](blend/#constructor_1)(int) | Initialise une nouvelle instance de la classe `Blend` avec le nombre spécifié de facteurs et de positions. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Obtient ou définit le tableau des facteurs de fusion pour le dégradé. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Obtient ou définit le tableau des positions de fusion pour le dégradé. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Teste si l'objet spécifié est une classe `Blend` et est équivalente à cette classe `Blend`. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Renvoie un code de hachage pour cette instance. |

## Remarques

L'utilisation typique de la classe de fusion consiste à définir un motif de fusion pour le pinceau. Ainsi, les propriétés de fusion doivent être initialisées avec soin. Les tableaux null ne sont pas autorisés. Le pinceau lèvera l'exception appropriée si les tableaux des facteurs de fusion ou des positions sont vides ou si leur longueur n'est pas identique. S'il y a deux éléments ou plus dans le tableau des positions, le premier élément doit être 0 et le dernier doit être 1.

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


