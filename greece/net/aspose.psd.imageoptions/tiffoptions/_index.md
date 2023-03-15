---
title: Class TiffOptions
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageOptions.TiffOptions τάξη. Οι επιλογές μορφής αρχείου tiff. Σημειώστε ότι οι ετικέτες πλάτους και ύψους θα αντικατασταθούν κατά τη δημιουργία εικόνας από παραμέτρους πλάτους και ύψους επομένως δεν χρειάζεται να τις προσδιορίσετε απευθείας. Σημειώστε ότι πολλές επιλογές επιστρέφουν μια προεπιλεγμένη τιμή αλλά αυτό δεν σημαίνει ότι αυτή η επιλογή ορίζεται ρητά ως τιμή ετικέτας. Για να επαληθεύσετε την ύπαρξη της ετικέτας χρησιμοποιήστε την ιδιότητα Tags ή την αντίστοιχη μέθοδο IsTagPresent.
type: docs
weight: 4940
url: /el/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Οι επιλογές μορφής αρχείου tiff. Σημειώστε ότι οι ετικέτες πλάτους και ύψους θα αντικατασταθούν κατά τη δημιουργία εικόνας από παραμέτρους πλάτους και ύψους, επομένως δεν χρειάζεται να τις προσδιορίσετε απευθείας. Σημειώστε ότι πολλές επιλογές επιστρέφουν μια προεπιλεγμένη τιμή, αλλά αυτό δεν σημαίνει ότι αυτή η επιλογή ορίζεται ρητά ως τιμή ετικέτας. Για να επαληθεύσετε την ύπαρξη της ετικέτας χρησιμοποιήστε την ιδιότητα Tags ή την αντίστοιχη μέθοδο IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Αρχικοποιεί μια νέα παρουσία του`TiffOptions` τάξη. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Αρχικοποιεί μια νέα παρουσία του`TiffOptions` τάξη. Από προεπιλογή χρησιμοποιείται μικρή σύμβαση endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Αρχικοποιεί μια νέα παρουσία του`TiffOptions` τάξη. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Αρχικοποιεί μια νέα παρουσία του`TiffOptions` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης alpha. Επιλογές εκτός απόUnspecified Τα χρησιμοποιούνται όταν είναι περισσότερα από 3[`SamplesPerPixel`](./samplesperpixel/) ορίζεται. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Παίρνει ή ρυθμίζει τον καλλιτέχνη. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Λαμβάνει τα bit ανά pixel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Λαμβάνει ή ορίζει τα bit ανά δείγμα. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά tiff byte. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Λαμβάνει ή ορίζει τον χρωματικό χάρτη. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Λαμβάνει ή ρυθμίζει την ποιότητα συμπιεσμένης εικόνας. Χρησιμοποιείται με τη συμπίεση Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Λαμβάνει ή ρυθμίζει τη συμπίεση. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Αποκτά ή ορίζει τα πνευματικά δικαιώματα. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Λαμβάνει ή ορίζει την ημερομηνία και την ώρα. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Λαμβάνει ή ορίζει την προεπιλεγμένη γραμματοσειρά αντικατάστασης (γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε ράστερ, εάν η υπάρχουσα γραμματοσειρά επιπέδου στο αρχείο PSD δεν εμφανίζεται στο σύστημα). Για να λάβετε το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορείτε να χρησιμοποιήσετε το επόμενο απόσπασμα κώδικα : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] οικογένειες = col.Families; stringN defaultFont; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του εγγράφου. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Λαμβάνει ή ορίζει τον δείκτη σε EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές φαξ t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Λαμβάνει ή ορίζει τη σειρά πλήρωσης των bit byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Λαμβάνει ή ορίζει τις ημίτονο υποδείξεις. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Λαμβάνει ή ρυθμίζει τη ροή προφίλ Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Λαμβάνει ή ορίζει τα ονόματα μελανιών. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν υπάρχουν τα επιπλέον δείγματα. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι πλακιδίων. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν το`TiffOptions` έχουν ρυθμιστεί σωστά. Χρησιμοποιήστε τη μέθοδο επικύρωσης για να βρείτε την αιτία αποτυχίας. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει την ελάχιστη τιμή δείγματος. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Οι επιλογές πολλών σελίδων |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Λαμβάνει ή ορίζει το όνομα της σελίδας. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Λαμβάνει ή ρυθμίζει το φωτομετρικό. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Λαμβάνει ή ορίζει την επίπεδη διαμόρφωση. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Λαμβάνει ή ορίζει τον προγνωστικό παράγοντα για συμπίεση LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία πρέπει να πολλαπλασιαστούν εκ των προτέρων. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων προόδου. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Λαμβάνει ή ορίζει τις σειρές ανά λωρίδα. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Λαμβάνει ή ορίζει τη μορφή δείγματος. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Λαμβάνει τα δείγματα ανά pixel. Για να αλλάξετε αυτήν την τιμή ιδιότητας χρησιμοποιήστε το[`BitsPerSample`](./bitspersample/) ρυθμιστής ιδιοτήτων. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Λήψη ή ρύθμιση του κατασκευαστή του σαρωτή. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Λήψη ή ρύθμιση του μοντέλου σαρωτή. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. Η τιμή έχει έναν τύπο πεδίου που ταιριάζει καλύτερα με τα δείγματα δεδομένων (τύπος Byte, Short ή Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Λαμβάνει ή ορίζει την ελάχιστη τιμή δείγματος. Η τιμή έχει έναν τύπο πεδίου που ταιριάζει καλύτερα με τα δείγματα δεδομένων (τύπος Byte, Short ή Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο λογισμικού. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία εικόνας. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Λαμβάνει ή ορίζει τις μετρήσεις των byte της ταινίας. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Λαμβάνει ή ορίζει τις μετατοπίσεις της ταινίας. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Λαμβάνει ή ορίζει μια γενική ένδειξη του είδους των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Λαμβάνει ή ορίζει τις ετικέτες. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Λαμβάνει ή ορίζει το όριο. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Λαμβάνει ή ορίζει τις μετρήσεις των byte πλακιδίων. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Λαμβάνει το μήκος πλακιδίων. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Λαμβάνει ή ορίζει τις μετατοπίσεις πλακιδίων. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Λαμβάνει ot ορίζει το πλάτος πλακιδίων. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Λαμβάνει τις συνολικές σελίδες. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Λαμβάνει τον έγκυρο αριθμό ετικετών. Αυτό δεν είναι ο συνολικός αριθμός ετικετών αλλά ο αριθμός των ετικετών που μπορούν να διατηρηθούν. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής ραστεροποίησης. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει το κοντέινερ μεταδεδομένων XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Λαμβάνει ή ορίζει τον συγγραφέα εικόνας, που χρησιμοποιείται από την Εξερεύνηση των Windows. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Λαμβάνει ή ορίζει σχόλια σε εικόνα, που χρησιμοποιείται από την Εξερεύνηση των Windows. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Λαμβάνει ή ορίζει εικόνα θέματος, η οποία χρησιμοποιείται από την Εξερεύνηση των Windows. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Λαμβάνει ή ορίζει τη θέση x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την εικόνα που χρησιμοποιείται από την Εξερεύνηση των Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την εικόνα που χρησιμοποιείται από την Εξερεύνηση των Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Λαμβάνει ή ορίζει τους συντελεστές YCbCr. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Λαμβάνει ή ορίζει τους συντελεστές υποδειγματοληψίας για το φωτομετρικό YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Λαμβάνει ή ορίζει τη θέση y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση y. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Προσθέτει μια νέα ετικέτα. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Προσθέτει τις ετικέτες. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Κλωνοποιεί αυτήν την παρουσία. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Λαμβάνει την παρουσία της ετικέτας ανά τύπο. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Καθορίζει εάν υπάρχει ετικέτα στις επιλογές ή όχι. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Αφαιρεί την ετικέτα. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Επικυρώνει εάν οι επιλογές έχουν έγκυρο συνδυασμό ετικετών |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Λαμβάνει τον έγκυρο αριθμό ετικετών. |

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

Αυτά τα παραδείγματα χρησιμοποιούν την κλάση GraphicsPath και Graphics για τη δημιουργία και τον χειρισμό Φιγούρων σε μια επιφάνεια εικόνας. Το Example δημιουργεί μια νέα εικόνα και σχεδιάζει μονοπάτια με τη βοήθεια της κλάσης GraphicsPath. Στο τέλος η μέθοδος DrawPath που εκτίθεται από την κλάση Graphics καλείται να αποδώσει τα μονοπάτια στην επιφάνεια. Τέλος, η εικόνα εξάγεται σε μορφή αρχείου Tiff.

```csharp
[C#]

//Δημιουργία μιας παρουσίας εικόνας 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Δημιουργία και προετοιμασία μιας παρουσίας της κλάσης Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Διαγραφή επιφάνειας γραφικών
    graphics.Clear(Color.Wheat);

    //Δημιουργήστε μια παρουσία της κλάσης GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Δημιουργήστε μια παρουσία της κλάσης Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Προσθήκη σχημάτων στο αντικείμενο Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Προσθήκη αντικειμένου Figure στο GraphicsPath
    graphicspath.AddFigure(figure);

    //Σχεδίαση διαδρομής με αντικείμενο στυλό χρώματος Μαύρο
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Δημιουργήστε μια παρουσία του TiffOptions και ορίστε τις διάφορες ιδιότητές του
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // αποθήκευση όλων των αλλαγών.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Δείτε επίσης

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* χώρος ονομάτων [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* συνέλευση [Aspose.PSD](../../)


