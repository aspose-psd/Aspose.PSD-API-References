---
title: Class RasterCachedImage
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.RasterCachedImage τάξη. Αντιπροσωπεύει μια εικόνα ράστερ που υποστηρίζει λειτουργίες γραφικών ράστερ. Αυτή η εικόνα αποθηκεύει προσωρινά δεδομένα pixel όταν απαιτείται.
type: docs
weight: 5310
url: /el/net/aspose.psd/rastercachedimage/
---
## RasterCachedImage class

Αντιπροσωπεύει μια εικόνα ράστερ που υποστηρίζει λειτουργίες γραφικών ράστερ. Αυτή η εικόνα αποθηκεύει προσωρινά δεδομένα pixel όταν απαιτείται.

```csharp
public abstract class RasterCachedImage : RasterImage
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η παλέτα αυτόματης προσαρμογής. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τα bit της εικόνας ανά πλήθος pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Παίρνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το[`Image`](../image/) δοχείο. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή της μορφής αρχείου |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει άλφα. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτής[`RasterImage`](../rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Λαμβάνει αδιαφάνεια αυτής της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λήψη ή ρύθμιση της οθόνης διακοπής. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα εικόνας αποθηκεύονται προσωρινά. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν είναι διαθέσιμη η φόρτωση πρωτογενών δεδομένων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η χρωματική παλέτα δεν χρησιμοποιείται όταν τα εικονοστοιχεία αναπαρίστανται απευθείας. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να πολλαπλασιαστούν εκ των προτέρων. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Λαμβάνει τη μορφή πρωτογενών δεδομένων. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Λαμβάνει τις τρέχουσες ρυθμίσεις πρωτογενών δεδομένων. Σημείωση όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Λαμβάνει ή ορίζει το εφεδρικό ευρετήριο για χρήση όταν το ευρετήριο παλέτας είναι εκτός ορίων |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον μετατροπέα χρώματος με ευρετήριο |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Λαμβάνει το ακατέργαστο μέγεθος γραμμής σε byte. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Παίρνει την εικόνα διαφανές χρώμα. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερώσει τα μεταδεδομένα XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί φόρτωση πρωτογενών δεδομένων όταν είναι διαθέσιμη η φόρτωση πρωτογενών δεδομένων. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη ανάλυση, σε pixel ανά ίντσα, αυτής[`RasterImage`](../rasterimage/) . |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Προσαρμογή φωτεινότητας για την εικόνα. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Αντίθεση εικόνας |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | Διόρθωση γάμμα εικόνας. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | Διόρθωση γάμμα εικόνας. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Δυαδοποίηση μιας εικόνας χρησιμοποιώντας τον προσαρμοστικό αλγόριθμο κατωφλίου του Bradley χρησιμοποιώντας το ενσωματωμένο thresholding |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Δυαδοποίηση μιας εικόνας χρησιμοποιώντας τον προσαρμοστικό αλγόριθμο κατωφλίου του Bradley χρησιμοποιώντας το ενσωματωμένο thresholding |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Δυαδοποίηση εικόνας με προκαθορισμένο όριο |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Δυαδοποίηση εικόνας με thresholding Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Αποθηκεύει προσωρινά τα δεδομένα και διασφαλίζει ότι δεν θα πραγματοποιηθεί πρόσθετη φόρτωση δεδομένων από το υποκείμενο[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις περασμένες επιλογές αποθήκευσης. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | Περικοπή της εικόνας. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Περικοπή εικόνας με μετατοπίσεις. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Εκτελεί παραμόρφωση στην τρέχουσα εικόνα. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Εκτελεί παραμόρφωση στην τρέχουσα εικόνα. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Λαμβάνει μια εικόνα 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel ARGB 32-bit. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο πίνακα πρωτογενών δεδομένων. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων χρησιμοποιώντας μερικό φορτωτή εικονοστοιχείων. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Λαμβάνει την ημερομηνία και την ώρα της τελευταίας τροποποίησης της εικόνας του πόρου. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές με βάση τις ρυθμίσεις του αρχικού αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρήσουμε το βάθος bit και άλλες παραμέτρους της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, αν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια αποθηκεύστε το χρησιμοποιώντας το [`Save`](../datastreamsupporter/save/) Με τη μέθοδο, θα παραχθεί η εικόνα εξόδου PNG με 8 bit ανά pixel. Για να το αποφύγετε και να αποθηκεύσετε εικόνα PNG με 1 bit ανά pixel, χρησιμοποιήστε αυτήν τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και να τις μεταφέρετε στο[`Save`](../image/save/)μέθοδος ως δεύτερη παράμετρος. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Λαμβάνει ένα εικονοστοιχείο εικόνας. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Μεταμόρφωση μιας εικόνας στην αναπαράστασή της σε κλίμακα του γκρι |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Φορτώνει pixel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Φορτώνει pixel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Φορτώνει pixel σε μορφή CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Φορτώνει pixel ARGB 32-bit μερικώς ανά πακέτα. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Φορτώνει τα pixel μερικώς ανά πακέτα. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Φορτώνει pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για να απαλλαγούμε από τη λοξή σάρωση. Αυτή η μέθοδος χρησιμοποιεί[`GetSkewAngle`](../rasterimage/getskewangle/) και[`Rotate`](../rasterimage/rotate/) μέθοδοι. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για να απαλλαγούμε από τη λοξή σάρωση. Αυτή η μέθοδος χρησιμοποιεί[`GetSkewAngle`](../rasterimage/getskewangle/) και[`Rotate`](../rasterimage/rotate/) μέθοδοι. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης από το καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης από το καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Αντικαθιστά το ένα χρώμα στο άλλο με την επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Αντικαθιστά το ένα χρώμα στο άλλο με την επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Περιστροφή εικόνας γύρω από το κέντρο. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | Περιστροφή εικόνας γύρω από το κέντρο. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στην υποκείμενη ροή. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Αποθηκεύει τα εικονοστοιχεία ARGB 32-bit. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Αποθηκεύει τα pixel. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Αποθηκεύει τα pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Αποθηκεύει τα πρωτογενή δεδομένα. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ορίζει μια εικόνα 32-bit ARGB pixel για την καθορισμένη θέση. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα εικόνων. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ορίζει ένα εικονοστοιχείο εικόνας για την καθορισμένη θέση. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ορίζει την ανάλυση για αυτό[`RasterImage`](../rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Μετατρέπει την εικόνα ράστερ στο bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Εγγράφει ολόκληρη τη γραμμή σάρωσης στο καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Εγγράφει ολόκληρη τη γραμμή σάρωσης στο καθορισμένο ευρετήριο γραμμής σάρωσης. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα περικοπής της εικόνας ανά συγκεκριμένο ορθογώνιο.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Αποθήκευση psd
    image.Save(exportPath, new PsdOptions());

    // Αποθήκευση png
    image.Save(exportPathPng, new PngOptions());
}
```

### Δείτε επίσης

* class [RasterImage](../rasterimage/)
* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


