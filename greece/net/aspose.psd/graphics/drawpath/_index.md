---
title: Graphics.DrawPath
second_title: Aspose.PSD για Αναφορά API .NET
description: Graphics μέθοδος. Ζωγραφίζει αGraphicsPath .
type: docs
weight: 270
url: /el/net/aspose.psd/graphics/drawpath/
---
## Graphics.DrawPath method

Ζωγραφίζει α[`GraphicsPath`](../../graphicspath/) .

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ της διαδρομής. |
| path | GraphicsPath | [`GraphicsPath`](../../graphicspath/) να ζωγραφίσει. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *path* είναι μηδενικό. |

### Παραδείγματα

Αυτά τα παραδείγματα χρησιμοποιούν την κλάση GraphicsPath και Graphics για τη δημιουργία και τον χειρισμό Φιγούρων σε μια επιφάνεια εικόνας. Το Example δημιουργεί μια νέα εικόνα και σχεδιάζει μονοπάτια με τη βοήθεια της κλάσης GraphicsPath. Στο τέλος η μέθοδος DrawPath που εκτίθεται από την κλάση Graphics καλείται να αποδώσει τα μονοπάτια στην επιφάνεια. Τέλος, η εικόνα εξάγεται σε μορφή αρχείου Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Προσθήκη σχημάτων στο αντικείμενο Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Προσθήκη αντικειμένου Figure στο GraphicsPath
    graphicspath.AddFigure(figure);

    //Σχεδίαση διαδρομής με αντικείμενο στυλό χρώματος Μαύρο
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Δημιουργήστε μια παρουσία του TiffOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // αποθήκευση όλων των αλλαγών.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Δείτε επίσης

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)


