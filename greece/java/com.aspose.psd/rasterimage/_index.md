---
title: "RasterImage"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει μια ραστερ εικόνα που υποστηρίζει λειτουργίες ραστερ γραφικών."
type: docs
weight: 86
url: /el/java/com.aspose.psd/rasterimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image)

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver
```

Αντιπροσωπεύει μια ραστερ εικόνα που υποστηρίζει λειτουργίες ραστερ γραφικών.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [OnCreate_internalized](#OnCreate-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε |
| [OnLoad_internalized](#OnLoad-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε από το createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ρύθμιση της φωτεινότητας για την εικόνα. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Αντίθεση εικόνας |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Γάμμα-διόρθωση μιας εικόνας. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Γάμμα-διόρθωση μιας εικόνας. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Μετατρέπει σε aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες create options. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες εικόνες ως σελίδες |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Δημιουργεί μια νέα εικόνα με τις καθορισμένες εικόνες ως σελίδες. |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Κόβει το καθορισμένο ορθογώνιο. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Περικόψτε την εικόνα με μετατοπίσεις. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η αυτόματη προσαρμογή παλέτας. |
| [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει τον αριθμό bits ανά pixel της εικόνας. |
| [getBounds()](#getBounds--) | Λαμβάνει τα όρια της εικόνας. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | Λαμβάνει το περιέκτη Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Λαμβάνει την παλέτα βαθιάς προσαρμογής. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Λαμβάνει τον προεπιλεγμένο πίνακα ακατέργαστων δεδομένων. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει μια τιμή μορφής αρχείου. |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Λαμβάνει τη μορφή αρχείου. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Λαμβάνει τη μορφή αρχείου. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Λαμβάνει την παλέτα από μορφο-συγκεκριμένες θέσεις. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος της εικόνας. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του  RasterImage . |
| [getImageOpacity()](#getImageOpacity--) | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Λαμβάνει τον παρακολουθητή διακοπής. |
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
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| [getRawDataFormat()](#getRawDataFormat--) | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων |
| [getRawLineSize()](#getRawLineSize--) | Λαμβάνει το μέγεθος ακατέργαστης γραμμής σε bytes. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος της εικόνας. |
| [getSkewAngle()](#getSkewAngle--) | Λαμβάνει τη γωνία παραμόρφωσης. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. |
| [getTransparentColor()](#getTransparentColor--) | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης |
| [getUseRawData()](#getUseRawData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Λαμβάνει την χρησιμοποιούμενη παλέτα. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Λαμβάνει την άδεια venture. |
| [getVerticalResolution()](#getVerticalResolution--) | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της εικόνας. |
| [getXmpData()](#getXmpData--) | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
| [grayscale()](#grayscale--) | Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι. |
| [hasAlpha()](#hasAlpha--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει άλφα. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [hasTransparentColor()](#hasTransparentColor--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Λαμβάνει ή ορίζει τη μέγιστη τιμή προόδου |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Δείχνει την πρόοδο. |
| [isCached()](#isCached--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [isUsePalette()](#isUsePalette--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα της εικόνας χρησιμοποιείται. |
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
| [normalizeAngle()](#normalizeAngle--) | Κανονικοποιεί τη γωνία. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Κανονικοποιεί τη γωνία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Καλείται όταν ο περιέκτης αυτού του [Image](../../com.aspose.psd/image) έχει οριστεί. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με τον καθορισμένο δείκτη γραμμής σάρωσης. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το μέγεθος της εικόνας με επεκταμένες επιλογές. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Αλλάζει το μέγεθος της εικόνας. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το ύψος αναλογικά. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Αλλάζει το ύψος αναλογικά. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Αλλάζει το πλάτος αναλογικά. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Αλλάζει το πλάτος αναλογικά. |
| [rotate(float angle)](#rotate-float-) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή στο καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Ορίζει ένα pixel εικόνας 32-bit ARGB για τη συγκεκριμένη θέση. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν η εικόνα έχει χρώμα φόντου. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Ορίζει το Image container. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Ορίζει τον φορτωτή δεδομένων απευθείας. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ορίζει τη ροή δεδομένων του αντικειμένου. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Ορίζει την παλέτα σε μορφο-συγκεκριμένες θέσεις |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του  RasterImage . |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία της εικόνας έχει αλλάξει μετά τη φόρτωση. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Ορίζει τον παρατηρητή διακοπής. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Ορίζει τον διαχειριστή μνήμης. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Ορίζει την παλέτα χρωμάτων. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Ορίζει την παλέτα εικόνας. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα στοιχεία της εικόνας πρέπει να προπολλαπλασιαστούν. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Λαμβάνει ή ορίζει τον δείκτη μετατροπέα χρωμάτων |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ορίζει την ανάλυση για αυτό το RasterImage. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Όλα τα προϊόντα Aspose πρέπει να υλοποιούν αυτή τη μέθοδο. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
| [toBitmap()](#toBitmap--) | Μετατρέπει την raster εικόνα σε bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
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
public abstract void cacheData()
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
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Κόβει το καθορισμένο ορθογώνιο.

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
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Λαμβάνει τον αριθμό bits ανά pixel της εικόνας.

**Returns:**
int - Ο αριθμός των bit ανά εικονοστοιχείο της εικόνας.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Λαμβάνει το περιέκτη Image.

Τιμή: Ο  Image  container.

Εάν αυτή η ιδιότητα δεν είναι null, υποδεικνύει ότι η εικόνα περιέχεται μέσα σε άλλη εικόνα.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Λαμβάνει το ύψος της εικόνας.

**Returns:**
int - Το ύψος της εικόνας.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του  RasterImage .

**Returns:**
double - Η οριζόντια ανάλυση.

Σημείωση: από προεπιλογή αυτή η τιμή είναι πάντα 96 επειδή διαφορετικές πλατφόρμες δεν μπορούν να επιστρέψουν την ανάλυση της οθόνης. Μπορείτε να εξετάσετε τη χρήση της μεθόδου SetResolution για την ενημέρωση και των δύο τιμών ανάλυσης σε μία κλήση.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Λαμβάνει τη διαφάνεια αυτής της εικόνας.

**Returns:**
float - Η τιμή διαφάνειας μεταξύ 0.0 (πλήρως διαφανές) και 1.0 (πλήρως αδιαφανές).
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Λαμβάνει τον παρακολουθητή διακοπής.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. Επιστρέφει μια κενή συμβολοσειρά εάν δεν μπορεί να βρεθεί η πηγαία διαδρομή.

**Returns:**
java.lang.String - Η διαδρομή αρχείου της πηγαίας εικόνας.
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage.

**Returns:**
double - Η κάθετη ανάλυση.

Σημείωση: από προεπιλογή αυτή η τιμή είναι πάντα 96 επειδή διαφορετικές πλατφόρμες δεν μπορούν να επιστρέψουν την ανάλυση της οθόνης. Μπορείτε να εξετάσετε τη χρήση της μεθόδου SetResolution για την ενημέρωση και των δύο τιμών ανάλυσης σε μία κλήση.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Λαμβάνει το πλάτος της εικόνας.

**Returns:**
int - Το πλάτος της εικόνας.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λαμβάνει ή ορίζει τα μεταδεδομένα XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι.

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει άλφα.

**Returns:**
boolean -  true  εάν αυτή η παρουσία έχει άλφα· διαφορετικά,  false .
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

**Returns:**
boolean -  true  εάν αυτή η παρουσία έχει τροποποιηθεί η εικόνα· διαφορετικά,  false .
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

### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.
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


Αλλάζει το μέγεθος της εικόνας με επεκταμένες επιλογές.

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
public abstract void rotateFlip(int rotateFlipType)
```


Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | int | Τύπος της περιστροφής/αναστροφής. |

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
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του  RasterImage .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η οριζόντια ανάλυση. |

