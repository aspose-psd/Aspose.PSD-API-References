---
title: "Classe Font"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Font. Définit un format particulier pour le texte incluant la taille et les attributs de style de la police. Cette classe ne peut pas être héritée."
type: docs
weight: 4750
url: /fr/net/aspose.psd/font/
---
{{< psd/tize >}}
## Font class

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée.

```csharp
public sealed class Font
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Initialise un nouveau `Font` qui utilise le `Font` existant spécifié et l'énumération [`FontStyle`](../fontstyle/). |
| [Font](font/#constructor_1)(string, float) | Initialise un nouveau `Font` en utilisant une taille spécifiée. Le jeu de caractères est défini sur Default, l'unité graphique sur Point, le style de police sur Regular. |
| [Font](font/#constructor_2)(string, float, FontStyle) | Initialise un nouveau `Font` en utilisant une taille et un style spécifiés. Le jeu de caractères est défini sur Default, l'unité graphique sur Point. |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Initialise un nouveau `Font` en utilisant une taille et une unité spécifiées. Le jeu de caractères est défini sur Default, le style est défini sur Regular. |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Initialise un nouveau `Font` en utilisant une taille, un style et une unité spécifiés. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Initialise un nouveau `Font` en utilisant une taille, un style, une unité et un jeu de caractères spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Obtient une valeur indiquant si ce `Font` est en gras. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Obtient une valeur byte qui spécifie le jeu de caractères utilisé par ce `Font`. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Obtient une valeur indiquant si ce `Font` est en italique. |
| [Name](../../aspose.psd/font/name/) { get; } | Obtient le nom de la police de ce `Font`. |
| [Size](../../aspose.psd/font/size/) { get; } | Obtient la taille en em de ce `Font` mesurée dans les unités spécifiées par la propriété [`Unit`](./unit/). |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Obtient une valeur indiquant si ce `Font` spécifie une ligne horizontale traversant la police. |
| [Style](../../aspose.psd/font/style/) { get; } | Obtient les informations de style pour ce `Font`. |
| [Underline](../../aspose.psd/font/underline/) { get; } | Obtient une valeur indiquant si ce `Font` est souligné. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Obtient l'unité de mesure de ce `Font`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Crée une copie profonde exacte de ce `Font`. |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indique si l'objet spécifié est un `Font` et possède les mêmes valeurs de propriétés que ce `Font`. |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Obtient le code de hachage de ce `Font`. |
| override [ToString](../../aspose.psd/font/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `Font`. |

## Exemples

Cet exemple montre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface Image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et de GraphicsPath

```csharp
[C#]

//Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics
    graphics.Clear(Color.Wheat);

    //Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crée une instance de SolidBrush avec la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée des options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // enregistrez toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


