---
title: Class JpegOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageOptions.JpegOptions τάξη. Η μορφή αρχείου jpeg δημιουργεί επιλογές.
type: docs
weight: 4840
url: /el/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Η μορφή αρχείου jpeg δημιουργεί επιλογές.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`JpegOptions` τάξη. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Αρχικοποιεί μια νέα παρουσία του`JpegOptions` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Λαμβάνει ή ορίζει bit ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bit ανά κανάλι. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Το προφίλ χρώματος CMYK προορισμού για εικόνες CMYK jpeg. Χρήση για αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το RGBColorProfile για σωστή μετατροπή χρώματος. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο χρώματος για την εικόνα jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο του αρχείου jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμπίεσης. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Λήψη ή ρύθμιση exif data container |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Λαμβάνει ή ορίζει τις οριζόντιες υποδειγματοληψίες για κάθε στοιχείο. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Λαμβάνει ή ορίζει το jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Λαμβάνει ή ρυθμίζει τη διαφορά JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία παρεμβολής JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Λαμβάνει ή ορίζει τις προκαθορισμένες παραμέτρους JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλών σελίδων |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε στοιχεία πρέπει να αναμειχθούν με χρώμα φόντου, εάν υπάρχει κανάλι άλφα. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Λαμβάνει ή ρυθμίζει την ποιότητα εικόνας. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις βελτιστοποίησης RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Το προφίλ χρώματος RGB προορισμού για εικόνες CMYK jpeg. Χρήση για αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το CMYKColorProfile για σωστή μετατροπή χρώματος. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία στρογγυλοποίησης δείγματος ώστε να ταιριάζει μια τιμή 8-bit σε μια τιμή n-bit.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Η κλιμακούμενη ποιότητα. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής ραστεροποίησης. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Λαμβάνει ή ορίζει τις κάθετες υποδειγματοληψίες για κάθε στοιχείο. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το κοντέινερ μεταδεδομένων XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

Αυτό το παράδειγμα δείχνει τη χρήση του Aspose.PSD για .Net API για τη μετατροπή Εικόνων σε μορφή Jpeg. Για να επιτευχθεί αυτός ο στόχος, αυτό το παράδειγμα φορτώνει μια υπάρχουσα εικόνα και στη συνέχεια τη μετατρέπει σε μορφή αρχείου Jpeg.

```csharp
[C#]

//Δημιουργεί μια παρουσία κλάσης εικόνας και την προετοιμάζει με ένα υπάρχον αρχείο μέσω της διαδρομής αρχείου
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Δημιουργήστε μια παρουσία της κλάσης PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Ρυθμίστε την ποιότητα στο 50% σε μικρότερο μέγεθος της εικόνας εξόδου.
    jpegOptions.Quality = 50;

    //Ρυθμίστε τα σχόλια exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Αποθηκεύστε την εικόνα στη θέση του δίσκου με τις παρεχόμενες ρυθμίσεις JpegOptions
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Αυτό το παράδειγμα δείχνει τη χρήση του System.IO.Stream για τη δημιουργία ενός νέου αρχείου εικόνας

```csharp
[C#]

//Δημιουργεί μια παρουσία του PsdOptions και ορίζει τις διάφορες ιδιότητές του
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Δημιουργήστε μια παρουσία του System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Ορίστε την ιδιότητα προέλευσης για την παρουσία του PsdOptions
//Η δεύτερη δυαδική παράμετρος καθορίζει εάν η ροή απορρίπτεται μόλις βγει από το πεδίο εφαρμογής
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Δημιουργεί μια παρουσία της εικόνας και καλεί τη μέθοδο Create με το PsdOptions ως παράμετρο για την προετοιμασία του αντικειμένου εικόνας   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Κάνε κάποια επεξεργασία εικόνας
}
```

Αυτό το παράδειγμα δείχνει τη χρήση διαφορετικών κλάσεων από το SaveOptions Namespace για σκοπούς εξαγωγής. Μια εικόνα τύπου Psd φορτώνεται σε μια παρουσία της εικόνας και στη συνέχεια εξάγεται σε διάφορες μορφές.

```csharp
[C#]

//Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Εξαγωγή σε μορφή αρχείου BMP χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Εξαγωγή σε μορφή αρχείου JPEG χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Εξαγωγή σε μορφή αρχείου JPEG 2000 χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Εξαγωγή σε μορφή αρχείου PNG χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Εξαγωγή σε μορφή αρχείου TIFF χρησιμοποιώντας τις προεπιλεγμένες επιλογές
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* χώρος ονομάτων [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* συνέλευση [Aspose.PSD](../../)


