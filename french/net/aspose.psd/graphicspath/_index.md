---
title: "Classe GraphicsPath"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.GraphicsPath. Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée"
type: docs
weight: 4790
url: /fr/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initialise une nouvelle instance de la classe `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initialise une nouvelle instance de la classe `GraphicsPath`. |

## Propriétés

| Nom | Description |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Obtient ou définit les limites de l'objet. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Obtient les figures du chemin. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Obtient ou définit une énumération [`FillMode`](../fillmode/) qui détermine comment les intérieurs des formes de ce `GraphicsPath` sont remplis. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Ajoute une nouvelle figure. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Ajoute de nouvelles figures. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Ajoute le `GraphicsPath` spécifié à ce chemin. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Ajoute le `GraphicsPath` spécifié à ce chemin. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Effectue un clonage profond de ce chemin graphique. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Applique la transformation spécifiée, puis convertit chaque courbe de ce `GraphicsPath` en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Convertit chaque courbe de ce `GraphicsPath` en une séquence de segments de ligne connectés. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié et en utilisant le [`Graphics`](../graphics/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié et en utilisant le [`Graphics`](../graphics/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié et en utilisant le [`Graphics`](../graphics/) spécifié. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indique si le point spécifié est contenu à l'intérieur (ou sous) du contour de ce `GraphicsPath` lorsqu'il est dessiné avec le [`Pen`](../pen/) spécifié et en utilisant le [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indique si le point spécifié est contenu dans ce `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indique si le point spécifié est contenu dans ce `GraphicsPath` dans la région de découpe visible du [`Graphics`](../graphics/) spécifié. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indique si le point spécifié est contenu dans ce `GraphicsPath`, en utilisant le [`Graphics`](../graphics/) spécifié. |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Supprime une figure. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Supprime des figures. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Vide le chemin graphique et définit le [`FillMode`](../fillmode/) sur Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Inverse l'ordre des figures, formes et points dans chaque forme de ce `GraphicsPath`. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applique une transformation de déformation, définie par un rectangle et un parallélogramme, à ce `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Ajoute un contour supplémentaire au chemin. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Ajoute un contour supplémentaire au `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Remplace ce `GraphicsPath` par des courbes qui entourent la zone remplie lorsque ce chemin est dessiné avec le pen spécifié. |

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


