---
title: "PsdImage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης, επεξεργασίας και αποθήκευσης αρχείων PSD, καθώς και ενημέρωσης ιδιοτήτων, προσθήκης υδατογραφιών, εκτέλεσης γραφικών λειτουργιών ή μετατροπής ενός μορφότυπου αρχείου σε άλλο."
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Ορίζει την κλάση PsdImage που παρέχει τη δυνατότητα φόρτωσης, επεξεργασίας και αποθήκευσης αρχείων PSD, καθώς και ενημέρωσης ιδιοτήτων, προσθήκης υδατογραφιών, εκτέλεσης γραφικών λειτουργιών ή μετατροπής ενός μορφότυπου αρχείου σε άλλο. Το Aspose.PSD υποστηρίζει εισαγωγή ως στρώση και εξαγωγή στα ακόλουθα μορφότυπα: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, καθώς και εξαγωγή σε Pdf με δυνατότητα επιλογής κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη διαδρομή). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη διαδρομή) με παραμέτρους κατασκευής. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στο ρεύμα). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στο ρεύμα) με παραμέτρους κατασκευής. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με παραμέτρους κατασκευής. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) με καθορισμένο πλάτος και ύψος. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) με καθορισμένα πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών, καθώς και παραμέτρους του καθορισμένου τρόπου συμπίεσης. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Το προεπιλεγμένο όνομα κωδικοποίησης |
| [DefaultVersion](#DefaultVersion) | Η προεπιλεγμένη έκδοση PSD. |
| [OnCreate_internalized](#OnCreate-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε |
| [OnLoad_internalized](#OnLoad-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε από το createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | Το αντικείμενο που μπορεί να χρησιμοποιηθεί για συγχρονισμό πρόσβασης στα στρώματα. |
| [horizontalResolution](#horizontalResolution) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Προσθέτει το επίπεδο ρύθμισης ασπρόμαυρου. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Προσθέτει το επίπεδο ρύθμισης φωτεινότητας/αντίθεσης. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Προσθέτει το επίπεδο ρύθμισης μίκτη καναλιών με προεπιλεγμένες παραμέτρους |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Προσθέτει το επίπεδο ρύθμισης ισορροπίας χρωμάτων. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής Καμπύλες. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Προσθέτει τη στρώση προσαρμογής έκθεσης. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής GradientMap. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής απόχρωσης/κορεσμού. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Προσθέτει μια στρώση αντιστροφής. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Προσθέτει τη στρώση. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Προσθέτει την ομάδα στρωμάτων. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Προσθέτει τη στρώση στον δείκτη. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής Επιπέδων. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Προσθέτει τη στρώση φίλτρου φωτογραφίας. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής Posterize. |
| [addRegularLayer()](#addRegularLayer--) | Προσθέτει μια νέα κανονική στρώση. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής επιλεκτικού χρώματος. |
| [addShapeLayer()](#addShapeLayer--) | Προσθέτει κενή στρώση Σχήματος. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Προσθέτει μια νέα στρώση Κειμένου. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής Κατωφλίου. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Προσθέτει τη στρώση προσαρμογής Ζωντάνιας. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ρύθμιση της φωτεινότητας για την εικόνα. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Αντίθεση εικόνας |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Γάμμα-διόρθωση μιας εικόνας. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Γάμμα-διόρθωση μιας εικόνας. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Ξεκινά τη διαδικασία αλλαγής μεγέθους. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι. |
| [binarizeOtsu()](#binarizeOtsu--) | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu. |
| [cacheData()](#cacheData--) | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας τις καθορισμένες loadOptions. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες open options. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο συγκεκριμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις παρεχόμενες save options. |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Μετατρέπει αυτή τη μορφή εικόνας στη μορφή που καθορίζεται στις επιλογές. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Μετατρέπει σε aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες εικόνες ως σελίδες |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Δημιουργεί μια νέα εικόνα με τις καθορισμένες εικόνες ως σελίδες. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Δημιουργεί τη νέα παρουσία της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class. |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Περικοπή της εικόνας. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Περικόψτε την εικόνα με μετατοπίσεις. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Περικοπή της εικόνας. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το μέγεθος της εικόνας. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [flattenImage()](#flattenImage--) | Ισοπεδώνει όλες τις στρώσεις. |
| [getActiveLayer()](#getActiveLayer--) | Λαμβάνει ή ορίζει τη ενεργή στρώση. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η αυτόματη προσαρμογή παλέτας. |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Λαμβάνει τα bits ανά κανάλι. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει τον αριθμό bits ανά pixel της εικόνας. |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια της εικόνας. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [getChannelsCount()](#getChannelsCount--) | Λαμβάνει τον αριθμό καναλιών PSD. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες PSD CMYK. |
| [getColorMode()](#getColorMode--) | Λαμβάνει ή ορίζει τη λειτουργία χρώματος. |
| [getCompression()](#getCompression--) | Λαμβάνει τη μέθοδο συμπίεσης. |
| [getContainer()](#getContainer--) | Λαμβάνει το περιέκτη Image. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Λαμβάνει τις τρέχουσες επιλογές εικόνας. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Λαμβάνει την παλέτα βαθιάς προσαρμογής. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει μια τιμή μορφής αρχείου. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Λαμβάνει τη μορφή αρχείου. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Λαμβάνει την παλέτα από μορφο-συγκεκριμένες θέσεις. |
| [getGlobalAngle()](#getGlobalAngle--) | Λαμβάνει ή ορίζει τη παγκόσμια γωνία. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Λαμβάνει τις πληροφορίες της παγκόσμιας μάσκας στρώσης. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Λαμβάνει ή ορίζει τους παγκόσμιους πόρους στρώσης. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Λαμβάνει ή ορίζει το προφίλ χρώματος GRAY (μονόχρωμο) για εικόνες PSD σε κλίμακα του γκρι. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος της εικόνας. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Λαμβάνει ή ορίζει τις στρώσεις PSD. |
| [getImageOpacity()](#getImageOpacity--) | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| [getImageResources()](#getImageResources--) | Λαμβάνει ή ορίζει τους πόρους εικόνας PSD. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Λαμβάνει τον εσωτερικό μετασχηματιστή δεδομένων. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Λαμβάνει τον παρακολουθητή διακοπής. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Λαμβάνει τη στρώση και τη μάσκα. |
| [getLayers()](#getLayers--) | Λαμβάνει ή ορίζει τις στρώσεις PSD. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Λαμβάνει τον διαχειριστή συνδεδεμένων στρώσεων. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Λαμβάνει τον διαχειριστή μνήμης. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Λαμβάνει την εικόνα που μπορεί να βαφτεί. |
| [getPalette()](#getPalette--) | Λαμβάνει την παλέτα χρωμάτων. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Λαμβάνει ένα pixel εικόνας. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Δημιουργεί την ιδιωτική κρυφή μνήμη γραμματοσειρών. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Λαμβάνει ένα αναλογικό ύψος. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Λαμβάνει ένα αναλογικό πλάτος. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα PSD. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| [getRawDataFormat()](#getRawDataFormat--) | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων |
| [getRawLineSize()](#getRawLineSize--) | Λαμβάνει το μέγεθος ακατέργαστης γραμμής σε bytes. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες PSD σε CMYK. |
| [getRotateMode()](#getRotateMode--) | Λαμβάνει ή ορίζει τη λειτουργία περιστροφής. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος της εικόνας. |
| [getSkewAngle()](#getSkewAngle--) | Λαμβάνει τη γωνία παραμόρφωσης. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Λαμβάνει τον πάροχο έξυπνου αντικειμένου. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Λαμβάνει τη ρίζα συγχρονισμού. |
| [getTimeline()](#getTimeline--) | Λαμβάνει το  Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Λαμβάνει ενημερωμένους πόρους με εντελώς νέο μπλοκ πόρων. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης |
| [getUseRawData()](#getUseRawData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Λαμβάνει την χρησιμοποιούμενη παλέτα. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Λαμβάνει την άδεια venture. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [getVerticalResolution()](#getVerticalResolution--) | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της εικόνας. |
| [getXmpData()](#getXmpData--) | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
| [grayscale()](#grayscale--) | Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι. |
| [hasAlpha()](#hasAlpha--) | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [hasTransparencyData()](#hasTransparencyData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται τα δεδομένα στρώσεων. |
| [hasTransparentColor()](#hasTransparentColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Λαμβάνει ή ορίζει τη μέγιστη τιμή προόδου |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Δείχνει την πρόοδο. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Εισάγει τη στρώση μετά τη συγκεκριμένη στρώση με όλες τις προετοιμασίες. |
| [isCached()](#isCached--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή. |
| [isFlatten()](#isFlatten--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα psd είναι επίπεδη. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [isUsePalette()](#isUsePalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα της εικόνας χρησιμοποιείται. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load(String filePath)](#load-java.lang.String-) | Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Φορτώνει pixel 32-bit ARGB. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Φορτώνει pixel 64-bit ARGB. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Φορτώνει pixel σε μορφή CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Φορτώνει pixel σε μορφή CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Φορτώνει pixel 32-bit ARGB μερικώς ανά πακέτα. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Φορτώνει pixel μερικώς ανά πακέτα. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Φορτώνει pixel. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Φορτώνει ακατέργαστα δεδομένα εικόνας χρησιμοποιώντας τον μηχανισμό μερικής επεξεργασίας. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Φορτώνει ακατέργαστα δεδομένα. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Συγχωνεύει τις στρώσεις. |
| [normalizeAngle()](#normalizeAngle--) | Κανονικοποιεί τη γωνία. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Κανονικοποιεί τη γωνία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Καλείται όταν ο περιέκτης αυτού του [Image](../../com.aspose.psd/image) έχει οριστεί. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Αφαιρεί τον παγκόσμιο πόρο μηχανής κειμένου - Η μέθοδος χρησιμοποιείται για ορισμένα αρχεία psd με στρώσεις κειμένου, που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώσεις κειμένου σχετικές με ελλείπουσες γραμματοσειρές). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Αλλάζει το μέγεθος της στρώσης με την καθορισμένη αντίστροφη κλίμακα. |
| [rotate(float angle)](#rotate-float-) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Αποθηκεύει τα δεδομένα εικόνας στην υποκείμενη ροή. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(String filePath)](#save-java.lang.String-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Αποθηκεύει τα 32-bit ARGB pixels. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Αποθηκεύει τα pixel. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Αποθηκεύει τα pixel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Αποθηκεύει τα pixel. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Αποθηκεύει τα δεδομένα εικόνας στη συγκεκριμένη ροή χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης και τα όρια. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Λαμβάνει ή ορίζει τη ενεργή στρώση. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Ορίζει ένα pixel εικόνας 32-bit ARGB για τη συγκεκριμένη θέση. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν η εικόνα έχει χρώμα φόντου. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες PSD CMYK. |
| [setColorMode(short value)](#setColorMode-short-) | Λαμβάνει ή ορίζει τη λειτουργία χρώματος. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ορίζει το Image container. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Ορίζει τον φορτωτή δεδομένων απευθείας. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ορίζει τη ροή δεδομένων του αντικειμένου. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Ορίζει την παλέτα σε μορφο-συγκεκριμένες θέσεις |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | Η παγκόσμια γωνία. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Λαμβάνει ή ορίζει τους παγκόσμιους πόρους στρώσης. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Το προφίλ χρώματος GRAY (monochrome) για εικόνες Grayscale PSD. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Λαμβάνει ή ορίζει τους πόρους εικόνας PSD. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Ορίζει τον εσωτερικό μετασχηματιστή δεδομένων. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ορίζει τον παρατηρητή διακοπής. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Λαμβάνει ή ορίζει τις στρώσεις PSD. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ορίζει τον διαχειριστή μνήμης. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ορίζει την παλέτα χρωμάτων. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ορίζει την παλέτα εικόνας. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ορίζει την ανάλυση για αυτό το [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες PSD σε CMYK. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Λαμβάνει ή ορίζει τη λειτουργία περιστροφής. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται τα δεδομένα στρώσεων. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Ορίζει την άδεια venture. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει ή ορίζει την έκδοση. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
| [toBitmap()](#toBitmap--) | Μετατρέπει την raster εικόνα σε bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη διαδρομή). Χρησιμοποιείται για την αρχικοποίηση εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στη διαδρομή) με παραμέτρους κατασκευής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |
| colorMode | short | Η λειτουργία χρώματος. |
| channelBitDepth | short | Το βάθος bit PSD ανά κανάλι. |
| channels | short | Ο αριθμός καναλιών PSD. |
| psdVersion | int | Η έκδοση PSD. |
| compression | short | Η συμπίεση που θα χρησιμοποιηθεί. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στο stream). Χρησιμοποιείται για την αρχικοποίηση εικόνας psd με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από καθορισμένη διαδρομή raster εικόνας (όχι εικόνα psd στο ρεύμα) με παραμέτρους κατασκευής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |
| colorMode | short | Η λειτουργία χρώματος. |
| channelBitDepth | short | Το βάθος bit PSD ανά κανάλι. |
| channels | short | Ο αριθμός καναλιών PSD. |
| psdVersion | int | Η έκδοση PSD. |
| compression | short | Η συμπίεση που θα χρησιμοποιηθεί. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) από υπάρχουσα raster εικόνα (όχι εικόνα psd) με παραμέτρους κατασκευής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |
| colorMode | short | Η λειτουργία χρώματος. |
| channelBitDepth | short | Το βάθος bit PSD ανά κανάλι. |
| channels | short | Ο αριθμός καναλιών PSD. |
| psdVersion | int | Η έκδοση PSD. |
| compression | short | Η συμπίεση που θα χρησιμοποιηθεί. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος της εικόνας. |
| ύψος | int | Το ύψος της εικόνας. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών καθώς και καθορισμένες παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την αρχικοποίηση κενής εικόνας psd.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος της εικόνας. |
| ύψος | int | Το ύψος της εικόνας. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| colorMode | short | Η λειτουργία χρώματος. |
| channelBitDepth | short | Το βάθος bit PSD ανά κανάλι. |
| channels | short | Ο αριθμός καναλιών PSD. |
| psdVersion | int | Η έκδοση PSD. |
| compression | short | Η συμπίεση που θα χρησιμοποιηθεί. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Το προεπιλεγμένο όνομα κωδικοποίησης

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


Η προεπιλεγμένη έκδοση PSD.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε από το createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


Το αντικείμενο που μπορεί να χρησιμοποιηθεί για συγχρονισμό πρόσβασης στα στρώματα.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Προσθέτει το επίπεδο ρύθμισης ασπρόμαυρου.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Προσθέτει το επίπεδο ρύθμισης φωτεινότητας/αντίθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | int | Η φωτεινότητα. |
| contrast | int | Η αντίθεση. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Προσθέτει το επίπεδο ρύθμισης μίκτη καναλιών με προεπιλεγμένες παραμέτρους

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Προσθέτει το επίπεδο ρύθμισης ισορροπίας χρωμάτων.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής Καμπύλες.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exposure | float |  |
| μετατόπιση | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Προσθέτει τη στρώση προσαρμογής έκθεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| exposure | float | Η έκθεση. |
| μετατόπιση | float | Η μετατόπιση. |
| gammaCorrection | float | Η διόρθωση γάμμα. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής GradientMap.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής απόχρωσης/κορεσμού.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Προσθέτει μια στρώση αντιστροφής.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Προσθέτει τη στρώση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το στρώμα. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Προσθέτει την ομάδα στρωμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupName | java.lang.String | Όνομα της ομάδας. |
| δείκτης | int | Ο δείκτης του επιπέδου μετά το οποίο θα εισαχθεί. |
| startBehaviour | boolean | αν οριστεί σε  true  [start behaviour] τότε η ομάδα θα βρίσκεται σε ανοιχτή κατάσταση κατά την εκκίνηση, διαφορετικά σε ελαχιστοποιημένη κατάσταση. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Προσθέτει τη στρώση στον δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το στρώμα. |
| δείκτης | int | Ο δείκτης. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής Επιπέδων.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Προσθέτει τη στρώση φίλτρου φωτογραφίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής Posterize.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Προσθέτει μια νέα κανονική στρώση.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής επιλεκτικού χρώματος.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Προσθέστε κενό στρώμα Σχήματος. Χωρίς διαδρομές. Θα πρέπει να προστεθούν στο στρώμα σχήματος πριν από την αποθήκευση.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Προσθέτει μια νέα στρώση Κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Το κείμενο του στρώματος. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο του στρώματος. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής Κατωφλίου.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Προσθέτει τη στρώση προσαρμογής Ζωντάνιας.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ρύθμιση της φωτεινότητας για την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | int | Τιμή φωτεινότητας. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Αντίθεση εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contrast | float | Τιμή αντίθεσης (σε εύρος [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Γάμμα-διόρθωση μιας εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gamma | float | Συντελεστής γάμμα για τα κανάλια κόκκινο, πράσινο και μπλε |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Γάμμα-διόρθωση μιας εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gammaRed | float | Συντελεστής γάμμα για το κόκκινο κανάλι |
| gammaGreen | float | Συντελεστής γάμμα για το πράσινο κανάλι |
| gammaBlue | float | Συντελεστής γάμμα για το μπλε κανάλι |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Ξεκινά τη διαδικασία αλλαγής μεγέθους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος εικόνας. |
| newHeight | int | Το νέο ύψος εικόνας. |

**Returns:**
com.aspose.internal.IResizeController - Ο ελεγκτής αλλαγής μεγέθους.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightnessDifference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s pixel κεντραρισμένου γύρω από αυτό το pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightnessDifference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s pixel κεντραρισμένου γύρω από αυτό το pixel. |
| windowSize | int | Το μέγεθος του παραθύρου s x s pixel κεντραρισμένου γύρω από αυτό το pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | byte | Τιμή κατωφλίου. Εάν η αντίστοιχη γκρι τιμή ενός pixel είναι μεγαλύτερη από το κατώφλι, θα του ανατεθεί τιμή 255, διαφορετικά 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu.

### cacheData() {#cacheData--}
```
public void cacheData()
```


Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο stream; διαφορετικά,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή και προαιρετικά χρησιμοποιώντας τις καθορισμένες loadOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο stream; διαφορετικά,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο αρχείο; διαφορετικά,  false .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες open options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να φορτωθεί από το καθορισμένο αρχείο; διαφορετικά,  false .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
boolean
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
boolean
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο συγκεκριμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις παρεχόμενες save options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης προς χρήση. |

**Returns:**
boolean -  true  αν η εικόνα μπορεί να αποθηκευτεί στην καθορισμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης; διαφορετικά,  false .
### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Μετατρέπει αυτή τη μορφή εικόνας στη μορφή που καθορίζεται στις επιλογές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Οι νέες επιλογές. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Μετατρέπει σε aps.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |
| mode | int | Η λειτουργία. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο αποκοπής. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - Η σελίδα APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες create options.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες εικόνες ως σελίδες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Οι εικόνες. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Δημιουργεί μια νέα εικόνα με τις καθορισμένες εικόνες ως σελίδες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Οι εικόνες. |
| disposeImages | boolean | αν οριστεί σε  true  [απόρριψη εικόνων]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Δημιουργεί τη νέα παρουσία της κλάσης [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | Η κεφαλίδα PSD. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Τα δεδομένα χρώματος. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Οι πόροι εικόνας. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Οι πληροφορίες στρώματος και μάσκας. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Τα δεδομένα εικόνας. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| version | int | Η έκδοση PSD. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |
| noLayerLoad | boolean | Καμία φόρτωση στρώματος |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resizer | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| πλάτος | int |  |
| ύψος | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Περικοπή της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Περικόψτε την εικόνα με μετατοπίσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftShift | int | Η αριστερή μετατόπιση. |
| rightShift | int | Η δεξιά μετατόπιση. |
| topShift | int | Η επάνω μετατόπιση. |
| bottomShift | int | Η κάτω μετατόπιση. |

### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Εκτελεί dithering στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ditheringMethod | int | Η μέθοδος τριψίματος. |
| bitsCount | int | Ο τελικός αριθμός bits για τριψίματος. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Εκτελεί dithering στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ditheringMethod | int | Η μέθοδος τριψίματος. |
| bitsCount | int | Ο τελικός αριθμός bits για τριψίματος. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η προσαρμοσμένη παλέτα για τριψίματος. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Περικοπή της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Αλλάζει το μέγεθος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | boolean |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int | Ο τύπος περιστροφής/αναστροφής. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Φιλτράρει το καθορισμένο ορθογώνιο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Οι επιλογές. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Ισοπεδώνει όλες τις στρώσεις.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Λαμβάνει ή ορίζει τη ενεργή στρώση.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Λαμβάνει ένα pixel εικόνας 32-bit ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |

**Returns:**
int - Το 32-bit ARGB pixel για την καθορισμένη θέση.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η αυτόματη προσαρμογή παλέτας.

**Returns:**
boolean -  true  εάν ενεργοποιηθεί η αυτόματη προσαρμογή παλέτας· διαφορετικά,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Λαμβάνει τα bits ανά κανάλι.

Τιμή: Τα bits ανά κανάλι.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Λαμβάνει τον αριθμό bits ανά pixel της εικόνας.

Τιμή: Ο αριθμός των bits εικόνας ανά pixel.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Λαμβάνει τα όρια της εικόνας.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Returns:**
int - η υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Λαμβάνει τον αριθμό καναλιών PSD.

Τιμή: Ο αριθμός καναλιών PSD.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το RgbColorProfile για σωστή μετατροπή χρώματος.

Τιμή: Το προφίλ χρώματος CMYK.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Λαμβάνει ή ορίζει τη λειτουργία χρώματος.

Τιμή: Η λειτουργία χρώματος.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Λαμβάνει τη μέθοδο συμπίεσης.

Τιμή: Η συμπίεση.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Λαμβάνει το περιέκτη Image.

Τιμή: Ο  Image  container.

Εάν αυτή η ιδιότητα δεν είναι null, υποδεικνύει ότι η εικόνα περιέχεται μέσα σε άλλη εικόνα.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Λαμβάνει τις τρέχουσες επιλογές εικόνας.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Λαμβάνει τη ροή δεδομένων του αντικειμένου.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Λαμβάνει την παλέτα βαθιάς προσαρμογής.

**Returns:**
boolean - Η βαθιά ρύθμιση παλέτας.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |

**Returns:**
int[] - Η προεπιλεγμένη σειρά pixel.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Λαμβάνει τις προεπιλεγμένες επιλογές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | java.lang.Object[] | Τα επιχειρήματα. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ο μερικός φορτωτής ακατέργαστων δεδομένων. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για λήψη ακατέργαστων δεδομένων. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων. |

**Returns:**
byte[] - Η προεπιλεγμένη σειρά ακατέργαστων δεδομένων.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης. Εάν έχει οριστεί η γραμματοσειρά αντικατάστασης, θα χρησιμοποιείται για την απόδοση. Χρειαζόμαστε αυτή τη μέθοδο για εσωτερική υποστήριξη.

**Returns:**
java.lang.String - Το όνομα της γραμματοσειράς αντικατάστασης
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Λαμβάνει μια τιμή μορφής αρχείου.

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Η ροή. |

--------------------

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν η ροή μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | stream | java.io.InputStream | Η ροή. |

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν η ροή μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Λαμβάνει τη μορφή αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή αρχείου. |

Η καθορισμένη μορφή αρχείου δεν σημαίνει ότι η συγκεκριμένη εικόνα μπορεί να φορτωθεί. Χρησιμοποιήστε μία από τις υπερφορτώσεις της μεθόδου CanLoad για να προσδιορίσετε εάν το αρχείο μπορεί να φορτωθεί. |

**Returns:**
long - Η καθορισμένη μορφή αρχείου.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για το οποίο λαμβάνεται το κατάλληλο ορθογώνιο. |
| πλάτος | int | Το πλάτος του αντικειμένου. |
| ύψος | int | Το ύψος του αντικειμένου. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για το οποίο λαμβάνεται το κατάλληλο ορθογώνιο. |
| pixels | int[] | Τα 32-bit ARGB pixel. |
| πλάτος | int | Το πλάτος του αντικειμένου. |
| ύψος | int | Το ύψος του αντικειμένου. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Λαμβάνει την παλέτα από μορφο-συγκεκριμένες θέσεις.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Λαμβάνει ή ορίζει τη παγκόσμια γωνία.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Λαμβάνει τις πληροφορίες της παγκόσμιας μάσκας στρώσης.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Λαμβάνει ή ορίζει τους παγκόσμιους πόρους στρώσης.

Τιμή: Οι παγκόσμιες πόροι στρώσης.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Λαμβάνει ή ορίζει το προφίλ χρώματος GRAY (μονόχρωμο) για εικόνες PSD σε κλίμακα του γκρι.

Τιμή: Το προφίλ χρώματος GRAY (μονόχρωμο).

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Λαμβάνει το ύψος της εικόνας.

Τιμή: Το ύψος της εικόνας.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Λαμβάνει ή ορίζει τις στρώσεις PSD.

Τιμή: Οι στρώσεις PSD.

--------------------

Σημειώστε ότι εάν δεν υπάρχουν στρώσεις, οι άλλες σχετικές πληροφορίες στην ενότητα πληροφοριών στρώσης και μάσκας δεν θα διατηρηθούν (μάσκες στρώσεων, πόροι κ.λπ.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Λαμβάνει τη διαφάνεια αυτής της εικόνας.

**Returns:**
float - Η τιμή διαφάνειας μεταξύ 0.0 (πλήρως διαφανές) και 1.0 (πλήρως αδιαφανές).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Λαμβάνει ή ορίζει τους πόρους εικόνας PSD.

Τιμή: Οι πόροι εικόνας PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Λαμβάνει τον εσωτερικό μετασχηματιστή δεδομένων.

Τιμή: Ο εσωτερικός μετασχηματιστής δεδομένων.

**Returns:**
com.aspose.internal.IInnerDataTransformer - ο εσωτερικός μετασχηματιστής δεδομένων.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Λαμβάνει τον παρακολουθητή διακοπής.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Λαμβάνει τη στρώση και τη μάσκα.

Τιμή: Η στρώση και η μάσκα.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Λαμβάνει ή ορίζει τις στρώσεις PSD.

Τιμή: Οι στρώσεις PSD.

--------------------

Σημειώστε ότι εάν δεν υπάρχουν στρώσεις, οι άλλες σχετικές πληροφορίες στην ενότητα πληροφοριών στρώσης και μάσκας δεν θα διατηρηθούν (μάσκες στρώσεων, πόροι κ.λπ.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Λαμβάνει τον διαχειριστή συνδεδεμένων στρώσεων.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής.

**Returns:**
int - Η μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Λαμβάνει τον διαχειριστή μνήμης.

Τιμή: Ο διαχειριστής μνήμης.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - ο διαχειριστής μνήμης.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| useDefault | boolean | αν οριστεί σε `true` χρησιμοποιεί τις πληροφορίες από το FileInfo ως προεπιλεγμένη τιμή. |

**Returns:**
java.util.Date - Η ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| useDefault | boolean |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων του αρχείου. Αυτό μπορεί να είναι χρήσιμο για να διατηρηθούν το βάθος χρώματος και άλλες παράμετροι της αρχικής εικόνας αμετάβλητες. Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη μέθοδο `DataStreamSupporter.Save(string)`, θα παραχθεί η έξοδος PNG εικόνα με 8-bit ανά pixel. Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις στη μέθοδο `Image.Save(string, ImageOptionsBase)` ως δεύτερη παράμετρο.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Λαμβάνει την εικόνα που μπορεί να βαφτεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Λαμβάνει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Λαμβάνει ένα pixel εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν.

**Returns:**
boolean - `true` εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν· διαφορετικά, `false`.
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Δημιουργεί την ιδιωτική κρυφή μνήμη γραμματοσειρών.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Η ιδιωτική κρυφή μνήμη γραμματοσειρών.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Λαμβάνει τις πληροφορίες του χειριστή συμβάντος προόδου.

Τιμή: Οι πληροφορίες του χειριστή συμβάντος προόδου.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Λαμβάνει ένα αναλογικό ύψος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |
| newWidth | int | Το νέο πλάτος. |

**Returns:**
int - Το αναλογικό ύψος.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Λαμβάνει ένα αναλογικό πλάτος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλάτος | int | Το πλάτος. |
| ύψος | int | Το ύψος. |
| newHeight | int | Το νέο ύψος. |

**Returns:**
int - Το αναλογικό πλάτος.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Λαμβάνει ή ορίζει την κεφαλίδα PSD.

Τιμή: Η κεφαλίδα PSD.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Λαμβάνει τη μορφή ακατέργαστων δεδομένων.

Τιμή: Η ακατέργαστη μορφή δεδομένων.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων

**Returns:**
int - Ο δείκτης εφεδρείας που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων.
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Λαμβάνει το μέγεθος ακατέργαστης γραμμής σε bytes.

**Returns:**
int - Το ακατέργαστο μέγεθος γραμμής σε bytes.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το CmykColorProfile για σωστή μετατροπή χρώματος.

Τιμή: Το προφίλ χρώματος RGB.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Λαμβάνει ή ορίζει τη λειτουργία περιστροφής.

**Returns:**
int - Η λειτουργία περιστροφής.
### getSize() {#getSize--}
```
public Size getSize()
```


Λαμβάνει το μέγεθος της εικόνας.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Λαμβάνει τη γωνία κλίσης. Αυτή η μέθοδος είναι εφαρμόσιμη σε σαρωμένα έγγραφα κειμένου, για τον προσδιορισμό της γωνίας κλίσης κατά τη σάρωση.

**Returns:**
float - Η γωνία κλίσης, σε μοίρες.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Λαμβάνει τον πάροχο έξυπνου αντικειμένου.

Τιμή: Ο πάροχος έξυπνου αντικειμένου.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. Επιστρέφει μια κενή συμβολοσειρά εάν δεν μπορεί να βρεθεί η πηγαία διαδρομή.

**Returns:**
java.lang.String - Η διαδρομή αρχείου της πηγαίας εικόνας.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Λαμβάνει τη ρίζα συγχρονισμού.

Τιμή: Η ρίζα συγχρονισμού.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Λαμβάνει το  Timeline ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Λαμβάνει το διαφανές χρώμα της εικόνας.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP.

**Returns:**
boolean -  true  εάν ενημερωθούν τα μεταδεδομένα XMP· διαφορετικά,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Λαμβάνει ενημερωμένους πόρους με εντελώς νέο μπλοκ πόρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Οι πόροι. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | Ο πόρος για προσθήκη στους υπάρχοντες πόρους. |
| removeDuplicates | boolean | εάν οριστεί σε  true  αφαιρεί πόρους με ταυτόσημα IDs. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Επιστρέφει έναν πίνακα με ενημερωμένα μπλοκ πόρων.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης

Τιμή:  true  εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη.

**Returns:**
boolean -  true  εάν χρησιμοποιείται φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη· διαφορετικά,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Λαμβάνει την χρησιμοποιούμενη παλέτα.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Λαμβάνει την άδεια venture.

**Returns:**
java.lang.Object - Η άδεια venture ως αντικείμενο.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Λαμβάνει το πλάτος της εικόνας.

Τιμή: Το πλάτος της εικόνας.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λαμβάνει ή ορίζει τα μεταδεδομένα XMP.

Τιμή: Τα μεταδεδομένα XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι.

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage.

Τιμή:  true  εάν αυτή η παρουσία έχει άλφα· διαφορετικά,  false .

**Returns:**
boolean
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου.

**Returns:**
boolean
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση.

Τιμή:  true  εάν αυτή η παρουσία έχει αλλαγή εικόνας· διαφορετικά,  false .

**Returns:**
boolean
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται τα δεδομένα στρώσεων.

Τιμή:  true  εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται δεδομένα στρώσεων· διαφορετικά,  false .

**Returns:**
boolean
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Λαμβάνει ή ορίζει τη μέγιστη τιμή προόδου

Τιμή: Η μέγιστη τιμή προόδου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Δείχνει την πρόοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Εισάγει τη στρώση μετά τη συγκεκριμένη στρώση με όλες τις προετοιμασίες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το στρώμα. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Η στρώση για εισαγωγή. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή.

**Returns:**
boolean -  true  εάν τα δεδομένα εικόνας είναι στην κρυφή μνήμη· διαφορετικά,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα psd είναι επίπεδη.

Τιμή:  true  εάν αυτή η παρουσία είναι επίπεδη· διαφορετικά,  false .

**Returns:**
boolean
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη.

**Returns:**
boolean -  true  εάν αυτή η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη· διαφορετικά,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα της εικόνας χρησιμοποιείται.

Τιμή:  true  εάν η παλέτα χρησιμοποιείται στην εικόνα· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν η παλέτα εικόνας χρησιμοποιείται.
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο από το οποίο θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο από το οποίο θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή του αρχείου από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από το συγκεκριμένο αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή του αρχείου από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Φορτώνει pixel 32-bit ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns:**
int[] - Ο φορτωμένος πίνακας pixel 32-bit ARGB.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Φορτώνει pixel 64-bit ARGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns:**
long[] - Ο φορτωμένος πίνακας pixel 64-bit ARGB.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Φορτώνει pixel σε μορφή CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns:**
int[] - Ο φορτωμένος πίνακας pixel CMYK που παρουσιάζονται ως 32-bit ακέραιες τιμές.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Φορτώνει pixel σε μορφή CMYK. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε τη πιο αποτελεσματική μέθοδο loadCmyk32Pixels(Rectangle).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns:**
com.aspose.psd.CmykColor[] - Ο φορτωμένος πίνακας pixel CMYK.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Φορτώνει pixel 32-bit ARGB μερικώς ανά πακέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το επιθυμητό ορθογώνιο. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Ο φορτωτής pixel 32-bit ARGB. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Φορτώνει pixel μερικώς ανά πακέτα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το επιθυμητό ορθογώνιο. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Ο φορτωτής pixel. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Φορτώνει pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns:**
com.aspose.psd.Color[] - Ο φορτωμένος πίνακας pixel.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Φορτώνει ακατέργαστα δεδομένα εικόνας χρησιμοποιώντας τον μηχανισμό μερικής επεξεργασίας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Η επιθυμητή ορθογώνια περιοχή της εικόνας από την οποία θα φορτωθούν τα δεδομένα. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Φορτώνει ακατέργαστα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν ακατέργαστα δεδομένα. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Τα όρια της προορισμένης εικόνας. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων για χρήση με τα φορτωμένα δεδομένα. Σημειώστε ότι εάν τα δεδομένα δεν είναι στη συγκεκριμένη μορφή, θα γίνει μετατροπή δεδομένων. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| startPosition | long | Η αρχική θέση από την οποία θα φορτωθεί η εικόνα. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Φορτώνει μια νέα εικόνα από τη συγκεκριμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| startPosition | long | Η αρχική θέση από την οποία θα φορτωθεί η εικόνα. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Συγχωνεύει τις στρώσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το κάτω στρώμα. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Το επάνω στρώμα. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Κανονίζει τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της παραμορφωμένης σάρωσης. Η μέθοδος χρησιμοποιεί [.getSkewAngle](../../null/\#getSkewAngle) και [.rotate(float)](../../null/\#rotate-float-) μεθόδους.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Κανονίζει τη γωνία. Αυτή η μέθοδος εφαρμόζεται σε σαρωμένα έγγραφα κειμένου για την απομάκρυνση της παραμορφωμένης σάρωσης. Η μέθοδος χρησιμοποιεί [.getSkewAngle](../../null/\#getSkewAngle) και [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) μεθόδους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resizeProportionally | boolean | εάν οριστεί σε true, το μέγεθος της εικόνας σας θα αλλάξει σύμφωνα με τις προβολές του περιστρεφόμενου ορθογωνίου (σημεία γωνίας), ενώ σε άλλη περίπτωση οι διαστάσεις παραμένουν αμετάβλητες και μόνο το εσωτερικό περιεχόμενο της εικόνας περιστρέφεται. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Χρώμα του φόντου. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Καλείται όταν ο περιέκτης αυτού του [Image](../../com.aspose.psd/image) έχει οριστεί.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scanLineIndex | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |

**Returns:**
int[] - Ο πίνακας τιμών χρώματος ARGB 32-bit της γραμμής σάρωσης.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scanLineIndex | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |

**Returns:**
com.aspose.psd.Color[] - Ο πίνακας τιμών χρώματος pixel της γραμμής σάρωσης.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Αφαιρεί τον παγκόσμιο πόρο μηχανής κειμένου - Η μέθοδος χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με ελλείπουσες γραμματοσειρές). Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να εκτελέσει τα εξής στο αρχείο που άνοιξε στο Photoshop: Μενού "Text" -> "Process absent fonts". Μετά από αυτή τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά. Παρακαλούμε σημειώστε ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες τελικές αλλαγές διάταξης.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Παλαιό χρώμα που θα αντικατασταθεί. |
| oldColorDiff | byte | Επιτρεπόμενη διαφορά στο παλιό χρώμα για να είναι δυνατή η διεύρυνση του αντικατεστημένου τόνου χρώματος. |
| newColor | [Color](../../com.aspose.psd/color) | Νέο χρώμα με το οποίο θα αντικατασταθεί το παλιό χρώμα. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldColorArgb | int | Τιμή ARGB του παλιού χρώματος που θα αντικατασταθεί. |
| oldColorDiff | byte | Επιτρεπόμενη διαφορά στο παλιό χρώμα για να είναι δυνατή η διεύρυνση του αντικατεστημένου τόνου χρώματος. |
| newColorArgb | int | Τιμή ARGB του νέου χρώματος για αντικατάσταση του παλιού χρώματος. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Αντικαθιστά όλα τα μη διαφανή χρώματα με το νέο χρώμα και διατηρεί την αρχική τιμή alpha για να διατηρηθούν οι ομαλές άκρες. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Νέο χρώμα με το οποίο θα αντικατασταθούν τα μη διαφανή χρώματα. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Αντικαθιστά όλα τα μη διαφανή χρώματα με το νέο χρώμα και διατηρεί την αρχική τιμή alpha για να διατηρηθούν οι ομαλές άκρες. Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newColorArgb | int | Τιμή ARGB του νέου χρώματος για αντικατάσταση των μη διαφανών χρωμάτων. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή ResizeType.LeftTopToLeftTop.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Αλλάζει το μέγεθος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Αλλάζει το μέγεθος της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| newHeight | int | Το νέο ύψος. |
| resizeType | int | Ο τύπος αλλαγής μεγέθους. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους εικόνας. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Αλλάζει το ύψος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newHeight | int | Το νέο ύψος. |
| resizeType | int | Τύπος αλλαγής μεγέθους. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους εικόνας. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Αλλάζει το πλάτος αναλογικά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | int | Το νέο πλάτος. |
| resizeType | int | Τύπος αλλαγής μεγέθους. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Αλλάζει το μέγεθος του στρώματος με την καθορισμένη αντίστροφη κλίμακα. (νέα πλάτος = παλιό πλάτος / κλίμακα· νέο ύψος = παλιό ύψος / κλίμακα)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | double | Η κλίμακα X. |
| scaleY | double | Η κλίμακα Y. |
| resizeType | int | Τύπος αλλαγής μεγέθους. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Περιστρέφει την εικόνα γύρω από το κέντρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές περιστρέφουν δεξιόστροφα. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Περιστρέφει την εικόνα γύρω από το κέντρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές περιστρέφουν δεξιόστροφα. |
| resizeProportionally | boolean | εάν οριστεί σε true, το μέγεθος της εικόνας σας θα αλλάξει σύμφωνα με τις προβολές του περιστρεφόμενου ορθογωνίου (σημεία γωνίας), ενώ σε άλλη περίπτωση οι διαστάσεις παραμένουν αμετάβλητες και μόνο το εσωτερικό περιεχόμενο της εικόνας περιστρέφεται. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Χρώμα του φόντου. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Αποθηκεύει τα δεδομένα εικόνας στην υποκείμενη ροή.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων της πηγής. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο για αποθήκευση των δεδομένων της εικόνας. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Το αρχείο για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της προορισμένης εικόνας. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| overWrite | boolean | εάν οριστεί σε  true  θα αντικαταστήσει το περιεχόμενο του αρχείου, διαφορετικά θα προσαρτηθεί. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της προορισμένης εικόνας. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Αποθηκεύει τα 32-bit ARGB pixels.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | int[] | Ο πίνακας εικονοστοιχείων ARGB 32-bit. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Αποθηκεύει τα pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | int[] | Τα εικονοστοιχεία CMYK που παρουσιάζονται ως τιμές 32-bit ακέραιου. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Αποθηκεύει τα εικονοστοιχεία. Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο  saveCmyk32Pixels(Rectangle, int[]) .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Ο πίνακας εικονοστοιχείων CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Αποθηκεύει τα pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Ο πίνακας εικονοστοιχείων. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Αποθηκεύει τα ακατέργαστα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα ακατέργαστα δεδομένα. |
| dataOffset | int | Η αρχική μετατόπιση ακατέργαστων δεδομένων. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο των ακατέργαστων δεδομένων. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις των ακατέργαστων δεδομένων στα οποία βρίσκονται τα δεδομένα. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Αποθηκεύει τα δεδομένα εικόνας στο καθορισμένο stream χρησιμοποιώντας τις καθορισμένες επιλογές αποθήκευσης και τα όρια. Προαιρετικά εξάγει μόνο τα καθορισμένα στρώματα για προεπισκόπηση απόδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Το stream στο οποίο θα αποθηκευτούν τα δεδομένα εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης προς χρήση. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων εικόνας προορισμού. Ορίστε το σε  Rectangle.Empty  για να χρησιμοποιήσετε τα όρια της πηγής. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Τα συγκεκριμένα στρώματα προς εξαγωγή. Μια τιμή  null  υποδεικνύει προεπιλεγμένη συμπεριφορά με όλα τα στρώματα. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων της πηγής. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Λαμβάνει ή ορίζει τη ενεργή στρώση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Ορίζει ένα pixel εικόνας 32-bit ARGB για τη συγκεκριμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |
| argb32Color | int | Το 32-bit ARGB pixel για τη συγκεκριμένη θέση. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν ενεργοποιηθεί η αυτόματη προσαρμογή παλέτας· διαφορετικά,  false . |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν η εικόνα έχει χρώμα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | η υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το RgbColorProfile για σωστή μετατροπή χρώματος.

Τιμή: Το προφίλ χρώματος CMYK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Λαμβάνει ή ορίζει τη λειτουργία χρώματος.

Τιμή: Η λειτουργία χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Ορίζει το Image container.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Το  Image  container. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Ορίζει τον φορτωτή δεδομένων απευθείας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Ο φορτωτής δεδομένων. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ορίζει τη ροή δεδομένων του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή δεδομένων του αντικειμένου. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Ορίζει την παλέτα σε μορφο-συγκεκριμένες θέσεις

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Νέα παλέτα 32-bit ARGB. |

**Returns:**
boolean
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


Η παγκόσμια γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Λαμβάνει ή ορίζει τους παγκόσμιους πόρους στρώσης.

Τιμή: Οι παγκόσμιες πόροι στρώσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Το προφίλ χρώματος GRAY (monochrome) για εικόνες Grayscale PSD.

Τιμή: Το προφίλ χρώματος GRAY (μονόχρωμο).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν [ignore after save].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν [ignore after save]; διαφορετικά,  false . |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν αυτή η παρουσία έχει αλλαγή εικόνας· διαφορετικά,  false . |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Λαμβάνει ή ορίζει τους πόρους εικόνας PSD.

Τιμή: Οι πόροι εικόνας PSD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Ορίζει τον εσωτερικό μετασχηματιστή δεδομένων.

Τιμή: Ο εσωτερικός μετασχηματιστής δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.IInnerDataTransformer | ο εσωτερικός μετασχηματιστής δεδομένων. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ορίζει τον παρατηρητή διακοπής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | ο παρακολουθητής διακοπής. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Λαμβάνει ή ορίζει τις στρώσεις PSD.

Τιμή: Οι στρώσεις PSD.

--------------------

Σημειώστε ότι εάν δεν υπάρχουν στρώσεις, οι άλλες σχετικές πληροφορίες στην ενότητα πληροφοριών στρώσης και μάσκας δεν θα διατηρηθούν (μάσκες στρώσεων, πόροι κ.λπ.).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η μέγιστη επιτρεπόμενη κατανομή για αποθήκευση μερικής περιστροφής. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Ορίζει τον διαχειριστή μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Ο διαχειριστής μνήμης. |
| needDispose | boolean | αν οριστεί σε  true  [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ορίζει την παλέτα εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Η παλέτα για ορισμό. |
| updateColors | boolean | αν οριστεί σε  true  τα χρώματα θα ενημερωθούν σύμφωνα με τη νέα παλέτα· διαφορετικά οι δείκτες χρωμάτων παραμένουν αμετάβλητοι. Σημειώστε ότι οι αμετάβλητοι δείκτες μπορεί να προκαλέσουν σφάλμα στην εικόνα κατά τη φόρτωση εάν κάποιοι δείκτες δεν έχουν αντίστοιχες καταχωρήσεις στην παλέτα. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα pixel για τη συγκεκριμένη θέση. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν· διαφορετικά,  false . |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Ο προσαρμοσμένος μετατροπέας χρωμάτων |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Ο εφεδρικός δείκτης για χρήση όταν ο δείκτης παλέτας είναι εκτός ορίων |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Ο μετατροπέας χρωμάτων με δείκτες |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ορίζει την ανάλυση για αυτό το [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpiX | double | Η οριζόντια ανάλυση, σε κουκκίδες ανά ίντσα, του  RasterImage . |
| dpiY | double | Η κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, του  RasterImage . |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με το CmykColorProfile για σωστή μετατροπή χρώματος.

Τιμή: Το προφίλ χρώματος RGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία περιστροφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η λειτουργία περιστροφής. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται τα δεδομένα στρώσεων.

Τιμή:  true  εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται δεδομένα στρώσεων· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Λαμβάνει το διαφανές χρώμα της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν ενημερωθούν τα μεταδεδομένα XMP· διαφορετικά,  false . |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | boolean |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη· διαφορετικά,  false . |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Ορίζει την άδεια venture.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ventureLicense | java.lang.Object | Η άδεια venture. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Λαμβάνει ή ορίζει τα μεταδεδομένα XMP.

Τιμή: Τα μεταδεδομένα XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Μετατρέπει την raster εικόνα σε bitmap.

**Returns:**
java.awt.image.BufferedImage - Το bitmap
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scanLineIndex | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| argb32Pixels | int[] | Ο πίνακας χρωμάτων 32-bit ARGB για εγγραφή. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scanLineIndex | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Ο πίνακας χρωμάτων pixel για εγγραφή. |