Σημείωση: από προεπιλογή αυτή η τιμή είναι πάντα 96, καθώς διαφορετικές πλατφόρμες δεν μπορούν να επιστρέψουν την ανάλυση της οθόνης. Μπορείτε να εξετάσετε τη χρήση της μεθόδου SetResolution για την ενημέρωση και των δύο τιμών ανάλυσης με μία κλήση. |

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

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Ορίζει τον παρατηρητή διακοπής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | ο παρακολουθητής διακοπής. |

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


Ορίζει την ανάλυση για αυτό το RasterImage.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpiX | double | Η οριζόντια ανάλυση, σε κουκκίδες ανά ίντσα, του  RasterImage . |
| dpiY | double | Η κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, του  RasterImage . |

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


Όλα τα προϊόντα Aspose πρέπει να υλοποιούν αυτή τη μέθοδο. Καλείται από ένα προϊόν GroupDocs για να υποδείξει εάν το GroupDocs είναι αδειοδοτημένο ή όχι και να καθορίσει ένα προσαρμοσμένο υδατογράφημα. Όταν το GroupDocs είναι αδειοδοτημένο, αυτή η παρουσία του εγγράφου πρέπει να συμπεριφέρεται επίσης ως αδειοδοτημένη ακόμη και αν το προϊόν Aspose δεν είναι αδειοδοτημένο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ventureLicense | java.lang.Object | license |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του RasterImage.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | double | Η κάθετη ανάλυση. |

Σημείωση: από προεπιλογή αυτή η τιμή είναι πάντα 96, καθώς διαφορετικές πλατφόρμες δεν μπορούν να επιστρέψουν την ανάλυση της οθόνης. Μπορείτε να εξετάσετε τη χρήση της μεθόδου SetResolution για την ενημέρωση και των δύο τιμών ανάλυσης με μία κλήση. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Λαμβάνει ή ορίζει τα μεταδεδομένα XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Τα μεταδεδομένα XMP. |

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

