---
title: Class GraphicsPath
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.GraphicsPath τάξη. Αντιπροσωπεύει μια σειρά από συνδεδεμένες γραμμές και καμπύλες. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 4320
url: /el/net/aspose.psd/graphicspath/
---
## GraphicsPath class

Αντιπροσωπεύει μια σειρά από συνδεδεμένες γραμμές και καμπύλες. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`GraphicsPath` τάξη. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Αρχικοποιεί μια νέα παρουσία του`GraphicsPath` τάξη. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Αρχικοποιεί μια νέα παρουσία του`GraphicsPath` τάξη. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Αρχικοποιεί μια νέα παρουσία του`GraphicsPath` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Λαμβάνει τα στοιχεία της διαδρομής. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Λαμβάνει ή ορίζει α[`FillMode`](../fillmode/) απαρίθμηση που καθορίζει πώς οι εσωτερικοί χώροι των σχημάτων σε αυτό`GraphicsPath` γεμίζουν. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Προσθέτει ένα νέο σχήμα. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Προσθέτει νέα στοιχεία. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Προσθέτει το καθορισμένο`GraphicsPath` σε αυτό το μονοπάτι. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Προσθέτει το καθορισμένο`GraphicsPath` σε αυτό το μονοπάτι. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Εκτελεί έναν βαθύ κλώνο αυτής της διαδρομής γραφικών. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό`GraphicsPath` σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Μετατρέπει κάθε καμπύλη σε αυτό`GraphicsPath` σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο[`Graphics`](../graphics/) . |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται (κάτω από) το περίγραμμα αυτού`GraphicsPath` όταν τραβηχτεί με το καθορισμένο[`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` στην περιοχή ορατού κλιπ του καθορισμένου[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Υποδεικνύει εάν το καθορισμένο σημείο περιέχεται σε αυτό`GraphicsPath` , χρησιμοποιώντας το καθορισμένο[`Graphics`](../graphics/) . |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Αφαιρεί μια φιγούρα. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Αφαιρεί φιγούρες. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Αδειάζει τη διαδρομή γραφικών και ορίζει το[`FillMode`](../fillmode/) προς τηνAlternate . |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Αντιστρέφει τη σειρά των σχημάτων, σχημάτων και σημείων σε κάθε σχήμα αυτού`GraphicsPath` . |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό`GraphicsPath` . |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Εφαρμόζει έναν μετασχηματισμό στημόνι, που ορίζεται από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Προσθέτει ένα επιπλέον περίγραμμα στο`GraphicsPath` . |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Αντικαθιστά αυτό`GraphicsPath` με καμπύλες που περικλείουν την περιοχή που γεμίζει όταν αυτή η διαδρομή χαράσσεται από την καθορισμένη πένα. |

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


