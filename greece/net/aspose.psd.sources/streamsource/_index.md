---
title: "Κλάση StreamSource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Sources.StreamSource. Αντιπροσωπεύει μια πηγή ροής"
type: docs
weight: 6120
url: /el/net/aspose.psd.sources/streamsource/
---
{{< psd/tize >}}
## StreamSource class

Αναπαριστά πηγή ροής.

```csharp
public sealed class StreamSource : Source
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [StreamSource](streamsource/#constructor)(Stream) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `StreamSource`. |
| [StreamSource](streamsource/#constructor_1)(Stream, bool) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `StreamSource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DisposeStream](../../aspose.psd.sources/streamsource/disposestream/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η ροή πρέπει να διαγραφεί όταν το δοχείο διαγραφεί. |
| [Stream](../../aspose.psd.sources/streamsource/stream/) { get; } | Λαμβάνει τη ροή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/streamsource/getstreamcontainer/)() | Λαμβάνει το κοντέινερ ροής. |

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

* class [Source](../../aspose.psd/source/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


