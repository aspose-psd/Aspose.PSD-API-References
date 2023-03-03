---
title: Class HatchBrush
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Brushes.HatchBrush τάξη. Καθορίζει ένα ορθογώνιο πινέλο με στυλ καταπακτής χρώμα προσκηνίου και χρώμα φόντου. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
type: docs
weight: 130
url: /el/net/aspose.psd.brushes/hatchbrush/
---
## HatchBrush class

Καθορίζει ένα ορθογώνιο πινέλο με στυλ καταπακτής, χρώμα προσκηνίου και χρώμα φόντου. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

```csharp
public sealed class HatchBrush : Brush
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [HatchBrush](hatchbrush/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../aspose.psd.brushes/hatchbrush/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα των διαστημάτων μεταξύ των γραμμών καταπακτής. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [ForegroundColor](../../aspose.psd.brushes/hatchbrush/foregroundcolor/) { get; set; } | Παίρνει ή ρυθμίζει το χρώμα των γραμμών καταπακτής. |
| [HatchStyle](../../aspose.psd.brushes/hatchbrush/hatchstyle/) { get; set; } | Αποκτά ή ρυθμίζει το στυλ καταπακτής αυτού του πινέλου. |
| [Opacity](../../aspose.psd/brush/opacity/) { get; set; } | Λαμβάνει ή ρυθμίζει την αδιαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Η τιμή 0 σημαίνει ότι η βούρτσα είναι πλήρως ορατή, η τιμή 1 σημαίνει ότι η βούρτσα είναι πλήρως αδιαφανής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [DeepClone](../../aspose.psd/brush/deepclone/)() | Δημιουργεί έναν νέο βαθύ κλώνο του ρεύματος[`Brush`](../../aspose.psd/brush/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη δημιουργία και τη χρήση αντικειμένων Pen. Το παράδειγμα δημιουργεί μια νέα εικόνα και σχεδιάζει ορθογώνια στην επιφάνεια της εικόνας.

```csharp
[C#]

//Δημιουργία μιας παρουσίας εικόνας
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε μια παρουσία γραφικών και αρχικοποιήστε την με αντικείμενο Image
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Διαγράψτε την επιφάνεια γραφικών με λευκό χρώμα
    graphics.Clear(Aspose.PSD.Color.White);

    //Δημιουργήστε ένα στιγμιότυπο στυλό με χρώμα κόκκινο και πλάτος 5
    Aspose.PSD.Pen pen = new Pen(Aspose.PSD.Color.Red, 5);

    //Δημιουργήστε μια παρουσία του HatchBrush και ορίστε τις ιδιότητές του
    Aspose.PSD.Brushes.HatchBrush brush = new Aspose.PSD.Brushes.HatchBrush();
    brush.BackgroundColor = Color.Wheat;
    brush.ForegroundColor = Color.Red;

    //Δημιουργία μιας παρουσίας στυλό
    //αρχικοποιήστε το με αντικείμενο και πλάτος HatchBrush
    Aspose.PSD.Pen brusedpen = new Pen(brush, 5);

    //Σχεδιάστε ορθογώνια καθορίζοντας αντικείμενο Pen
    graphics.DrawRectangles(pen, new[] { new Rectangle(new Point(210, 210), new Size(100, 100)), new Rectangle(new Point(110, 110), new Size(100, 100)), new Rectangle(new Point(310, 310), new Size(100, 100)) });

    //Σχεδιάστε ορθογώνια καθορίζοντας αντικείμενο Pen
    graphics.DrawRectangles(brusedpen, new[] { new Rectangle(new Point(310, 110), new Size(100, 100)), new Rectangle(new Point(110, 310), new Size(100, 100)) });

    // Δημιουργήστε επιλογές εξαγωγής και αρχικοποιήστε τις.
    Aspose.PSD.ImageOptions.Jpeg2000Options options = new Aspose.PSD.ImageOptions.Jpeg2000Options();

    // αποθήκευση όλων των αλλαγών.
    image.Save("c:\\temp\\output.jp2", options);
}
```

### Δείτε επίσης

* class [Brush](../../aspose.psd/brush/)
* χώρος ονομάτων [Aspose.PSD.Brushes](../../aspose.psd.brushes/)
* συνέλευση [Aspose.PSD](../../)


