---
title: "Figure.AddShape"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Figure. Ajoute une forme à la figure"
type: docs
weight: 60
url: /fr/net/aspose.psd/figure/addshape/
---
{{< psd/tize >}}
## Figure.AddShape method

Ajoute une forme à la figure.

```csharp
public void AddShape(Shape shape)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| forme | Forme | La forme à ajouter. |

## Exemples

Ces exemples utilisent les classes GraphicsPath et Graphics pour créer et manipuler des Figures sur une surface Image. L'exemple crée une nouvelle Image et trace des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour rendre les chemins sur la surface. Enfin, l'image est exportée au format de fichier Tiff.

```csharp
[C#]

//Créez une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez et initialisez une instance de la classe Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics.
    graphics.Clear(Color.Wheat);

    //Créez une instance de la classe GraphicsPath.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créez une instance de la classe Figure.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Ajoutez des formes à l'objet Figure.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Ajoutez l'objet Figure à GraphicsPath.
    graphicspath.AddFigure(figure);

    //Dessinez le chemin avec l'objet Pen de couleur Noir.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Créez une instance de TiffOptions et définissez ses différentes propriétés.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Enregistrez toutes les modifications.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Voir aussi

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


