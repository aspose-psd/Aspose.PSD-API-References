---
title: "BmpOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές δημιουργίας μορφής αρχείου bmp."
type: docs
weight: 10
url: /el/java/com.aspose.psd.imageoptions/bmpoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

Οι επιλογές δημιουργίας μορφής αρχείου bmp.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BmpOptions. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.psd.imageoptions.BmpOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BmpOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerPixel()](#getBitsPerPixel--) | Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [getClass()](#getClass--) |  |
| [getCompression()](#getCompression--) | Λαμβάνει ή ορίζει τη συμπίεση. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFullFrame()](#getFullFrame--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Οι επιλογές πολλαπλών σελίδων |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [getResolutionSettings()](#getResolutionSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [getSource()](#getSource--) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [getXmpData()](#getXmpData--) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [setCompression(long value)](#setCompression-long-) | Λαμβάνει ή ορίζει τη συμπίεση. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Οι επιλογές πολλαπλών σελίδων |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BmpOptions.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.psd.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BmpOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.psd.imageoptions/bmpoptions) | Οι επιλογές BMP. |

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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας.

**Returns:**
int - Ο αριθμός των bit ανά εικονοστοιχείο της εικόνας.
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
### getCompression() {#getCompression--}
```
public long getCompression()
```


Λαμβάνει ή ορίζει τη συμπίεση.

**Returns:**
long - Η συμπίεση.
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
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο].

Τιμή:  true  εάν [full frame]; διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος.

Τιμή:  true  εάν αγνοείται μετά τη δημιουργία του συμβάντος· διαφορετικά,  false .

**Returns:**
boolean
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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
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
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP.

Τιμή: Το δοχείο δεδομένων XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Λαμβάνει ή ορίζει τον αριθμό bits ανά pixel της εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Ο αριθμός bits ανά pixel της εικόνας. |

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

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Λαμβάνει ή ορίζει τη συμπίεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long | Η συμπίεση. |

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

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP.

Τιμή: Το δοχείο δεδομένων XMP.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

