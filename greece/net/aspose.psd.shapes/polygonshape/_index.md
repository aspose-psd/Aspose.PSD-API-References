---
title: "Κλάση PolygonShape"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Η κλάση Aspose.PSD.Shapes.PolygonShape. Αντιπροσωπεύει ένα σχήμα πολύγωνου."
type: docs
weight: 6010
url: /el/net/aspose.psd.shapes/polygonshape/
---
{{< psd/tize >}}
## PolygonShape class

Αναπαριστά ένα σχήμα πολυγώνου.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PolygonShape`. |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PolygonShape`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/polygonshape/bounds/) { get; } | Λαμβάνει τα όρια του αντικειμένου. |
| override [Center](../../aspose.psd.shapes/polygonshape/center/) { get; } | Λαμβάνει το κέντρο του σχήματος. |
| virtual [EndPoint](../../aspose.psd.shapes/polygonshape/endpoint/) { get; } | Λαμβάνει το τελικό σημείο του σχήματος. |
| override [HasSegments](../../aspose.psd.shapes/polygonshape/hassegments/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| [IsClosed](../../aspose.psd.shapes/polygonshape/isclosed/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σχήμα είναι κλειστό. |
| [Points](../../aspose.psd.shapes/polygonshape/points/) { get; set; } | Λαμβάνει ή ορίζει τα σημεία της καμπύλης. |
| override [Segments](../../aspose.psd.shapes/polygonshape/segments/) { get; } | Λαμβάνει τα τμήματα του σχήματος. |
| virtual [StartPoint](../../aspose.psd.shapes/polygonshape/startpoint/) { get; } | Λαμβάνει το αρχικό σημείο του σχήματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [Reverse](../../aspose.psd.shapes/polygonshape/reverse/)() | Αντιστρέφει τη σειρά των σημείων για αυτό το σχήμα. |
| override [Transform](../../aspose.psd.shapes/polygonshape/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

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

* class [Shape](../../aspose.psd/shape/)
* interface [IOrderedShape](../../aspose.psd/iorderedshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


