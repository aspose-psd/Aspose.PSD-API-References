---
title: "Graphics.DrawPath"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Graphics μέθοδος. Σχεδιάζει ένα GraphicsPath"
type: docs
weight: 280
url: /el/net/aspose.psd/graphics/drawpath/
---
{{< psd/tize >}}
## Graphics.DrawPath method

Σχεδιάζει ένα [`GraphicsPath`](../../graphicspath/).

```csharp
public void DrawPath(Pen pen, GraphicsPath path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | `Pen` που καθορίζει το χρώμα, το πλάτος και το στυλ της διαδρομής. |
| path | GraphicsPath | `GraphicsPath` για σχεδίαση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *path* είναι null. |

## Παραδείγματα

Αυτά τα παραδείγματα χρησιμοποιούν τις κλάσεις GraphicsPath και Graphics για τη δημιουργία και τη διαχείριση Σχημάτων σε μια επιφάνεια Image. Το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει διαδρομές με τη βοήθεια της κλάσης GraphicsPath. Στο τέλος, η μέθοδος DrawPath που εκτίθεται από την κλάση Graphics καλείται για την απόδοση των διαδρομών στην επιφάνεια. Τέλος, η εικόνα εξάγεται σε μορφή αρχείου Tiff.

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
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Προσθέστε Σχήματα στο αντικείμενο Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Προσθέστε το αντικείμενο Figure στο GraphicsPath
    graphicspath.AddFigure(figure);

    //Σχεδιάστε τη διαδρομή με το αντικείμενο Pen χρώματος Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Δημιουργήστε ένα στιγμιότυπο του TiffOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Δείτε επίσης

* class [Pen](../../pen/)
* class [GraphicsPath](../../graphicspath/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


