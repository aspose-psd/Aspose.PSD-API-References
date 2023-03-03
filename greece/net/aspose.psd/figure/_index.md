---
title: Class Figure
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Figure τάξη. Το σχήμα. Ένα δοχείο για σχήματα.
type: docs
weight: 1200
url: /el/net/aspose.psd/figure/
---
## Figure class

Το σχήμα. Ένα δοχείο για σχήματα.

```csharp
public class Figure : ObjectWithBounds
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Figure](figure/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτός ο αριθμός είναι κλειστός. Ένα κλειστό σχήμα θα κάνει τη διαφορά μόνο στην περίπτωση που το πρώτο και το τελευταίο σχήμα είναι συνεχόμενα σχήματα. Σε αυτή την περίπτωση το πρώτο σημείο του πρώτου σχήματος θα είναι συνδεδεμένο με μια ευθεία γραμμή από το τελευταίο σημείο του τελευταίου σχήματος. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Λαμβάνει ολόκληρα τμήματα του σχήματος. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Παίρνει τα σχήματα. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Προσθέτει ένα σχήμα στο σχήμα. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Προσθέτει μια σειρά σχημάτων στο σχήμα. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Αφαιρεί ένα σχήμα από το σχήμα. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Αφαιρεί μια σειρά σχημάτων από το σχήμα. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Αντιστρέφει αυτό το σχήμα που διαμορφώνει τη σειρά και διαμορφώνει τη σημειακή σειρά. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


