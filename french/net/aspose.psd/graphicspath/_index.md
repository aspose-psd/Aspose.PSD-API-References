---
title: Class GraphicsPath
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.GraphicsPath classe. Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.
type: docs
weight: 4320
url: /fr/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Initialise une nouvelle instance du`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Initialise une nouvelle instance du`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Initialise une nouvelle instance du`GraphicsPath` classe. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Initialise une nouvelle instance du`GraphicsPath` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Obtient ou définit les limites de l'objet. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Obtient les chiffres du chemin. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Obtient ou définit un[`FillMode`](../fillmode/) énumération qui détermine comment les intérieurs des formes dans ce`GraphicsPath` sont remplis. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Ajoute une nouvelle figure. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Ajoute de nouveaux chiffres. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Ajoute le spécifié`GraphicsPath` à ce chemin. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Ajoute le spécifié`GraphicsPath` à ce chemin. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Effectue un clone en profondeur de ce chemin graphique. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Convertit chaque courbe de ce chemin en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Applique la transformation spécifiée, puis convertit chaque courbe dans cette`GraphicsPath` en une séquence de segments de ligne connectés. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Convertit chaque courbe dans ce`GraphicsPath` en une séquence de segments de ligne connectés. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Obtient les limites de l'objet. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Obtient les limites de l'objet. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) et en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) et en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) et en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Indique si le point spécifié est contenu dans (sous) le contour de ce`GraphicsPath` lorsqu'il est dessiné avec le spécifié[`Pen`](../pen/) et en utilisant le spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Indique si le point spécifié est contenu dans ce`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Indique si le point spécifié est contenu dans ce`GraphicsPath` dans la zone de clip visible du fichier spécifié[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Indique si le point spécifié est contenu dans ce`GraphicsPath` , en utilisant le spécifié[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Supprime une figure. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Supprime les chiffres. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Vide le chemin graphique et définit le[`FillMode`](../fillmode/) pourAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Inverse l'ordre des chiffres, des formes et des points dans chaque forme de ce`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Applique la transformation spécifiée à la forme. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Applique une transformation warp, définie par un rectangle et un parallélogramme, à cette`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Ajoute un contour supplémentaire au chemin. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Ajoute un contour supplémentaire au`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Remplace ceci`GraphicsPath` avec des courbes qui entourent la zone qui est remplie lorsque ce chemin est dessiné par le stylo spécifié. |

### Exemples

Ces exemples utilisent GraphicsPath et la classe Graphics pour créer et manipuler des figures sur une surface Image. L'exemple crée une nouvelle image et dessine des chemins à l'aide de la classe GraphicsPath. À la fin, la méthode DrawPath exposée par la classe Graphics est appelée pour restituer les chemins sur la surface. Enfin, l'image est exportée au format de fichier Tiff.

```csharp
[C#]

//Créer une instance de Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créer et initialiser une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacer la surface graphique
    graphics.Clear(Color.Wheat);

    //Créer une instance de la classe GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Créer une instance de la classe Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Ajouter des formes à l'objet Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Ajouter un objet Figure à GraphicsPath
    graphicspath.AddFigure(figure);

    // Dessine un chemin avec un objet Pen de couleur noire
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Créer une instance de TiffOptions et définir ses différentes propriétés
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Enregistrer toutes les modifications.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Voir également

* class [ObjectWithBounds](../objectwithbounds/)
* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


