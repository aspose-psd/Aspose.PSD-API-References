---
title: "Classe SolidBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.SolidBrush. Le pinceau solide est destiné au dessin continu avec une couleur spécifique. Cette classe ne peut pas être héritée."
type: docs
weight: 200
url: /fr/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Le pinceau plein est destiné au dessin continu avec une couleur spécifique. Cette classe ne peut pas être héritée.

```csharp
public sealed class SolidBrush : Brush
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Initialise une nouvelle instance de la classe `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Initialise une nouvelle instance de la classe `SolidBrush`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Obtient ou définit la couleur du pinceau. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du [`Brush`](../../aspose.psd/brush/) actuel. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

## Exemples

Cet exemple utilise la classe Graphics pour créer des formes primitives sur la surface de l'Image. Pour démontrer l'opération, l'exemple crée une nouvelle Image au format PSD et dessine des formes primitives sur la surface de l'Image en utilisant les méthodes Draw exposées par la classe Graphics, puis l'exporte au format de fichier PSD.

```csharp
[C#]

//Créez une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Dessinez un arc en spécifiant l'objet Pen de couleur noire, 
    //un Rectangle entourant l'arc, l'angle de départ et l'angle de balayage
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Dessinez une courbe de Bézier en spécifiant l'objet Pen de couleur bleue et les points de coordonnées.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Dessinez une courbe en spécifiant l'objet Pen de couleur verte et un tableau de points
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Dessinez une ellipse en utilisant l'objet Pen et un rectangle entourant
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Dessinez une ligne 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Dessinez un segment de secteur
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Dessinez un polygone en spécifiant l'objet Pen de couleur rouge et un tableau de points
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Dessinez un rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Créez un objet SolidBrush et définissez ses différentes propriétés
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Dessinez une chaîne en utilisant l'objet SolidBrush et la police, à un point spécifique
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Créez une instance de PngOptions et définissez ses différentes propriétés
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // Enregistrez toutes les modifications.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Voir aussi

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


