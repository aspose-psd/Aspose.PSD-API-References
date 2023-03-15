---
title: Class SolidBrush
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.SolidBrush τάξη. Το Το συμπαγές πινέλο προορίζεται για συνεχή σχεδίαση με συγκεκριμένο χρώμα. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 200
url: /el/net/aspose.psd.brushes/solidbrush/
---
## SolidBrush class

Το Το συμπαγές πινέλο προορίζεται για συνεχή σχεδίαση με συγκεκριμένο χρώμα. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class SolidBrush : Brush
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`SolidBrush` τάξη. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Αρχικοποιεί μια νέα παρουσία του`SolidBrush` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Παίρνει ή ρυθμίζει το χρώμα του πινέλου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί έναν νέο βαθύ κλώνο του ρεύματος[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

Αυτό το παράδειγμα χρησιμοποιεί την κλάση Graphics για τη δημιουργία πρωτόγονων σχημάτων στην επιφάνεια της εικόνας. Για την επίδειξη της λειτουργίας, το παράδειγμα δημιουργεί μια νέα εικόνα σε μορφή PSD και σχεδιάζει πρωτόγονα σχήματα στην επιφάνεια της εικόνας χρησιμοποιώντας μεθόδους Draw που εκτίθενται από την κλάση Graphics και στη συνέχεια την εξάγει σε μορφή αρχείου PSD.

```csharp
[C#]

//Δημιουργία μιας παρουσίας εικόνας 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργία και προετοιμασία μιας παρουσίας της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Διαγραφή επιφάνειας γραφικών
    graphics.Clear(Color.Wheat);

    //Σχεδιάστε ένα τόξο καθορίζοντας το αντικείμενο Pen να έχει μαύρο χρώμα, 
    //α Ορθογώνιο που περιβάλλει το τόξο, τη γωνία έναρξης και τη γωνία σάρωσης
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Σχεδιάστε ένα Bezier καθορίζοντας το αντικείμενο Pen να έχει μπλε χρώμα και συντεταγμένα σημεία.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Σχεδιάστε μια καμπύλη καθορίζοντας το αντικείμενο Pen να έχει πράσινο χρώμα και έναν πίνακα σημείων
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Σχεδιάστε μια έλλειψη χρησιμοποιώντας το αντικείμενο στυλό και ένα ορθογώνιο που το περιβάλλει
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //ΖΩΓΡΑΦΙΣΕ μια γραμμη 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Σχεδιάστε ένα τμήμα πίτας
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Σχεδιάστε ένα πολύγωνο καθορίζοντας το αντικείμενο Pen να έχει κόκκινο χρώμα και έναν πίνακα σημείων
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Σχεδιάστε ένα ορθογώνιο
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Δημιουργήστε ένα αντικείμενο SolidBrush και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Σχεδιάστε μια συμβολοσειρά χρησιμοποιώντας το αντικείμενο SolidBrush και τη γραμματοσειρά, σε συγκεκριμένο σημείο
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Δημιουργήστε μια παρουσία του PngOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // αποθήκευση όλων των αλλαγών.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Δείτε επίσης

* class [Brush](../../aspose.psd/brush/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


