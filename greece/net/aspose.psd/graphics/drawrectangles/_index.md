---
title: "Graphics.DrawRectangles"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Graphics. Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές RectangleF."
type: docs
weight: 320
url: /el/net/aspose.psd/graphics/drawrectangles/
---
{{< psd/tize >}}
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [`RectangleF`](../../rectanglef/).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | RectangleF[] | Πίνακας δομών [`RectangleF`](../../rectanglef/) που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *rects* είναι null. |

### Δείτε επίσης

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Σχεδιάζει μια σειρά από ορθογώνια που καθορίζονται από δομές [`Rectangle`](../../rectangle/).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) που καθορίζει το χρώμα, το πλάτος και το στυλ των περιγραμμάτων των ορθογωνίων. |
| rects | Rectangle[] | Πίνακας δομών [`Rectangle`](../../rectangle/) που αντιπροσωπεύουν τα ορθογώνια προς σχεδίαση. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | *pen* είναι null. -ή- *rects* είναι null. |

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

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


