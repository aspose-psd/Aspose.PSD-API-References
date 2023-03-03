---
title: Class FileCreateSource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.Sources.FileCreateSource τάξη. Αντιπροσωπεύει μια πηγή αρχείου για δημιουργία.
type: docs
weight: 5590
url: /el/net/aspose.psd.sources/filecreatesource/
---
## FileCreateSource class

Αντιπροσωπεύει μια πηγή αρχείου για δημιουργία.

```csharp
public sealed class FileCreateSource : FileSource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Αρχικοποιεί μια νέα παρουσία του`FileCreateSource` τάξη. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Αρχικοποιεί μια νέα παρουσία του`FileCreateSource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Λαμβάνει τη διαδρομή αρχείου για δημιουργία. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το αρχείο θα είναι προσωρινό. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Λαμβάνει το κοντέινερ ροής. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση της κλάσης Font και SolidBrush για τη σχεδίαση συμβολοσειρών στην επιφάνεια εικόνας. Το παράδειγμα δημιουργεί μια νέα εικόνα και σχεδιάζει σχήματα χρησιμοποιώντας το Figure και το GraphicsPath

```csharp
[C#]

//Δημιουργεί μια παρουσία εικόνας
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργεί και προετοιμάζει μια παρουσία της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίζει την επιφάνεια γραφικών
    graphics.Clear(Color.Wheat);

    //Δημιουργεί μια παρουσία γραμματοσειράς
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Δημιουργήστε μια παρουσία του SolidBrush με κόκκινο χρώμα
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Σχεδιάστε μια συμβολοσειρά
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // δημιουργία επιλογών εξαγωγής.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // αποθήκευση όλων των αλλαγών
    image.Save("C:\\temp\\output.gif", options);
}
```

### Δείτε επίσης

* class [FileSource](../filesource/)
* χώρος ονομάτων [Aspose.PSD.Sources](../../aspose.psd.sources/)
* συνέλευση [Aspose.PSD](../../)


