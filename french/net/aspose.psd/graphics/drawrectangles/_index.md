---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Dessine une série de rectangles spécifiés par des structures RectangleF."
type: docs
weight: 320
url: /fr/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Dessine une série de rectangles spécifiés par des structures [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | RectangleF[] | Tableau de structures [`RectangleF`](../../rectanglef/) qui représentent les rectangles à dessiner. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *rects* est nul. |

### Voir aussi

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Dessine une série de rectangles spécifiés par des structures [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) qui détermine la couleur, la largeur et le style des contours des rectangles. |
| rects | Rectangle[] | Tableau de structures [`Rectangle`](../../rectangle/) qui représentent les rectangles à dessiner. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *pen* est nul. -ou- *rects* est nul. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


