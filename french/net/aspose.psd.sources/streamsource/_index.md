---
title: "Classe StreamSource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Sources.StreamSource. Représente une source de flux"
type: docs
weight: 6120
url: /fr/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

Représente une source de flux.

```csharp
public sealed class StreamSource : Source
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Initialise une nouvelle instance de la classe `StreamSource`. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Initialise une nouvelle instance de la classe `StreamSource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Obtient une valeur indiquant si le flux doit être libéré chaque fois que le conteneur est libéré. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Obtient le flux. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Obtient le conteneur de flux. |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


