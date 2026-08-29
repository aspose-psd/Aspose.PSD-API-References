---
title: "Classe RawColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor class. La classe Raw Color permet de stocker des couleurs avec n'importe quel nombre de canaux, n'importe quel mode couleur et n'importe quelle profondeur de bits. Veuillez noter que certaines classes internes peuvent rencontrer des problèmes lors de la conversion de RawColor vers son format natif, donc si l'API vous fournit une couleur CMYK, il est plus fiable d'utiliser le format fourni. Il peut également y avoir des cas où la couleur brute peut être convertie."
type: docs
weight: 1650
url: /fr/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

La classe Raw Color aide à stocker des couleurs avec n'importe quel nombre de canaux, n'importe quel mode couleur et n'importe quelle profondeur de bits. Veuillez noter que certaines classes internes peuvent rencontrer des problèmes lors de la conversion de RawColor vers son format natif, donc si l'API vous fournit une couleur CMYK, il est plus fiable d'utiliser le format fourni. De plus, il peut y avoir des cas où Raw Color peut être converti.

```csharp
public sealed class RawColor
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Initialise une nouvelle instance de la classe `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Initialise une nouvelle instance de la classe `RawColor` à partir du format de données de pixels en utilisant des modes de couleur prédéfinis |

## Propriétés

| Nom | Description |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Mode pour la couleur à suivre. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Obtient les composants de la couleur. Chaque composant est un canal séparé, et si vous utilisez un schéma de couleur peu répandu, il est préférable de travailler avec chaque canal séparément. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Détermine si l'objet spécifié est égal à cette instance. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Obtient la couleur sous forme d'entier si cela est possible. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Obtient la couleur sous forme de long si cela est possible. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Obtient la profondeur de bits de Raw Color. Par exemple, pour une couleur ARGB avec 8 bits par canal/composant, la profondeur est de 32 bits ; pour une couleur ARGB complète avec 16 bits par canal/composant, elle est de 64 bits. La profondeur de bits est accumulée à partir de la somme des profondeurs de bits des canaux. C'est possible si différents canaux ont des profondeurs de bits différentes. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Obtient le nom du mode couleur. Le nom du mode couleur est accumulé à partir des noms des canaux/composants. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Obtient le code de hachage de l'objet actuel. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Définit les données de tous les canaux à partir d'un argument entier si cela est possible. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Définit les données de tous les canaux à partir d'un argument entier si cela est possible. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implémente l'opérateur ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implémente l'opérateur !=. |

## Exemples

Le code suivant montre la prise en charge de la classe RawColor à la place de la structure Color obsolète.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


