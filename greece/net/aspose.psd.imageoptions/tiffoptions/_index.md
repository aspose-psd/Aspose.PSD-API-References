---
title: "Κλάση TiffOptions"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageOptions.TiffOptions κλάση. Οι επιλογές μορφής αρχείου tiff. Σημειώστε ότι οι ετικέτες width και height θα αντικατασταθούν κατά τη δημιουργία της εικόνας από τις παραμέτρους width και height, οπότε δεν υπάρχει ανάγκη να τις καθορίσετε άμεσα. Σημειώστε ότι πολλές επιλογές επιστρέφουν μια προεπιλεγμένη τιμή, αλλά αυτό δεν σημαίνει ότι αυτή η επιλογή έχει οριστεί ρητά ως τιμή ετικέτας. Για να επαληθεύσετε ότι η ετικέτα υπάρχει, χρησιμοποιήστε την ιδιότητα Tags ή τη αντίστοιχη μέθοδο IsTagPresent."
type: docs
weight: 5430
url: /el/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Οι επιλογές μορφής αρχείου tiff. Σημειώστε ότι οι ετικέτες πλάτους και ύψους θα αντικατασταθούν κατά τη δημιουργία της εικόνας από τις παραμέτρους πλάτους και ύψους, οπότε δεν υπάρχει ανάγκη να τις καθορίσετε άμεσα. Σημειώστε ότι πολλές επιλογές επιστρέφουν μια προεπιλεγμένη τιμή, αλλά αυτό δεν σημαίνει ότι αυτή η επιλογή έχει οριστεί ρητά ως τιμή ετικέτας. Για να επαληθεύσετε ότι η ετικέτα υπάρχει, χρησιμοποιήστε την ιδιότητα Tags ή τη σχετική μέθοδο IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TiffOptions`. Από προεπιλογή χρησιμοποιείται η συμβατική little endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `TiffOptions`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης alpha. Επιλογές εκτός του Unspecified χρησιμοποιούνται όταν ορίζονται περισσότερα από 3 [`SamplesPerPixel`](./samplesperpixel/). |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Λαμβάνει τα bits ανά pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Λαμβάνει ή ορίζει τα bits ανά δείγμα. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Λαμβάνει ή ορίζει το χάρτη χρωμάτων. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Λαμβάνει ή ορίζει την ποιότητα συμπιεσμένης εικόνας. Χρησιμοποιείται με τη συμπίεση Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Λαμβάνει ή ορίζει τη συμπίεση. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Λαμβάνει ή ορίζει το δικαίωμα πνευματικής ιδιοκτησίας. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Λαμβάνει ή ορίζει την ημερομηνία και ώρα. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του εγγράφου. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Λαμβάνει ή ορίζει τον δείκτη στο EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bit του byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Λαμβάνει ή ορίζει τις υποδείξεις ημιτονοειδούς. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Λαμβάνει ή ορίζει τη ροή προφίλ Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Λαμβάνει ή ορίζει τα ονόματα μελανιού. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν υπάρχουν επιπλέον δείγματα. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι πλακιδική. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν οι `TiffOptions` έχουν ρυθμιστεί σωστά. Χρησιμοποιήστε τη μέθοδο Validate για να βρείτε τον λόγο αποτυχίας. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλαπλών σελίδων. |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Λαμβάνει ή ορίζει το όνομα της σελίδας. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Λαμβάνει ή ορίζει το φωτομετρικό. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Λαμβάνει ή ορίζει τον πρόβλεπτη για τη συμπίεση LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία πρέπει να προπολλαπλασιαστούν. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Λαμβάνει ή ορίζει τις γραμμές ανά ταινία. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Λαμβάνει ή ορίζει τη μορφή δείγματος. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Λαμβάνει τα δείγματα ανά εικονοστοιχείο. Για να αλλάξετε αυτήν την τιμή ιδιότητας χρησιμοποιήστε τον οριστή ιδιότητας [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Λαμβάνει ή ορίζει το μοντέλο του σαρωτή. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα με τα δεδομένα δείγματος (τύπος Byte, Short ή Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο λογισμικού. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Λαμβάνει ή ορίζει τις μετρήσεις byte της ταινίας. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Λαμβάνει ή ορίζει τις μετατοπίσεις της ταινίας. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Λαμβάνει ή ορίζει τις ετικέτες. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Λαμβάνει ή ορίζει το κατώφλι. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Λαμβάνει ot ορίζει το μήκος του πλακιδίου. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Λαμβάνει ot ορίζει το πλάτος του πλακιδίου. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Λαμβάνει τις συνολικές σελίδες. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Λαμβάνει τον έγκυρο αριθμό ετικετών. Αυτό δεν είναι ο συνολικός αριθμός ετικετών αλλά ο αριθμός των ετικετών που μπορεί να διατηρηθεί. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Λαμβάνει ή ορίζει τον δημιουργό της εικόνας, που χρησιμοποιείται από τον Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Λαμβάνει ή ορίζει το σχόλιο στην εικόνα, που χρησιμοποιείται από τον Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Λαμβάνει ή ορίζει το θέμα της εικόνας, που χρησιμοποιείται από τον Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Λαμβάνει ή ορίζει τη θέση x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την image, η οποία χρησιμοποιείται από το Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την image, η οποία χρησιμοποιείται από το Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Λαμβάνει ή ορίζει τα YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το YCbCr photometric. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Λαμβάνει ή ορίζει τη θέση y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση y. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Προσθέτει μια νέα ετικέτα. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Προσθέτει τις ετικέτες. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Λαμβάνει το στιγμιότυπο της ετικέτας ανά τύπο. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Καθορίζει αν η ετικέτα υπάρχει στις επιλογές ή όχι. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Αφαιρεί την ετικέτα. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Επικυρώνει εάν οι επιλογές έχουν έγκυρο συνδυασμό ετικετών |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Λαμβάνει τον αριθμό των έγκυρων ετικετών. |

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

Αυτά τα παραδείγματα χρησιμοποιούν τις κλάσεις GraphicsPath και Graphics για τη δημιουργία και τη διαχείριση Σχημάτων σε μια επιφάνεια Image. Το παράδειγμα δημιουργεί μια νέα Image και σχεδιάζει διαδρομές με τη βοήθεια της κλάσης GraphicsPath. Στο τέλος, η μέθοδος DrawPath που εκτίθεται από την κλάση Graphics καλείται για την απόδοση των διαδρομών στην επιφάνεια. Τέλος, η εικόνα εξάγεται σε μορφή αρχείου Tiff.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του Image 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργήστε και αρχικοποιήστε ένα στιγμιότυπο της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Καθαρίστε την επιφάνεια Graphics
    graphics.Clear(Color.Wheat);

    //Δημιουργήστε ένα στιγμιότυπο της κλάσης GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Δημιουργήστε ένα στιγμιότυπο της κλάσης Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Προσθέστε Σχήματα στο αντικείμενο Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Προσθέστε το αντικείμενο Figure στο GraphicsPath
    graphicspath.AddFigure(figure);

    //Σχεδιάστε τη διαδρομή με το αντικείμενο Pen χρώματος Black
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Δημιουργήστε ένα στιγμιότυπο του TiffOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // αποθηκεύστε όλες τις αλλαγές.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


