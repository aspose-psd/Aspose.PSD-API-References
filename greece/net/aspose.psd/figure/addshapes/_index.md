---
title: Figure.AddShapes
second_title: Aspose.PSD για Αναφορά API .NET
description: Figure μέθοδος. Προσθέτει μια σειρά σχημάτων στο σχήμα.
type: docs
weight: 70
url: /el/net/aspose.psd/figure/addshapes/
---
## Figure.AddShapes method

Προσθέτει μια σειρά σχημάτων στο σχήμα.

```csharp
public void AddShapes(Shape[] shapes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | Shape[] | Τα σχήματα για προσθήκη. |

### Παραδείγματα

Αυτό το παράδειγμα δημιουργεί μια νέα εικόνα και σχεδιάζει μια ποικιλία σχημάτων χρησιμοποιώντας σχήματα και GraphicsPath στην επιφάνεια της εικόνας

```csharp
[C#]

//Δημιουργία μιας παρουσίας εικόνας
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργία και προετοιμασία μιας παρουσίας της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Διαγραφή επιφάνειας γραφικών
    graphics.Clear(Color.Wheat);

    //Δημιουργήστε μια παρουσία της κλάσης GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Δημιουργήστε μια παρουσία της κλάσης Figure
    Aspose.PSD.Figure figure1 = new Aspose.PSD.Figure();

    //Προσθήκη σχήματος στο αντικείμενο σχήματος
    figure1.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Δημιουργήστε μια παρουσία της κλάσης Figure
    Aspose.PSD.Figure figure2 = new Aspose.PSD.Figure();

    //Προσθήκη σχήματος στο αντικείμενο σχήματος
    figure2.AddShape(new Aspose.PSD.Shapes.ArcShape(new RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.PSD.Shapes.PolygonShape(new[] { new PointF(150, 10), new PointF(150, 200), new PointF(250, 300), new PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.PSD.Shapes.RectangleShape(new Rectangle(new Point(250, 250), new Size(200, 200))));

    //Προσθήκη αντικειμένου Figure στο GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //Σχεδίαση διαδρομής με αντικείμενο στυλό χρώματος Μαύρο
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    // Δημιουργήστε επιλογές εξαγωγής και αρχικοποιήστε τις.
    Aspose.PSD.ImageOptions.BmpOptions options = new Aspose.PSD.ImageOptions.BmpOptions();

    // αποθήκευση όλων των αλλαγών.
    image.Save("c:\\temp\\output.bmp", options);
}
```

### Δείτε επίσης

* class [Shape](../../shape/)
* class [Figure](../)
* χώρος ονομάτων [Aspose.PSD](../../figure/)
* συνέλευση [Aspose.PSD](../../../)


