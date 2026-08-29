---
title: "Classe Pen"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Pen. Définit un objet utilisé pour dessiner des lignes, des courbes et des figures."
type: docs
weight: 5690
url: /fr/net/aspose.psd/pen/
---
{{< psd/tize >}}
## Pen class

Définit un objet utilisé pour dessiner des lignes, des courbes et des figures.

```csharp
public class Pen : TransparencySupporter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initialise une nouvelle instance de la classe `Pen` avec le [`Brush`](./brush/) spécifié. |
| [Pen](pen/#constructor_2)(Color) | Initialise une nouvelle instance de la classe `Pen` avec la couleur spécifiée. |
| [Pen](pen/#constructor_1)(Brush, float) | Initialise une nouvelle instance de la classe `Pen` avec le [`Brush`](./brush/) et la [`Width`](./width/) spécifiés. |
| [Pen](pen/#constructor_3)(Color, float) | Initialise une nouvelle instance de la classe `Pen` avec les propriétés [`Color`](./color/) et [`Width`](./width/) spécifiées. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Obtient ou définit l’alignement de ce `Pen`. |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Obtient ou définit le [`Brush`](./brush/) qui détermine les attributs de ce `Pen`. |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Obtient ou définit la couleur de ce `Pen`. |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé trace une ligne composée de lignes parallèles et d’espaces. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Obtient ou définit un capuchon personnalisé à utiliser à l’extrémité des lignes dessinées avec ce `Pen`. |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Obtient ou définit une coiffe personnalisée à utiliser au début des lignes tracées avec ce `Pen`. |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Obtient ou définit le style de coiffe utilisé à la fin des tirets qui composent les lignes en pointillé tracées avec ce `Pen`. |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Obtient ou définit la distance du début d'une ligne jusqu'au commencement d'un motif de tirets. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Obtient ou définit le style utilisé pour les lignes en pointillé tracées avec ce `Pen`. |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Obtient ou définit le style de coiffe utilisé à la fin des lignes tracées avec ce `Pen`. |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives tracées avec ce `Pen`. |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Obtient ou définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que l'objet est entièrement visible, une valeur de 1 signifie que l'objet est entièrement opaque. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Obtient le style des lignes tracées avec ce `Pen`. |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Obtient ou définit le style de coiffe utilisé au début des lignes tracées avec ce `Pen`. |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Obtient ou définit une copie de la transformation géométrique pour ce `Pen`. |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Obtient ou définit la largeur de ce `Pen`, en unités de l'objet Graphics utilisé pour le dessin. |

## Méthodes

| Nom | Description |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplie la matrice de transformation de ce `Pen` par la [`Matrix`](../matrix/) spécifiée. |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la matrice de transformation de ce `Pen` par la [`Matrix`](../matrix/) spécifiée dans l'ordre indiqué. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Réinitialise la matrice de transformation géométrique de ce `Pen` à l'identité. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Fait pivoter la transformation géométrique locale de l'angle spécifié. Cette méthode préfixe la rotation à la transformation. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre indiqué. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode préfixe la matrice d'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre indiqué. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Définit les valeurs qui déterminent le style de coiffe utilisé pour terminer les lignes tracées par ce `Pen`. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Translater la transformation géométrique locale par les dimensions spécifiées. Cette méthode préfixe la translation à la transformation. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Translater la transformation géométrique locale par les dimensions spécifiées dans l'ordre indiqué. |

## Exemples

Cet exemple montre la création et l'utilisation d'objets Pen. L'exemple crée une nouvelle Image et dessine des Rectangles sur la surface de l'Image.

```csharp
[C#]

//Créez une instance d'Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créez une instance de Graphics et initialisez-la avec un objet Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacez la surface Graphics avec la couleur blanche
    graphics.Clear(Aspose.PSD.Color.White);

    //Créez une instance de Pen avec la couleur Rouge et une largeur de 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Créez une instance de HatchBrush et définissez ses propriétés
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Créez une instance de Pen
    //initialisez-la avec un objet HatchBrush et une largeur
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Dessinez des Rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Dessinez des Rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Créez des options d'exportation et initialisez-les.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Enregistrez toutes les modifications.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Voir aussi

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


