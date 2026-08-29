---
title: "Figure.AddShapes"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Figure. Προσθέτει μια σειρά σχημάτων στο Figure"
type: docs
weight: 70
url: /el/net/aspose.psd/figure/addshapes/
---
{{< psd/tize >}}
## Figure.AddShapes method

Προσθέτει μια σειρά σχημάτων στο σχήμα.

```csharp
public void AddShapes(Shape[] shapes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σχήματα | Shape[] | Τα σχήματα προς προσθήκη. |

## Παραδείγματα

Αυτό το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει μια ποικιλία σχημάτων χρησιμοποιώντας Figures και GraphicsPath στην επιφάνεια της Image.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε και αρχικοποιήστε ένα στιγμιότυπο της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίστε την επιφάνεια Graphics
    graphics.Clear(Color.Wheat);

    //Δημιουργήστε ένα στιγμιότυπο της κλάσης GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Δημιουργήστε ένα στιγμιότυπο της κλάσης Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Προσθήκη Shape στο αντικείμενο Figure
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Δημιουργήστε ένα στιγμιότυπο της κλάσης Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Προσθήκη Shape στο αντικείμενο Figure
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Προσθέστε το αντικείμενο Figure στο GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Σχεδιάστε τη διαδρομή με το αντικείμενο Pen χρώματος Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Δημιουργήστε επιλογές εξαγωγής και αρχικοποιήστε τις.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Δείτε επίσης

* class [Shape](../../shape/)
* class [Figure](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


