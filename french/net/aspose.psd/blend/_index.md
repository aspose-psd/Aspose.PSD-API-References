---
title: Class Blend
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Blend classe. Définit un motif de fusion. Cette classe ne peut pas être héritée.
type: docs
weight: 110
url: /fr/net/aspose.psd/blend/
---
## Blend class

Définit un motif de fusion. Cette classe ne peut pas être héritée.

```csharp
public sealed class Blend
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Blend](blend/#constructor)() | Initialise une nouvelle instance du`Blend` classe. Le nombre d'éléments dans les tableaux factor et blend sera égal à 1. |
| [Blend](blend/#constructor_1)(int) | Initialise une nouvelle instance du`Blend` classe avec le nombre spécifié de facteurs et de positions. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Obtient ou définit le tableau des facteurs de fusion pour le dégradé. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Obtient ou définit le tableau des positions de fusion pour le dégradé. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Teste si l'objet spécifié est un`Blend` classe et équivaut à ceci`Blend` classe. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Renvoie un code de hachage pour cette instance. |

### Remarques

L'utilisation typique de la classe de mélange consiste à définir un motif de mélange pour le pinceau. Et donc les propriétés de mélange doivent être initialisées avec soin. Les tableaux nuls ne sont pas autorisés. Le pinceau lèvera l'exception appropriée si les facteurs de fusion ou le tableau de positions sont vides ou si leur longueur n'est pas la même. S'il y a deux éléments ou plus dans le tableau de positions, le premier élément doit être 0 et le dernier doit être 1.

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


