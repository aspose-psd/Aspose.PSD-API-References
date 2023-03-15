---
title: Class Pen
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Pen classe. Définit un objet utilisé pour dessiner des lignes des courbes et des figures.
type: docs
weight: 5200
url: /fr/net/aspose.psd/pen/
---
## Pen class

Définit un objet utilisé pour dessiner des lignes, des courbes et des figures.

```csharp
public class Pen : TransparencySupporter
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | Initialise une nouvelle instance du`Pen` classe avec le spécifié[`Brush`](./brush/) . |
| [Pen](pen/#constructor_2)(Color) | Initialise une nouvelle instance du`Pen` classe avec la couleur spécifiée. |
| [Pen](pen/#constructor_1)(Brush, float) | Initialise une nouvelle instance du`Pen` classe avec le spécifié[`Brush`](./brush/) et[`Width`](./width/) . |
| [Pen](pen/#constructor_3)(Color, float) | Initialise une nouvelle instance du`Pen` classe avec le spécifié[`Color`](./color/) et[`Width`](./width/) propriétés. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Alignment](../../aspose.psd/pen/alignment/) { get; set; } | Obtient ou définit l'alignement pour ce`Pen` . |
| [Brush](../../aspose.psd/pen/brush/) { get; set; } | Obtient ou définit le[`Brush`](./brush/) qui détermine les attributs de ce`Pen` . |
| [Color](../../aspose.psd/pen/color/) { get; set; } | Obtient ou définit la couleur de ce`Pen` . |
| [CompoundArray](../../aspose.psd/pen/compoundarray/) { get; set; } | Obtient ou définit un tableau de valeurs qui spécifie un stylo composé. Un stylo composé dessine une ligne composée composée de lignes parallèles et d'espaces. |
| [CustomEndCap](../../aspose.psd/pen/customendcap/) { get; set; } | Obtient ou définit une limite personnalisée à utiliser à la fin des lignes dessinées avec ce`Pen` . |
| [CustomStartCap](../../aspose.psd/pen/customstartcap/) { get; set; } | Obtient ou définit une limite personnalisée à utiliser au début des lignes dessinées avec ce`Pen` . |
| [DashCap](../../aspose.psd/pen/dashcap/) { get; set; } | Obtient ou définit le style de majuscule utilisé à la fin des tirets qui composent les lignes pointillées dessinées avec ce`Pen` . |
| [DashOffset](../../aspose.psd/pen/dashoffset/) { get; set; } | Obtient ou définit la distance entre le début d'une ligne et le début d'un motif en tirets. |
| [DashPattern](../../aspose.psd/pen/dashpattern/) { get; set; } | Obtient ou définit un tableau de tirets et d'espaces personnalisés. |
| [DashStyle](../../aspose.psd/pen/dashstyle/) { get; set; } | Obtient ou définit le style utilisé pour les lignes en pointillés dessinées avec ce`Pen` . |
| [EndCap](../../aspose.psd/pen/endcap/) { get; set; } | Obtient ou définit le style de majuscule utilisé à la fin des lignes dessinées avec ce`Pen` . |
| [LineJoin](../../aspose.psd/pen/linejoin/) { get; set; } | Obtient ou définit le style de jointure pour les extrémités de deux lignes consécutives dessinées avec ce`Pen` . |
| [MiterLimit](../../aspose.psd/pen/miterlimit/) { get; set; } | Obtient ou définit la limite de l'épaisseur de la jointure sur un coin en onglet. |
| [Opacity](../../aspose.psd/transparencysupporter/opacity/) { get; set; } | Obtient ou définit l'opacité de l'objet. La valeur doit être comprise entre 0 et 1. La valeur 0 signifie que l'objet est entièrement visible, la valeur 1 signifie que l'objet est entièrement opaque. |
| [PenType](../../aspose.psd/pen/pentype/) { get; } | Obtient le style des lignes dessinées avec ceci`Pen` . |
| [StartCap](../../aspose.psd/pen/startcap/) { get; set; } | Obtient ou définit le style de majuscule utilisé au début des lignes dessinées avec ce`Pen` . |
| [Transform](../../aspose.psd/pen/transform/) { get; set; } | Obtient ou définit une copie de la transformation géométrique pour ce`Pen` . |
| [Width](../../aspose.psd/pen/width/) { get; set; } | Obtient ou définit la largeur de cette`Pen` , en unités de l'objet Graphics utilisé pour le dessin. |

## Méthodes

| Nom | La description |
| --- | --- |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform)(Matrix) | Multiplie la matrice de transformation pour cette`Pen` par le spécifié[`Matrix`](../matrix/) . |
| [MultiplyTransform](../../aspose.psd/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | Multiplie la matrice de transformation pour cette`Pen` par le spécifié[`Matrix`](../matrix/) dans l'ordre spécifié. |
| [ResetTransform](../../aspose.psd/pen/resettransform/)() | Réinitialise la matrice de transformation géométrique pour ce`Pen` à l'identité. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform)(float) | Fait pivoter la transformation géométrique locale selon l'angle spécifié. Cette méthode ajoute la rotation à la transformation. |
| [RotateTransform](../../aspose.psd/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | Fait pivoter la transformation géométrique locale de l'angle spécifié dans l'ordre spécifié. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform)(float, float) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés. Cette méthode ajoute la matrice de mise à l'échelle à la transformation. |
| [ScaleTransform](../../aspose.psd/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | Met à l'échelle la transformation géométrique locale par les facteurs spécifiés dans l'ordre spécifié. |
| [SetLineCap](../../aspose.psd/pen/setlinecap/)(LineCap, LineCap, DashCap) | Définit les valeurs qui déterminent le style de capuchon utilisé pour terminer les lignes dessinées par ce`Pen` . |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform)(float, float) | Traduit la transformation géométrique locale par les dimensions spécifiées. Cette méthode ajoute la traduction à la transformation. |
| [TranslateTransform](../../aspose.psd/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | Traduit la transformation géométrique locale par les dimensions spécifiées dans l'ordre spécifié. |

### Exemples

Cet exemple montre la création et l'utilisation des objets Pen. L'exemple crée une nouvelle image et dessine des rectangles sur la surface de l'image.

```csharp
[C#]

//Créer une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Créer une instance de Graphics et l'initialiser avec l'objet Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Effacer la surface graphique avec la couleur blanche
    graphics.Clear(Aspose.PSD.Color.White);

    //Crée une instance de Pen avec la couleur Rouge et la largeur 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Créer une instance de HatchBrush et définir ses propriétés
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Créer une instance de Pen
    // l'initialise avec l'objet HatchBrush et sa largeur
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    // Dessiner des rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    // Dessiner des rectangles en spécifiant l'objet Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Créer des options d'exportation et les initialiser.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // Enregistrer toutes les modifications.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Voir également

* class [TransparencySupporter](../transparencysupporter/)
* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


