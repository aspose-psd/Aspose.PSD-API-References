---
title: "Classe HatchBrush"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Brushes.HatchBrush. Définit un brush rectangulaire avec un style de hachure, une couleur de premier plan et une couleur d'arrière-plan. Cette classe ne peut pas être héritée"
type: docs
weight: 130
url: /fr/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Définit un pinceau rectangulaire avec un style hachuré, une couleur de premier plan et une couleur d'arrière-plan. Cette classe ne peut pas être héritée.

```csharp
public sealed class HatchBrush : Brush
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Obtient ou définit la couleur des espaces entre les lignes de hachure. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Obtient ou définit la couleur des lignes de hachure. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Obtient ou définit le style de hachure de ce brush. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Obtient ou définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est entièrement opaque. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Crée un nouveau clone profond du [`Brush`](../../aspose.psd/brush/) actuel. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

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

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


