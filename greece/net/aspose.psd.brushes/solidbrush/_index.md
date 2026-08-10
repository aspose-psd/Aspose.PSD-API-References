---
title: "Κλάση SolidBrush"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.Brushes.SolidBrush κλάση. Το Solid brush προορίζεται για συνεχή σχεδίαση με συγκεκριμένο χρώμα. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 200
url: /el/net/aspose.psd.brushes/solidbrush/
---
{{< psd/tize >}}
## SolidBrush class

Το συμπαγές πινέλο προορίζεται για συνεχή σχεδίαση με συγκεκριμένο χρώμα. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class SolidBrush : Brush
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `SolidBrush`. |
| [SolidBrush](solidbrush/#constructor_1)(Color) | Αρχικοποιεί μια νέα παρουσία της κλάσης `SolidBrush`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Color](../../aspose.psd.brushes/solidbrush/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα του brush. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |

## Παραδείγματα

Αυτό το παράδειγμα χρησιμοποιεί την κλάση Graphics για τη δημιουργία πρωτόγονων σχημάτων στην επιφάνεια Image. Για να επιδείξει τη λειτουργία, το παράδειγμα δημιουργεί ένα νέο Image σε μορφή PSD και σχεδιάζει πρωτόγονα σχήματα στην επιφάνεια Image χρησιμοποιώντας τις μεθόδους Draw που εκτίθενται από την κλάση Graphics, στη συνέχεια το εξάγει σε μορφή αρχείου PSD.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε και αρχικοποιήστε ένα στιγμιότυπο της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίστε την επιφάνεια Graphics
    graphics.Clear(Color.Wheat);

    //Σχεδιάστε ένα τόξο καθορίζοντας το αντικείμενο Pen με χρώμα Μαύρο, 
    //ένα Rectangle που περιβάλλει το τόξο, η γωνία έναρξης και η γωνία σάρωσης
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //Σχεδιάστε μια καμπύλη Bezier καθορίζοντας το αντικείμενο Pen με χρώμα Μπλε και σημεία συντεταγμένων.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //Σχεδιάστε μια Καμπύλη καθορίζοντας το αντικείμενο Pen με χρώμα Πράσινο και έναν πίνακα σημείων
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Σχεδιάστε μια Έλλειψη χρησιμοποιώντας το αντικείμενο Pen και ένα περιβάλλον Rectangle
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //Σχεδιάστε μια Γραμμή 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //Σχεδιάστε ένα τμήμα Πίτας
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //Σχεδιάστε ένα Πολύγωνο καθορίζοντας το αντικείμενο Pen με χρώμα Κόκκινο και έναν πίνακα σημείων
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //Σχεδιάστε ένα Rectangle
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //Δημιουργήστε ένα αντικείμενο SolidBrush και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //Σχεδιάστε ένα String χρησιμοποιώντας το αντικείμενο SolidBrush και τη Font, σε συγκεκριμένο Point
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //Δημιουργήστε ένα στιγμιότυπο του PngOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### Δείτε επίσης

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


