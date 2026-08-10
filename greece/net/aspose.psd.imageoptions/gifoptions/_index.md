---
title: "Κλάση GifOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageOptions.GifOptions κλάση. Οι επιλογές δημιουργίας μορφής αρχείου gif"
type: docs
weight: 5300
url: /el/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

Οι επιλογές δημιουργίας μορφής αρχείου gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Αρχικοποιεί μια νέα παρουσία της κλάσης `GifOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις της παλέτας είναι ταξινομημένες. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά pixel. Εάν είναι μεγαλύτερη του μηδενός, θα χρησιμοποιηθεί συμπίεση με απώλειες. Η συνιστώμενη τιμή για βέλτιστη συμπίεση με απώλειες είναι 80. Το 30 αντιστοιχεί σε πολύ ήπια συμπίεση, το 200 σε βαριά. Λειτουργεί καλύτερα όταν εισάγεται μόνο μικρή απώλεια, και λόγω περιορισμού του αλγορίθμου συμπίεσης πολύ υψηλά επίπεδα απώλειας δεν προσφέρουν τόσο κέρδος. Το εύρος των επιτρεπόμενων τιμών είναι [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλαπλών σελίδων. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel του GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση διαφορετικών κλάσεων από το Namespace SaveOptions για σκοπούς εξαγωγής. Μια εικόνα τύπου Psd φορτώνεται σε μια παρουσία της Image και στη συνέχεια εξάγεται σε διάφορες μορφές.

```csharp
[C#]

//Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Εξαγωγή σε μορφή αρχείου BMP χρησιμοποιώντας τις προεπιλεγμένες επιλογές.
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Εξαγωγή σε μορφή αρχείου JPEG χρησιμοποιώντας τις προεπιλεγμένες επιλογές.
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Εξαγωγή σε μορφή αρχείου JPEG 2000 χρησιμοποιώντας τις προεπιλεγμένες επιλογές.
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Εξαγωγή σε μορφή αρχείου PNG χρησιμοποιώντας τις προεπιλεγμένες επιλογές.
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Εξαγωγή σε μορφή αρχείου TIFF χρησιμοποιώντας τις προεπιλεγμένες επιλογές.
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


