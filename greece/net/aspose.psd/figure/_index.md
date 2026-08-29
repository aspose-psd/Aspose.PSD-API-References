---
title: "Κλάση Figure"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.Figure κλάση. Το σχήμα. Ένας υποδοχέας για σχήματα."
type: docs
weight: 1210
url: /el/net/aspose.psd/figure/
---
{{< psd/tize >}}
## Figure class

Το σχήμα. Ένα δοχείο για σχήματα.

```csharp
public class Figure : ObjectWithBounds
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Figure](figure/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd/figure/bounds/) { get; } | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [IsClosed](../../aspose.psd/figure/isclosed/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτό το σχήμα είναι κλειστό. Ένα κλειστό σχήμα θα κάνει διαφορά μόνο στην περίπτωση όπου τα σχήματα του πρώτου και του τελευταίου σχήματος είναι συνεχόμενα σχήματα. Σε αυτήν την περίπτωση το πρώτο σημείο του πρώτου σχήματος θα συνδεθεί με ευθεία γραμμή από το τελευταίο σημείο του τελευταίου σχήματος. |
| [Segments](../../aspose.psd/figure/segments/) { get; } | Λαμβάνει τα ολόκληρα τμήματα του σχήματος. |
| [Shapes](../../aspose.psd/figure/shapes/) { get; } | Λαμβάνει τα σχήματα του σχήματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddShape](../../aspose.psd/figure/addshape/)(Shape) | Προσθέτει ένα σχήμα στο σχήμα. |
| [AddShapes](../../aspose.psd/figure/addshapes/)(Shape[]) | Προσθέτει μια σειρά σχημάτων στο σχήμα. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd/figure/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [RemoveShape](../../aspose.psd/figure/removeshape/)(Shape) | Αφαιρεί ένα σχήμα από το σχήμα. |
| [RemoveShapes](../../aspose.psd/figure/removeshapes/)(Shape[]) | Αφαιρεί μια σειρά σχημάτων από το σχήμα. |
| [Reverse](../../aspose.psd/figure/reverse/)() | Αντιστρέφει τη σειρά των σχημάτων αυτού του σχήματος και τη σειρά των σημείων των σχημάτων. |
| override [Transform](../../aspose.psd/figure/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

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

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


