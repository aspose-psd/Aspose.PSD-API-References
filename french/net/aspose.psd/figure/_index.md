---
title: "Classe Figure"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.Figure class. La figure. Un conteneur pour les formes"
type: docs
weight: 1210
url: /fr/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

La figure. Un conteneur pour les formes.

```csharp
public class Figure : ObjectWithBounds
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Figure](figure/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Obtient ou définit les limites de l'objet. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si cette figure est fermée. Une figure fermée ne fera une différence que dans le cas où les formes de la première et de la dernière figure sont continues. Dans ce cas, le premier point de la première forme sera relié par une ligne droite au dernier point de la dernière forme. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Obtient les segments complets de la figure. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Obtient les formes de la figure. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Ajoute une forme à la figure. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Ajoute une série de formes à la figure. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Supprime une forme de la figure. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Supprime une série de formes de la figure. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Inverse l'ordre des formes de cette figure ainsi que l'ordre des points des formes. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


