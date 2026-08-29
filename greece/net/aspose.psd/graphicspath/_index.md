---
title: "Κλάση GraphicsPath"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.GraphicsPath. Αντιπροσωπεύει μια σειρά συνδεδεμένων γραμμών και καμπυλών. Αυτή η κλάση δεν μπορεί να κληρονομηθεί"
type: docs
weight: 4790
url: /el/net/aspose.psd/graphicspath/
---
{{< psd/tize >}}
## GraphicsPath class

Αναπαριστά μια σειρά συνδεδεμένων γραμμών και καμπυλών. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης `GraphicsPath`. |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης `GraphicsPath`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Bounds](../../aspose.psd/graphicspath/bounds/) { get; } | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [Figures](../../aspose.psd/graphicspath/figures/) { get; } | Λαμβάνει τα σχήματα διαδρομής. |
| [FillMode](../../aspose.psd/graphicspath/fillmode/) { get; set; } | Λαμβάνει ή ορίζει μια απαρίθμηση [`FillMode`](../fillmode/) που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτό το `GraphicsPath`. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddFigure](../../aspose.psd/graphicspath/addfigure/)(Figure) | Προσθέτει ένα νέο σχήμα. |
| [AddFigures](../../aspose.psd/graphicspath/addfigures/)(Figure[]) | Προσθέτει νέα σχήματα. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath)(GraphicsPath) | Προσθέτει στο τέλος το καθορισμένο `GraphicsPath` σε αυτή τη διαδρομή. |
| [AddPath](../../aspose.psd/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | Προσθέτει στο τέλος το καθορισμένο `GraphicsPath` σε αυτή τη διαδρομή. |
| [DeepClone](../../aspose.psd/graphicspath/deepclone/)() | Δημιουργεί ένα πλήρες αντίγραφο αυτής της διαδρομής γραφικών. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten)() | Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_1)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το `GraphicsPath` σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| [Flatten](../../aspose.psd/graphicspath/flatten/#flatten_2)(Matrix, float) | Μετατρέπει κάθε καμπύλη σε αυτό το `GraphicsPath` σε μια ακολουθία συνδεδεμένων τμημάτων γραμμής. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds)(Matrix) | Λαμβάνει τα όρια του αντικειμένου. |
| override [GetBounds](../../aspose.psd/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | Λαμβάνει τα όρια του αντικειμένου. |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsOutlineVisible](../../aspose.psd/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του `GraphicsPath` όταν σχεδιάζεται με το καθορισμένο [`Pen`](../pen/) και χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible)(Point) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_2)(PointF) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_6)(float, float) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_4)(int, int) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`. |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath` στην ορατή περιοχή αποκοπής του καθορισμένου [`Graphics`](../graphics/). |
| [IsVisible](../../aspose.psd/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το `GraphicsPath`, χρησιμοποιώντας το καθορισμένο [`Graphics`](../graphics/). |
| [RemoveFigure](../../aspose.psd/graphicspath/removefigure/)(Figure) | Αφαιρεί ένα σχήμα. |
| [RemoveFigures](../../aspose.psd/graphicspath/removefigures/)(Figure[]) | Αφαιρεί σχήματα. |
| [Reset](../../aspose.psd/graphicspath/reset/)() | Αδειάζει τη διαδρομή γραφικών και ορίζει το [`FillMode`](../fillmode/) σε Alternate. |
| [Reverse](../../aspose.psd/graphicspath/reverse/)() | Αντιστρέφει τη σειρά των σχημάτων, μορφών και σημείων σε κάθε μορφή αυτού του `GraphicsPath`. |
| override [Transform](../../aspose.psd/graphicspath/transform/)(Matrix) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp)(PointF[], RectangleF) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το `GraphicsPath`. |
| [Warp](../../aspose.psd/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Εφαρμόζει έναν παραμορφωτικό μετασχηματισμό, ορισμένο από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτό το `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen)(Pen) | Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_1)(Pen, Matrix) | Προσθέτει ένα επιπλέον περίγραμμα στο `GraphicsPath`. |
| [Widen](../../aspose.psd/graphicspath/widen/#widen_2)(Pen, Matrix, float) | Αντικαθιστά αυτό το `GraphicsPath` με καμπύλες που περικλείουν την περιοχή που γεμίζει όταν αυτή η διαδρομή σχεδιάζεται με το καθορισμένο στυλό. |

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


