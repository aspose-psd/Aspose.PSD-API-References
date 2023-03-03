---
title: Class SolidBrush
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Brushes.SolidBrush classe. Le pinceau solide est destiné à dessiner en continu avec une couleur spécifique. Cette classe ne peut pas être héritée.
type: docs
weight: 200
url: /fr/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

Le pinceau solide est destiné à dessiner en continu avec une couleur spécifique. Cette classe ne peut pas être héritée.

```csharp
public sealed class SolidBrush : Brush
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Initialise une nouvelle instance du`SolidBrush` classe. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Initialise une nouvelle instance du`SolidBrush` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Obtient ou définit la couleur du pinceau. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que le pinceau est entièrement visible, la valeur 1 signifie que le pinceau est entièrement opaque. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du courant[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |

### Exemples

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface Image. Pour illustrer l'opération, l'exemple crée une nouvelle image au format PSD et dessine des formes primitives sur la surface de l'image à l'aide des méthodes Draw exposées par la classe Graphics, puis l'exporte au format de fichier PSD.

```csharp
[C#]

//Créer une instance de Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créer et initialiser une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacer la surface graphique
    graphics.Clear(Color.Wheat);

    // Dessine un arc en spécifiant l'objet Pen de couleur noire, 
    //un rectangle entourant l'arc, l'angle de départ et l'angle de balayage
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    // Dessinez un Bézier en spécifiant l'objet Pen ayant la couleur bleue et les points de coordonnées.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    // Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    // Dessine une ellipse à l'aide de l'objet Pen et d'un rectangle environnant
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Tracer une ligne 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    // Dessine un segment de tarte
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    // Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    // Dessine un rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Créer un objet SolidBrush et définir ses différentes propriétés
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    // Dessine une chaîne à l'aide de l'objet SolidBrush et de la police, à un point spécifique
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Créer une instance de PngOptions et définir ses différentes propriétés
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Enregistrer toutes les modifications.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Voir également

* class [Brush](../../aspose.psd/brush/)
* espace de noms [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* Assemblée [Aspose.PSD](../../)


