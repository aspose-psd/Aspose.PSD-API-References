---
title: "Κλάση HatchBrush"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Brushes.HatchBrush. Ορίζει ένα ορθογώνιο Brush με στυλ διαγράμμισης, χρώμα προσκηνίου και χρώμα φόντου. Αυτή η κλάση δεν μπορεί να κληρονομηθεί."
type: docs
weight: 130
url: /el/net/aspose.psd.brushes/hatchbrush/
---
{{< psd/tize >}}
## HatchBrush class

Ορίζει ένα ορθογώνιο πινέλο με στυλ διαγράμμισης, χρώμα προσκηνίου και χρώμα φόντου. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class HatchBrush : Brush
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Ανακτά ή ορίζει το χρώμα των κενών μεταξύ των γραμμών διαγράμμισης. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Ανακτά ή ορίζει το χρώμα των γραμμών διαγράμμισης. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Ανακτά ή ορίζει το στυλ διαγράμμισης αυτού του brush. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Αποκτά ή ορίζει τη διαφάνεια του πινέλου. Η τιμή πρέπει να βρίσκεται μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος [`Brush`](../../aspose.psd/brush/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη δημιουργία και χρήση αντικειμένων Pen. Το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει Rectangles στην επιφάνεια της Image.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε μια παρουσία του Graphics και αρχικοποιήστε την με το αντικείμενο Image.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίστε την επιφάνεια του Graphics με λευκό χρώμα.
    graphics.Clear(Aspose.PSD.Color.White);

    //Δημιουργήστε μια παρουσία του Pen με χρώμα Red και πλάτος 5.
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Δημιουργήστε μια παρουσία του HatchBrush και ορίστε τις ιδιότητές του.
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Δημιουργήστε μια παρουσία του Pen.
    //Αρχικοποιήστε το με το αντικείμενο HatchBrush και το πλάτος.
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Σχεδιάστε Rectangles καθορίζοντας το αντικείμενο Pen.
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Σχεδιάστε Rectangles καθορίζοντας το αντικείμενο Pen.
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Δημιουργήστε επιλογές εξαγωγής και αρχικοποιήστε τις.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Δείτε επίσης

* class [Brush](../../aspose.psd/brush/)
* namespace [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* assembly [Aspose.PSD](../../)


