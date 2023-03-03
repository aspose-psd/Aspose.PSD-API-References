---
title: Class PsdImage
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.PsdImage τάξη. Καθορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης επεξεργασίας αποθήκευσης αρχείων PSD καθώς και ιδιοτήτων ενημέρωσης  προσθήκης υδατογραφημάτων εκτέλεσης λειτουργιών γραφικών ή μετατροπής μιας μορφής αρχείου σε άλλη. Το Aspose.PSD υποστηρίζει εισαγωγή ως επίπεδο και εξαγωγή στο παρακάτω μορφές Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb μαζί με εξαγωγή σε Pdf με επιλέξιμο κείμενο
type: docs
weight: 3590
url: /el/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Καθορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης, επεξεργασίας, αποθήκευσης αρχείων PSD καθώς και ιδιοτήτων ενημέρωσης , προσθήκης υδατογραφημάτων, εκτέλεσης λειτουργιών γραφικών ή μετατροπής μιας μορφής αρχείου σε άλλη. Το Aspose.PSD υποστηρίζει εισαγωγή ως επίπεδο και εξαγωγή στο παρακάτω μορφές: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb μαζί με εξαγωγή σε Pdf με επιλέξιμο κείμενο

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Αρχικοποιεί μια νέα παρουσία του`PsdImage`κλάση από υπάρχουσα εικόνα ράστερ (όχι εικόνα psd) με λειτουργία χρώματος RGB με 4 κανάλια 8 bit/κανάλι και χωρίς συμπίεση. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd σε ροή). Χρησιμοποιείται για την προετοιμασία της εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, συμπίεση - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd στη διαδρομή). Χρησιμοποιείται για την προετοιμασία της εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, συμπίεση - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κατηγορία με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την προετοιμασία της άδειας εικόνας psd. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση από υπάρχουσα εικόνα ράστερ (όχι εικόνα psd) με παραμέτρους κατασκευαστή. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd σε ροή) με παραμέτρους κατασκευαστή. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση από καθορισμένη διαδρομή από εικόνα ράστερ (όχι εικόνα psd στη διαδρομή) με παραμέτρους κατασκευαστή. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί μια νέα παρουσία του`PsdImage` κλάση με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, πλήθος καναλιών και μήκος bit καναλιών και καθορισμένες παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την προετοιμασία της άδειας εικόνας psd. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Λαμβάνει ή ορίζει το ενεργό επίπεδο. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η παλέτα αυτόματης προσαρμογής. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Λαμβάνει τα bit ανά κανάλι. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Λαμβάνει τα bit της εικόνας ανά πλήθος pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Παίρνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffer. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Λαμβάνει τον αριθμό των καναλιών PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το RgbColorProfile για σωστή μετατροπή χρώματος. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία χρώματος. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Λαμβάνει τη μέθοδο συμπίεσης. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το[`Image`](../../aspose.psd/image/) δοχείο. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διατεθεί. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Λαμβάνει μια τιμή της μορφής αρχείου |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Λαμβάνει ή ορίζει την καθολική γωνία. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Λαμβάνει τις πληροφορίες μάσκας καθολικού επιπέδου. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Λαμβάνει ή ορίζει τους πόρους του καθολικού επιπέδου. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος ΓΚΡΙ (μονόχρωμο) για εικόνες PSD σε κλίμακα του γκρι. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Λαμβάνει ή ορίζει την κατακόρυφη ανάλυση, σε pixel ανά ίντσα, αυτής[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα κατά τον καθορισμό δεδομένων επιπέδων. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτής`PsdImage` . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Λαμβάνει αδιαφάνεια αυτής της εικόνας. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Λαμβάνει ή ορίζει τους πόρους εικόνας PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λήψη ή ρύθμιση της οθόνης διακοπής. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα εικόνας αποθηκεύονται προσωρινά. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα psd είναι ισοπεδωμένη. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν είναι διαθέσιμη η φόρτωση πρωτογενών δεδομένων. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Λαμβάνει ή ορίζει τα επίπεδα PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Λαμβάνει τον διαχειριστή συνδεδεμένων επιπέδων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η χρωματική παλέτα δεν χρησιμοποιείται όταν τα εικονοστοιχεία αναπαρίστανται απευθείας. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να πολλαπλασιαστούν εκ των προτέρων. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Λαμβάνει τη μορφή πρωτογενών δεδομένων. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Λαμβάνει τις τρέχουσες ρυθμίσεις πρωτογενών δεδομένων. Σημείωση όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Λαμβάνει ή ορίζει το εφεδρικό ευρετήριο για χρήση όταν το ευρετήριο παλέτας είναι εκτός ορίων |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον μετατροπέα χρώματος με ευρετήριο |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Λαμβάνει το ακατέργαστο μέγεθος γραμμής σε byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το CmykColorProfile για σωστή μετατροπή χρώματος. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Αποκτά τον πάροχο έξυπνων αντικειμένων. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Παίρνει την εικόνα διαφανές χρώμα. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερώσει τα μεταδεδομένα XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί φόρτωση πρωτογενών δεδομένων όταν είναι διαθέσιμη η φόρτωση πρωτογενών δεδομένων. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Λαμβάνει ή ορίζει την κατακόρυφη ανάλυση, σε pixel ανά ίντσα, αυτής`PsdImage` . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Προσθέτει το μαύρο λευκό επίπεδο προσαρμογής. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Προσθέτει το επίπεδο ρύθμισης φωτεινότητας/αντίθεσης. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής μείκτη καναλιών με προεπιλεγμένες παραμέτρους |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Προσθέτει το επίπεδο ρύθμισης ισορροπίας χρωμάτων. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής καμπυλών. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Προσθέτει το επίπεδο προσαρμογής έκθεσης. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Προσθέτει το επίπεδο ρύθμισης απόχρωσης/κορεσμού. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Προσθέτει ένα επίπεδο προσαρμογής αντιστροφής. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Προσθέτει το επίπεδο. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Προσθέτει την ομάδα επιπέδων. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής των επιπέδων. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Προσθέτει το επίπεδο PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Προσθέτει ένα νέο κανονικό επίπεδο. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Προσθέτει ένα νέο επίπεδο κειμένου. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής Vibrance. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Προσαρμογή φωτεινότητας για την εικόνα. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Αντίθεση εικόνας |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Διόρθωση γάμμα εικόνας. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Διόρθωση γάμμα εικόνας. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Δυαδοποίηση μιας εικόνας χρησιμοποιώντας τον προσαρμοστικό αλγόριθμο κατωφλίου του Bradley χρησιμοποιώντας το ενσωματωμένο thresholding |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Δυαδοποίηση μιας εικόνας χρησιμοποιώντας τον προσαρμοστικό αλγόριθμο κατωφλίου του Bradley χρησιμοποιώντας το ενσωματωμένο thresholding |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Δυαδοποίηση εικόνας με προκαθορισμένο όριο |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Δυαδοποίηση εικόνας με thresholding Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Αποθηκεύει προσωρινά τα δεδομένα και διασφαλίζει ότι δεν θα πραγματοποιηθεί πρόσθετη φόρτωση δεδομένων από το υποκείμενο[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις περασμένες επιλογές αποθήκευσης. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Μετατρέπει αυτήν τη μορφή εικόνας σε αυτήν που καθορίζεται στις επιλογές. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Περικοπή της εικόνας. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Περικοπή εικόνας με μετατοπίσεις. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Διαθέτει την τρέχουσα παρουσία. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Εκτελεί παραμόρφωση στην τρέχουσα εικόνα. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Εκτελεί παραμόρφωση στην τρέχουσα εικόνα. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Ισιώνει όλα τα στρώματα. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Λαμβάνει μια εικόνα 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel ARGB 32-bit. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο πίνακα πρωτογενών δεδομένων. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων χρησιμοποιώντας μερικό φορτωτή εικονοστοιχείων. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Λαμβάνει την ημερομηνία και την ώρα της τελευταίας τροποποίησης της εικόνας του πόρου. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές με βάση τις ρυθμίσεις του αρχικού αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρήσουμε το βάθος bit και άλλες παραμέτρους της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, αν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια αποθηκεύστε το χρησιμοποιώντας το [`Save`](../../aspose.psd/datastreamsupporter/save/) Με τη μέθοδο, θα παραχθεί η εικόνα εξόδου PNG με 8 bit ανά pixel. Για να το αποφύγετε και να αποθηκεύσετε εικόνα PNG με 1 bit ανά pixel, χρησιμοποιήστε αυτήν τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και να τις μεταφέρετε στο[`Save`](../../aspose.psd/image/save/)μέθοδος ως δεύτερη παράμετρος. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Λαμβάνει ένα εικονοστοιχείο εικόνας. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Μεταμόρφωση μιας εικόνας στην αναπαράστασή της σε κλίμακα του γκρι |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Φορτώνει pixel ARGB 32-bit. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Φορτώνει pixel ARGB 64-bit. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Φορτώνει pixel σε μορφή CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Φορτώνει pixel ARGB 32-bit μερικώς ανά πακέτα. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Φορτώνει τα pixel μερικώς ανά πακέτα. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Φορτώνει pixel. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Συγχωνεύει τα επίπεδα. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για να απαλλαγούμε από τη λοξή σάρωση. Αυτή η μέθοδος χρησιμοποιεί[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και[`Rotate`](../../aspose.psd/rasterimage/rotate/) μέθοδοι. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για να απαλλαγούμε από τη λοξή σάρωση. Αυτή η μέθοδος χρησιμοποιεί[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και[`Rotate`](../../aspose.psd/rasterimage/rotate/) μέθοδοι. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης από το καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης από το καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Αντικαθιστά το ένα χρώμα στο άλλο με την επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Αντικαθιστά το ένα χρώμα στο άλλο με την επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Αντικαθιστά όλα τα αδιαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για εξοικονόμηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιείτε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Αλλάζει το μέγεθος του πλάτους αναλογικά. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Περιστροφή εικόνας γύρω από το κέντρο. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Περιστροφή εικόνας γύρω από το κέντρο. |
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
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Ορίζει την ανάλυση για αυτό[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Μετατρέπει την εικόνα ράστερ στο bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Εγγράφει ολόκληρη τη γραμμή σάρωσης στο καθορισμένο ευρετήριο γραμμής σάρωσης. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Εγγράφει ολόκληρη τη γραμμή σάρωσης στο καθορισμένο ευρετήριο γραμμής σάρωσης. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Η προεπιλεγμένη έκδοση PSD. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την ικανότητα περιστροφής της εικόνας κατά συγκεκριμένη τιμή γωνίας.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Ολόκληρη η εικόνα περιστρέφεται
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Περιστροφή στρώματος
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Δείτε επίσης

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* συνέλευση [Aspose.PSD](../../)


