---
title: "Classe StringFormat"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.StringFormat. Encapsule les informations de mise en page du texte telles que l'orientation d'alignement et les arrêts de tabulation, les manipulations d'affichage comme l'insertion d'ellipse, la substitution de chiffres nationaux et les fonctionnalités OpenType. Cette classe ne peut pas être héritée"
type: docs
weight: 6170
url: /fr/net/aspose.psd/stringformat/
---
{{< psd/tize >}}
## StringFormat class

Encapsule les informations de mise en page du texte (telles que l’alignement, l’orientation et les tabulations), les manipulations d’affichage (telles que l’insertion d’ellipse et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée.

```csharp
public sealed class StringFormat : DisposableObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Initialise un nouvel objet `StringFormat`. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Initialise un nouvel objet `StringFormat` à partir de l'objet `StringFormat` existant spécifié. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Initialise un nouvel objet `StringFormat` avec l'énumération [`StringFormatFlags`](../stringformatflags/) et la langue spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Obtient un objet `StringFormat` générique par défaut. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Obtient un objet `StringFormat` typographique générique. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Obtient ou définit les informations d'alignement du texte sur le plan vertical. |
| [CustomCharIdent](../../aspose.psd/stringformat/customcharident/) { get; set; } | Obtient ou définit l'identifiant de caractère personnalisé. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Obtient ou définit la langue utilisée lorsque les chiffres locaux sont substitués aux chiffres occidentaux. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Obtient ou définit la méthode à utiliser pour la substitution des chiffres. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Obtient le nombre d'espaces entre le début d'une ligne de texte et le premier arrêt de tabulation. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Obtient ou définit une énumération [`StringFormatFlags`](../stringformatflags/) qui contient les informations de formatage. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Obtient ou définit l'objet [`HotkeyPrefix`](../hotkeyprefix/) pour cet objet `StringFormat`. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Obtient ou définit l'alignement de ligne sur le plan horizontal. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Obtient un tableau de distances entre les arrêts de tabulation dans les unités spécifiées par la propriété [`PageUnit`](../graphics/pageunit/). |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Obtient ou définit l'énumération [`StringTrimming`](../stringtrimming/) pour cet objet `StringFormat`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Crée un clone profond de cet objet `StringFormat`. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| override [Equals](../../aspose.psd/stringformat/equals/)(object) | Vérifie si les objets sont égaux. |
| override [GetHashCode](../../aspose.psd/stringformat/gethashcode/)() | Obtient le code de hachage de l'objet actuel. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Définit les arrêts de tabulation pour cet objet `StringFormat`. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Convertit cet objet `StringFormat` en une chaîne lisible par l'homme. |

### Voir aussi

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


