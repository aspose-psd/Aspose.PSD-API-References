---
title: Class BmpOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageOptions.BmpOptions τάξη. Οι επιλογές δημιουργίας μορφής αρχείου bmp.
type: docs
weight: 4790
url: /el/net/aspose.psd.imageoptions/bmpoptions/
---
## BmpOptions class

Οι επιλογές δημιουργίας μορφής αρχείου bmp.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`BmpOptions` τάξη. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | Αρχικοποιεί μια νέα παρουσία του`BmpOptions` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BitsPerPixel](../../aspose.psd.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | Λαμβάνει ή ορίζει τα bits εικόνας ανά πλήθος pixel. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [Compression](../../aspose.psd.imageoptions/bmpoptions/compression/) { get; set; } | Λαμβάνει ή ρυθμίζει τη συμπίεση. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλών σελίδων |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία εικόνας. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής ραστεροποίησης. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το κοντέινερ μεταδεδομένων XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |

### Παραδείγματα

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


