---
title: "JpegOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές δημιουργίας μορφής αρχείου jpeg."
type: docs
weight: 15
url: /el/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Οι επιλογές δημιουργίας μορφής αρχείου jpeg.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpegOptions . |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpegOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Λαμβάνει τα δυαδικά ψηφία ανά κανάλι για εικόνα jpeg χωρίς απώλειες. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Το προφίλ χρώματος CMYK προορισμού για εικόνες jpeg CMYK. |
| [getColorType()](#getColorType--) | Λαμβάνει τον τύπο χρώματος για εικόνα jpeg. |
| [getComment()](#getComment--) | Λαμβάνει το σχόλιο του αρχείου jpeg. |
| [getCompressionType()](#getCompressionType--) | Λαμβάνει τον τύπο συμπίεσης. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Λαμβάνει το προεπιλεγμένο όριο κατανομής μνήμης. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getExifData()](#getExifData--) | Αποκτήστε ή ορίστε το δοχείο δεδομένων exif |
| [getFullFrame()](#getFullFrame--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Λαμβάνει τις οριζόντιες υποδειγματοληψίες για κάθε συστατικό. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [getJfif()](#getJfif--) | Λαμβάνει το jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Λαμβάνει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Λαμβάνει τη λειτουργία διαπλέξης JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Λαμβάνει τις προρυθμισμένες παραμέτρους JPEG-LS. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Οι επιλογές πολλαπλών σελίδων |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [getQuality()](#getQuality--) | Λαμβάνει την ποιότητα εικόνας. |
| [getRdOptSettings()](#getRdOptSettings--) | Λαμβάνει τις ρυθμίσεις του βελτιστοποιητή RD. |
| [getResolutionSettings()](#getResolutionSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [getResolutionUnit()](#getResolutionUnit--) | Λαμβάνει τη μονάδα ανάλυσης. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Το προφίλ χρώματος RGB προορισμού για εικόνες CMYK jpeg. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Λαμβάνει τη λειτουργία στρογγυλοποίησης δείγματος για προσαρμογή μιας 8-bit τιμής σε τιμή n-bit. |
| [getScaledQuality()](#getScaledQuality--) | Η κλιμακωμένη ποιότητα. |
| [getSource()](#getSource--) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [getVerticalSampling()](#getVerticalSampling--) | Λαμβάνει τις κάθετες υποδειγματοληψίες για κάθε συστατικό. |
| [getXmpData()](#getXmpData--) | Λαμβάνει το δοχείο μεταδεδομένων XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Το προφίλ χρώματος CMYK προορισμού για εικόνες jpeg CMYK. |
| [setColorType(int value)](#setColorType-int-) | Ορίζει τον τύπο χρώματος για εικόνα jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Ορίζει το σχόλιο του αρχείου jpeg. |
| [setCompressionType(int value)](#setCompressionType-int-) | Ορίζει τον τύπο συμπίεσης. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Αποκτήστε ή ορίστε το δοχείο δεδομένων exif |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Ορίζει τις οριζόντιες υποδειγματοληψίες για κάθε συστατικό. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Ορίζει το jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Ορίζει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Ορίζει τη λειτουργία διαπλέξης JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Ορίζει τις προρυθμισμένες παραμέτρους JPEG-LS. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Οι επιλογές πολλαπλών σελίδων |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [setQuality(int value)](#setQuality-int-) | Ορίζει την ποιότητα της εικόνας. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Ορίζει τις ρυθμίσεις του βελτιστοποιητή RD. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Ορίζει τη μονάδα ανάλυσης. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Το προφίλ χρώματος RGB προορισμού για εικόνες CMYK jpeg. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για προσαρμογή μιας 8-bit τιμής σε τιμή n-bit. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Ορίζει τις κατακόρυφες υποδειγματοληψίες για κάθε συστατικό. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Ορίζει το δοχείο μεταδεδομένων XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpegOptions .

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpegOptions .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Οι επιλογές JPEG. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Κλωνοποιεί αυτήν την παρουσία.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Λαμβάνει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι.

**Returns:**
byte
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

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
public StreamSource getCmykColorProfile()
```


Το προορισμένο προφίλ χρώματος CMYK για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να συνδυάζεται με το RGBColorProfile για σωστή μετατροπή χρώματος.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Λαμβάνει τον τύπο χρώματος για εικόνα jpeg.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Λαμβάνει το σχόλιο του αρχείου jpeg.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Λαμβάνει τον τύπο συμπίεσης.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Λαμβάνει το προεπιλεγμένο όριο κατανομής μνήμης.

**Returns:**
int - Το προεπιλεγμένο όριο κατανομής μνήμης.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για την σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώσης στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Τιμή: Η προεπιλεγμένη εναλλακτική γραμματοσειρά.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Αποκτήστε ή ορίστε το δοχείο δεδομένων exif

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο].

Τιμή:  true  εάν [full frame]; διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Λαμβάνει τις οριζόντιες υποδειγματοληψίες για κάθε συστατικό.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος.

Τιμή:  true  εάν αγνοείται μετά τη δημιουργία του συμβάντος· διαφορετικά,  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Λαμβάνει το jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Λαμβάνει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Λαμβάνει τη λειτουργία διαπλέξης JPEG-LS.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Λαμβάνει τις προρυθμισμένες παραμέτρους JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Οι επιλογές πολλαπλών σελίδων

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Λαμβάνει την ποιότητα εικόνας.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Λαμβάνει τις ρυθμίσεις του βελτιστοποιητή RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Λαμβάνει τη μονάδα ανάλυσης.

**Returns:**
byte - η μονάδα ανάλυσης.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Το προορισμένο προφίλ χρώματος RGB για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να συνδυάζεται με το CMYKColorProfile για σωστή μετατροπή χρώματος.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Λαμβάνει τη λειτουργία στρογγυλοποίησης δείγματος για προσαρμογή μιας 8-bit τιμής σε τιμή n-bit.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Η κλιμακωμένη ποιότητα.

**Returns:**
int
### getSource() {#getSource--}
```
public final Source getSource()
```


Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας.

Τιμή: Η πηγή για τη δημιουργία της εικόνας.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Λαμβάνει τις κάθετες υποδειγματοληψίες για κάθε συστατικό.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λαμβάνει το δοχείο μεταδεδομένων XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Το προορισμένο προφίλ χρώματος CMYK για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να συνδυάζεται με το RGBColorProfile για σωστή μετατροπή χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Ορίζει τον τύπο χρώματος για εικόνα jpeg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ορίζει το σχόλιο του αρχείου jpeg.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Ορίζει τον τύπο συμπίεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Ορίζει το προεπιλεγμένο όριο κατανομής μνήμης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το προεπιλεγμένο όριο κατανομής μνήμης. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για την σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώσης στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Τιμή: Η προεπιλεγμένη εναλλακτική γραμματοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Αποκτήστε ή ορίστε το δοχείο δεδομένων exif

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν [full frame].

Τιμή:  true  εάν [full frame]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν [full frame]. |

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Ορίζει τις οριζόντιες υποδειγματοληψίες για κάθε συστατικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος.

Τιμή:  true  εάν αγνοείται μετά τη δημιουργία του συμβάντος· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Ορίζει το jfif.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Ορίζει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Ορίζει τη λειτουργία διαπλέξης JPEG-LS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Ορίζει τις προρυθμισμένες παραμέτρους JPEG-LS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Οι επιλογές πολλαπλών σελίδων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Λαμβάνει ή ορίζει την παλέτα χρωμάτων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Ορίζει την ποιότητα της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Ορίζει τις ρυθμίσεις του βελτιστοποιητή RD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Οι ρυθμίσεις του βελτιστοποιητή RD. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Ορίζει τη μονάδα ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte | η μονάδα ανάλυσης. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Το προορισμένο προφίλ χρώματος RGB για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να συνδυάζεται με το CMYKColorProfile για σωστή μετατροπή χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για προσαρμογή μιας 8-bit τιμής σε τιμή n-bit.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας.

Τιμή: Η πηγή για τη δημιουργία της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Ορίζει τις κατακόρυφες υποδειγματοληψίες για κάθε συστατικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Ορίζει το δοχείο μεταδεδομένων XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Το δοχείο δεδομένων XMP. |

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

