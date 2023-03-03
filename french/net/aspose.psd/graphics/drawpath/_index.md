---
title: Graphics.DrawPath
second_title: Référence de l'API Aspose.PSD pour .NET
description: Graphics méthode. dessine unGraphicsPath .
type: docs
weight: 270
url: /fr/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

dessine un[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style du chemin. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) dessiner. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *path* est nul. |

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

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)


