---
title: "Κλάση RasterImage"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.RasterImage. Αντιπροσωπεύει μια ραστερ εικόνα που υποστηρίζει λειτουργίες ραστερ γραφικών"
type: docs
weight: 5820
url: /el/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

Αναπαριστά μια raster εικόνα που υποστηρίζει λειτουργίες raster γραφικών.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν γίνεται αυτόματη προσαρμογή παλέτας. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Λαμβάνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το κοντέινερ [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Λαμβάνει μια τιμή μορφής αρχείου |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει άλφα. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του `RasterImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να είναι προπολλαπλασιασμένα. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ανακτά ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ανακτά ή ορίζει τον μετατροπέα χρωμάτων με δείκτη |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Λαμβάνει το μέγεθος της ακατέργαστης γραμμής σε byte. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η παλέτα της εικόνας. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του `RasterImage`. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Ανακτά ή ορίζει τα μεταδεδομένα XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Ρύθμιση της φωτεινότητας για την εικόνα. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Αντίθεση εικόνας |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Διόρθωση γάμμα μιας εικόνας. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Διόρθωση γάμμα μιας εικόνας. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Κόβει το καθορισμένο ορθογώνιο. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Περικοπή εικόνας με μετατοπίσεις. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθεί το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά εικονοστοιχείο και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο [`Save`](../datastreamsupporter/save/), θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά εικονοστοιχείο. Για να το αποφύγουμε και να αποθηκεύσουμε την PNG εικόνα με 1-bit ανά εικονοστοιχείο, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο [`Save`](../image/save/) ως δεύτερη παράμετρο. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Λαμβάνει ένα pixel εικόνας. Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης. Για πιο αποδοτική διαχείριση pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Μετασχηματισμός μιας εικόνας στην γκρι κλίμακα της |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 32-bit ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 64-bit ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία σε μορφή CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Φορτώνει pixel σε μορφή CMYK. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`LoadCmyk32Pixels`](./loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Φορτώνει εικονοστοιχεία 32-bit ARGB μερικώς ανά πακέτα. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Φορτώνει εικονοστοιχεία μερικώς ανά πακέτα. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Φορτώνει εικονοστοιχεία. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της παραμορφωμένης σάρωσης. Η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](./getskewangle/) και [`Rotate`](./rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της παραμορφωμένης σάρωσης. Η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](./getskewangle/) και [`Rotate`](./rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας με επεκταμένες επιλογές. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Αλλάζει το πλάτος αναλογικά. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Αλλάζει το πλάτος αναλογικά. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Αποθηκεύει τα 32-bit ARGB pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Αποθηκεύει τα pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Αποθηκεύει τα pixel. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`SaveCmyk32Pixels`](./savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Αποθηκεύει τα pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα της εικόνας. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ορίζει το pixel της εικόνας για τη συγκεκριμένη θέση. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ορίζει την ανάλυση για αυτό το `RasterImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Μετατρέπει την raster εικόνα σε bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να φορτώνει πληροφορίες Pixel σε έναν Πίνακα τύπου Color, να επεξεργάζεται τον πίνακα και να τον επαναφέρει στην εικόνα. Για την εκτέλεση αυτών των λειτουργιών, αυτό το παράδειγμα δημιουργεί ένα νέο αρχείο Image (σε μορφή PSD) χρησιμοποιώντας το αντικείμενο MemoryStream.

```csharp
[C#]

//Δημιουργήστε ένα στιγμιότυπο του MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Δημιουργήστε ένα στιγμιότυπο του PsdOptions και ορίστε τις διάφορες ιδιότητές του, συμπεριλαμβανομένης της ιδιότητας Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Δημιουργήστε ένα στιγμιότυπο του Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Αποκτήστε τα pixel της εικόνας καθορίζοντας την περιοχή ως όριο της εικόνας
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Επανάληψη πάνω στον πίνακα και ορίζει το χρώμα του εναλλακτικού ευρετηριασμένου pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε κίτρινο
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Ορίστε το χρώμα του ευρετηριασμένου pixel σε μπλε
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Εφαρμόστε τις αλλαγές pixel στην εικόνα
        image.SavePixels(image.Bounds, pixels);

        // αποθηκεύστε όλες τις αλλαγές.
        image.Save();
    }

    //Γράψτε το MemoryStream σε αρχείο
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Δείτε επίσης

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


