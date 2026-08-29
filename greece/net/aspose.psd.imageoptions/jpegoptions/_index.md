---
title: "Κλάση JpegOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageOptions.JpegOptions κλάση. Οι επιλογές δημιουργίας μορφής αρχείου jpeg"
type: docs
weight: 5330
url: /el/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

Οι επιλογές δημιουργίας μορφής αρχείου jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Αρχικοποιεί μια νέα παρουσία της κλάσης `JpegOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Το προορισμένο προφίλ χρώματος CMYK για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το RGBColorProfile για σωστή μετατροπή χρώματος. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο χρώματος για εικόνα jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο αρχείου jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμπίεσης. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Λάβετε ή ορίστε το δοχείο δεδομένων exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Λαμβάνει ή ορίζει τις οριζόντιες υποδειγματοληψίες για κάθε στοιχείο. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Λαμβάνει ή ορίζει το jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Λαμβάνει ή ορίζει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία διαπλέγματος JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Λαμβάνει ή ορίζει τις προρυθμισμένες παραμέτρους JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλαπλών σελίδων. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Λαμβάνει ή ορίζει την ποιότητα της εικόνας. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις του βελτιστοποιητή RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Το προορισμένο προφίλ χρώματος RGB για εικόνες JPEG CMYK. Χρησιμοποιείται για την αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το CMYKColorProfile για σωστή μετατροπή χρώματος. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης του δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Η κλιμακωμένη ποιότητα. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Λαμβάνει ή ορίζει τις κάθετες υποδειγματοληψίες για κάθε συστατικό. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του Aspose.PSD για .Net API για τη μετατροπή εικόνων σε μορφή JPEG. Για να επιτευχθεί αυτό, το παράδειγμα φορτώνει μια υπάρχουσα εικόνα και στη συνέχεια τη μετατρέπει σε μορφή αρχείου JPEG.

```csharp
[C#]

//Δημιουργεί μια παρουσία της κλάσης image και την αρχικοποιεί με ένα υπάρχον αρχείο μέσω της διαδρομής αρχείου.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Δημιουργήστε μια παρουσία της κλάσης PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Ορίστε την ποιότητα στο 50% για να μειώσετε το μέγεθος της εξαγόμενης εικόνας.
    jpegOptions.Quality = 50;

    //Ορίστε τα σχόλια exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Αποθηκεύστε την εικόνα σε τοποθεσία δίσκου με τις παρεχόμενες ρυθμίσεις JpegOptions.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Αυτό το παράδειγμα δείχνει τη χρήση του System.IO.Stream για τη δημιουργία ενός νέου αρχείου Image.

```csharp
[C#]

//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Ορίστε την ιδιότητα source για την παρουσία του PsdOptions.
//Η δεύτερη παράμετρος boolean καθορίζει εάν το Stream θα απελευθερωθεί μόλις βγει εκτός εμβέλειας.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Δημιουργεί μια παρουσία του Image και καλεί τη μέθοδο Create με το PsdOptions ως παράμετρο για την αρχικοποίηση του αντικειμένου Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //κάντε κάποια επεξεργασία εικόνας
}
```

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


