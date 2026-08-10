---
title: "Κλάση FileCreateSource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.Sources.FileCreateSource. Αντιπροσωπεύει μια πηγή αρχείου για δημιουργία."
type: docs
weight: 6090
url: /el/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Αναπαριστά πηγή αρχείου για δημιουργία.

```csharp
public sealed class FileCreateSource : FileSource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `FileCreateSource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Λαμβάνει τη διαδρομή του αρχείου για δημιουργία. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν το αρχείο θα είναι προσωρινό. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Λαμβάνει το κοντέινερ ροής. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση των κλάσεων Font και SolidBrush για τη σχεδίαση κειμένων στην επιφάνεια της Image. Το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει σχήματα χρησιμοποιώντας τις Figures και το GraphicsPath.

```csharp
[C#]

//Δημιουργεί ένα στιγμιότυπο της Image.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργεί και αρχικοποιεί ένα στιγμιότυπο της κλάσης Graphics.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίζει την επιφάνεια Graphics.
    graphics.Clear(Color.Wheat);

    //Δημιουργεί ένα στιγμιότυπο της Font.
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Δημιουργεί ένα στιγμιότυπο της SolidBrush με κόκκινο χρώμα.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Σχεδιάζει μια συμβολοσειρά.
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // Δημιουργεί επιλογές εξαγωγής.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // αποθηκεύστε όλες τις αλλαγές
    image.Save("C:\\temp\\output.gif", options);
}
```

### Δείτε επίσης

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


