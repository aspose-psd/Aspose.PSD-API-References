---
title: "Κλάση PsdImage"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Η κλάση Aspose.PSD.FileFormats.Psd.PsdImage. Ορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης, επεξεργασίας και αποθήκευσης αρχείων PSD, καθώς και ενημέρωσης ιδιοτήτων, προσθήκης υδατογραφήματος, εκτέλεσης γραφικών λειτουργιών ή μετατροπής ενός τύπου αρχείου σε άλλο. Το Aspose.PSD υποστηρίζει εισαγωγή ως στρώση και εξαγωγή στα ακόλουθα μορφότυπα: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, καθώς και εξαγωγή σε Pdf με δυνατότητα επιλογής κειμένου."
type: docs
weight: 4050
url: /el/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Ορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης, επεξεργασίας, αποθήκευσης αρχείων PSD καθώς και ενημέρωσης ιδιοτήτων, προσθήκης υδατογραφιών, εκτέλεσης γραφικών λειτουργιών ή μετατροπής ενός τύπου αρχείου σε άλλο. Το Aspose.PSD υποστηρίζει την εισαγωγή ως στρώμα και την εξαγωγή στα ακόλουθα μορφότυπα: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, καθώς και εξαγωγή σε Pdf με δυνατότητα επιλογής κειμένου.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από υπάρχουσα ραστερική εικόνα (όχι εικόνα psd) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από καθορισμένη διαδρομή ραστερικής εικόνας (όχι εικόνα psd σε ροή). Χρησιμοποιείται για την αρχικοποίηση εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από καθορισμένη διαδρομή ραστερικής εικόνας (όχι εικόνα psd στη διαδρομή). Χρησιμοποιείται για την αρχικοποίηση εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από υπάρχουσα ραστερική εικόνα (όχι εικόνα psd) με παραμέτρους κατασκευής. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από καθορισμένη διαδρομή ραστερικής εικόνας (όχι εικόνα psd σε ροή) με παραμέτρους κατασκευής. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` από καθορισμένη διαδρομή ραστερικής εικόνας (όχι εικόνα psd στη διαδρομή) με παραμέτρους κατασκευής. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `PsdImage` με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών, καθώς και με παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Λαμβάνει ή ορίζει το ενεργό στρώμα. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν γίνεται αυτόματη προσαρμογή παλέτας. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Λαμβάνει τα bits ανά κανάλι. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Λαμβάνει τα όρια της εικόνας. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Λαμβάνει τον αριθμό καναλιών PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες CMYK PSD. Πρέπει να συνδυάζεται με το RgbColorProfile για σωστή μετατροπή χρώματος. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία χρώματος. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Λαμβάνει τη μέθοδο συμπίεσης. |
| [Container](../../aspose.psd/image/container/) { get; } | Λαμβάνει το κοντέινερ [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Λαμβάνει μια τιμή μορφής αρχείου |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Λαμβάνει ή ορίζει τη παγκόσμια γωνία. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Λαμβάνει τις πληροφορίες της παγκόσμιας μάσκας στρώματος. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Λαμβάνει ή ορίζει τους παγκόσμιους πόρους στρώματος. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος GRAY (μονόχρωμο) για εικόνες Grayscale PSD. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Ανακτά ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται δεδομένα στρωμάτων. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Λαμβάνει το ύψος της εικόνας. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του `PsdImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Λαμβάνει ή ορίζει τους πόρους εικόνας PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα psd είναι επίπεδη. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Λαμβάνει ή ορίζει τα επίπεδα PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Λαμβάνει τον διαχειριστή συνδεδεμένων επιπέδων. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να είναι προπολλαπλασιασμένα. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Ανακτά ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Ανακτά ή ορίζει τον μετατροπέα χρωμάτων με δείκτη |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Λαμβάνει το μέγεθος της ακατέργαστης γραμμής σε byte. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες PSD CMYK. Πρέπει να είναι σε ζεύγος με το CmykColorProfile για σωστή μετατροπή χρώματος. |
| [Size](../../aspose.psd/image/size/) { get; } | Λαμβάνει το μέγεθος της εικόνας. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Λαμβάνει τον πάροχο έξυπνων αντικειμένων. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Λαμβάνει το [`Timeline`](./timeline/) αυτού του `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η παλέτα της εικόνας. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Ανακτά ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Λαμβάνει το πλάτος της εικόνας. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Ανακτά ή ορίζει τα μεταδεδομένα XMP. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής ασπρόμαυρου. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Προσθέτει το επίπεδο προσαρμογής φωτεινότητας/αντίθεσης. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής μίκτη καναλιών με προεπιλεγμένες παραμέτρους |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής ισορροπίας χρώματος. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής Curves Adjustment. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Προσθέτει το επίπεδο προσαρμογής έκθεσης. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής GradientMap. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής απόχρωσης/κορεσμού. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Προσθέτει ένα επίπεδο προσαρμογής αντιστροφής. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Προσθέτει το επίπεδο. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Προσθέτει την ομάδα επιπέδων. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής Levels. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Προσθέτει το επίπεδο PhotoFilter. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής Posterize. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Προσθέτει ένα νέο κανονικό επίπεδο. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής επιλεκτικού χρώματος. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Προσθέτει κενό επίπεδο Shape. Χωρίς διαδρομές. Θα πρέπει να προστεθούν στο shape layer πριν από την αποθήκευση. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Προσθέτει ένα νέο Text layer. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Προσθέτει το επίπεδο προσαρμογής Κατωφλίου. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Προσθέτει το Vibrance adjustment layer. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Ρύθμιση της φωτεινότητας για την εικόνα. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Αντίθεση εικόνας |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Διόρθωση γάμμα μιας εικόνας. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Διόρθωση γάμμα μιας εικόνας. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Μετατρέπει αυτή τη μορφή εικόνας στην μορφή που καθορίζεται στις επιλογές. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Περικοπή της εικόνας. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Περικοπή εικόνας με μετατοπίσεις. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Αποδεσμεύει την τρέχουσα παρουσία. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Ισοπεδώνει όλα τα επίπεδα. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθεί το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο [`Save`](../../aspose.psd/datastreamsupporter/save/), θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά pixel. Για να το αποφύγουμε και να αποθηκεύσουμε την PNG εικόνα με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο [`Save`](../../aspose.psd/image/save/) ως δεύτερη παράμετρο. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Λαμβάνει ένα pixel εικόνας. Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης. Για πιο αποδοτική διαχείριση pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Μετασχηματισμός μιας εικόνας στην γκρι κλίμακα της |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 32-bit ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία 64-bit ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Φορτώνει εικονοστοιχεία σε μορφή CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Φορτώνει εικονοστοιχεία σε μορφή CMYK. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλούμε χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Φορτώνει εικονοστοιχεία 32-bit ARGB μερικώς ανά πακέτα. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Φορτώνει εικονοστοιχεία μερικώς ανά πακέτα. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Φορτώνει εικονοστοιχεία. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Φορτώνει ακατέργαστα δεδομένα. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Συγχωνεύει τα επίπεδα. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος είναι εφαρμόσιμη σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της κλίσης της σάρωσης. Αυτή η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Κανονικοποιεί τη γωνία. Αυτή η μέθοδος είναι εφαρμόσιμη σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της κλίσης της σάρωσης. Αυτή η μέθοδος χρησιμοποιεί τις μεθόδους [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) και [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για τη διατήρηση ομαλών άκρων. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Αλλάζει το μέγεθος της εικόνας. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Αλλάζει το μέγεθος της εικόνας. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Αλλάζει το ύψος αναλογικά. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Αλλάζει το ύψος αναλογικά. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Αλλάζει το ύψος αναλογικά. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Αλλάζει το πλάτος αναλογικά. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Αλλάζει το πλάτος αναλογικά. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [Save](../../aspose.psd/image/save/)() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Αποθηκεύει τα δεδομένα του αντικειμένου στο καθορισμένο ρεύμα. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα της εικόνας στο καθορισμένο ρεύμα στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στην καθορισμένη μορφή αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Αποθηκεύει τα 32-bit ARGB pixel. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Αποθηκεύει τα pixel. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Αποθηκεύει τα pixel. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Αποθηκεύει τα pixel. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Ορίζει την παλέτα της εικόνας. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Ορίζει το pixel της εικόνας για τη συγκεκριμένη θέση. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Ορίζει την ανάλυση για αυτό το `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Μετατρέπει την raster εικόνα σε bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Η προεπιλεγμένη έκδοση PSD. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα περιστροφής της εικόνας κατά συγκεκριμένη τιμή γωνίας.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Περιστροφή ολόκληρης εικόνας
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

// Περιστροφή επιπέδου
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
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


