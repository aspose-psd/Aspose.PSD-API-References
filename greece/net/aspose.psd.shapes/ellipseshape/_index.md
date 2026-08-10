---
title: "Κλάση EllipseShape"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Shapes.EllipseShape. Αντιπροσωπεύει ένα σχήμα έλλειψης"
type: docs
weight: 5990
url: /el/net/aspose.psd.shapes/ellipseshape/
---
{{< psd/tize >}}
## EllipseShape class

Αναπαριστά ένα σχήμα έλλειψης.

```csharp
public class EllipseShape : RectangleShape
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EllipseShape](ellipseshape/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `EllipseShape`. |
| [EllipseShape](ellipseshape/#constructor_1)(RectangleF) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `EllipseShape`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Λαμβάνει τα όρια του αντικειμένου. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Λαμβάνει το κέντρο του σχήματος. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το σχήμα έχει τμήματα. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Λαμβάνει το αριστερό κάτω σημείο του ορθογωνίου. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Λαμβάνει το αριστερό πάνω σημείο του ορθογωνίου. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Λαμβάνει το ύψος του ορθογωνίου. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Λαμβάνει το πλάτος του ορθογωνίου. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Λαμβάνει το δεξί κάτω σημείο του ορθογωνίου. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Λαμβάνει το δεξί πάνω σημείο του ορθογωνίου. |
| override [Segments](../../aspose.psd.shapes/ellipseshape/segments/) { get; } | Λαμβάνει τα τμήματα του σχήματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

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

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* assembly [Aspose.PSD](../../)


