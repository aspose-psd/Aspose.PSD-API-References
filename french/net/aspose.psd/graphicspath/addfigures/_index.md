---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode GraphicsPath. Ajoute de nouvelles figures"
type: docs
weight: 60
url: /fr/net/aspose.psd/graphicspath/addfigures/
---
{{< psd/tize >}}
## GraphicsPath.AddFigures method

Ajoute de nouvelles figures.

```csharp
public void AddFigures(Figure[] figures)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| figures | Figure[] | Les figures à ajouter. |

## Exemples

Cet exemple crée une nouvelle Image et dessine une variété de formes en utilisant Figures et GraphicsPath sur la surface de l'Image

```csharp
[C#]

//Créez une instance d'Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Créez une instance de la classe GraphicsPath.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Ajouter une forme à l'objet Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Ajouter une forme à l'objet Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Ajoutez l'objet Figure à GraphicsPath.
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Dessinez le chemin avec l'objet Pen de couleur Noir.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Créez des options d'exportation et initialisez-les.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // Enregistrez toutes les modifications.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Voir aussi

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


