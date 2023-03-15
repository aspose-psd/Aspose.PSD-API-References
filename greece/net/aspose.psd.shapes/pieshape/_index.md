---
title: Class PieShape
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Shapes.PieShape τάξη. Αντιπροσωπεύει σχήμα πίτας.
type: docs
weight: 5500
url: /el/net/aspose.psd.shapes/pieshape/
---
## PieShape class

Αντιπροσωπεύει σχήμα πίτας.

```csharp
public class PieShape : EllipseShape
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PieShape](pieshape/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`PieShape` τάξη. |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | Αρχικοποιεί μια νέα παρουσία του`PieShape` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd.shapes/rectangleprojectedshape/bounds/) { get; } | Λαμβάνει τα όρια του αντικειμένου. |
| override [Center](../../aspose.psd.shapes/rectangleprojectedshape/center/) { get; } | Λαμβάνει το κέντρο του σχήματος. |
| override [HasSegments](../../aspose.psd.shapes/rectangleprojectedshape/hassegments/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το σχήμα έχει τμήματα. |
| [LeftBottom](../../aspose.psd.shapes/rectangleprojectedshape/leftbottom/) { get; } | Λαμβάνει το αριστερό κάτω ορθογώνιο σημείο. |
| [LeftTop](../../aspose.psd.shapes/rectangleprojectedshape/lefttop/) { get; } | Λαμβάνει το αριστερό επάνω ορθογώνιο σημείο. |
| [RectangleHeight](../../aspose.psd.shapes/rectangleprojectedshape/rectangleheight/) { get; } | Παίρνει το ύψος του ορθογωνίου. |
| [RectangleWidth](../../aspose.psd.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | Λαμβάνει το πλάτος του ορθογωνίου. |
| [RightBottom](../../aspose.psd.shapes/rectangleprojectedshape/rightbottom/) { get; } | Παίρνει το δεξιό κάτω ορθογώνιο σημείο. |
| [RightTop](../../aspose.psd.shapes/rectangleprojectedshape/righttop/) { get; } | Λαμβάνει το δεξί επάνω ορθογώνιο σημείο. |
| override [Segments](../../aspose.psd.shapes/pieshape/segments/) { get; } | Παίρνει τα τμήματα σχήματος. |
| [StartAngle](../../aspose.psd.shapes/pieshape/startangle/) { get; set; } | Λαμβάνει ή ρυθμίζει τη γωνία έναρξης. |
| [SweepAngle](../../aspose.psd.shapes/pieshape/sweepangle/) { get; set; } | Λαμβάνει ή ρυθμίζει τη γωνία σάρωσης. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| override [Transform](../../aspose.psd.shapes/rectangleprojectedshape/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |

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

* class [EllipseShape](../ellipseshape/)
* χώρος ονομάτων [Aspose.PSD.Shapes](../../aspose.psd.shapes/)
* συνέλευση [Aspose.PSD](../../)


