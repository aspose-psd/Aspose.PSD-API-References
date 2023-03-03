---
title: Class Font
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Font classe. Définit un format particulier pour le texte y compris les attributs de police de taille et de style. Cette classe ne peut pas être héritée.
type: docs
weight: 4280
url: /fr/net/aspose.psd/font/
---
## Font class

Définit un format particulier pour le texte, y compris les attributs de police, de taille et de style. Cette classe ne peut pas être héritée.

```csharp
public sealed class Font
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initialise un nouveau`Font` qui utilise l'existant spécifié`Font` et[`FontStyle`](../fontstyle/) énumération. |
| [Font](font/#constructor_1)(string, float) | Initialise un nouveau`Font` en utilisant une taille spécifiée. Le jeu de caractères est défini surDefault , l'unité graphique àPoint , le style de police àRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initialise un nouveau`Font` en utilisant une taille et un style spécifiés. Le jeu de caractères est défini surDefault , l'unité graphique àPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initialise un nouveau`Font` en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini surDefault le style est défini surRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initialise un nouveau`Font` en utilisant une taille, un style et une unité spécifiés. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initialise un nouveau`Font` en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Obtient une valeur indiquant si cela`Font` est en gras. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Obtient une valeur d'octet qui spécifie le jeu de caractères que cette`Font` utilise. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Obtient une valeur indiquant si cela`Font`est en italique. |
| [Name](../../aspose.psd/font/name/) { get; } | Obtient le nom du visage de ce`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Obtient la taille em de ce`Font` mesurée dans les unités spécifiées par le[`Unit`](./unit/) propriété. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Obtient une valeur indiquant si cela`Font` spécifie une ligne horizontale à travers la police. |
| [Style](../../aspose.psd/font/style/) { get; } | Obtient les informations de style pour cela`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Obtient une valeur indiquant si cela`Font` est souligné. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Obtient l'unité de mesure pour ce`Font` . |

## Méthodes

| Nom | La description |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Crée une copie profonde exacte de ceci`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indique si l'objet spécifié est un`Font` et a les mêmes valeurs de propriété que celle-ci`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Obtient le code de hachage pour cela`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce`Font` . |

### Exemples

Cet exemple illustre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface de l'image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et GraphicsPath

```csharp
[C#]

// Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface graphique
    graphics.Clear(Color.Wheat);

    // Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Créer une instance de SolidBrush ayant la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée les options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // Enregistrer toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


