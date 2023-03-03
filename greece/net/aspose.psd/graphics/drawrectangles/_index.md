---
title: Graphics.DrawRectangles
second_title: Aspose.PSD για Αναφορά API .NET
description: Graphics μέθοδος. Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται απόRectangleF δομές.
type: docs
weight: 310
url: /el/net/aspose.psd/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από[`RectangleF`](../../rectanglef/) δομές.

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | RectangleF[] | Συστοιχία από[`RectangleF`](../../rectanglef/) δομές που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *rects* είναι μηδενικό. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από[`Rectangle`](../../rectangle/) δομές.

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | Rectangle[] | Συστοιχία από[`Rectangle`](../../rectangle/) δομές που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *pen* είναι μηδενικό. -ή- *rects* είναι μηδενικό. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* χώρος ονομάτων [Aspose.PSD](../../graphics/)
* συνέλευση [Aspose.PSD](../../../)


