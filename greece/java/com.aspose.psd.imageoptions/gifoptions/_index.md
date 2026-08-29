---
title: "GifOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές δημιουργίας μορφής αρχείου gif."
type: docs
weight: 12
url: /el/java/com.aspose.psd.imageoptions/gifoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Οι επιλογές δημιουργίας μορφής αρχείου gif.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GifOptions()](#GifOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης GifOptions. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.psd.imageoptions.GifOptions-) | Αρχικοποιεί μια νέα παρουσία της κλάσης GifOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [getClass()](#getClass--) |  |
| [getColorResolution()](#getColorResolution--) | Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται η διόρθωση παλέτας. |
| [getFullFrame()](#getFullFrame--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [getInterlaced()](#getInterlaced--) | Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη. |
| [getMaxDiff()](#getMaxDiff--) | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά pixel. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Οι επιλογές πολλαπλών σελίδων |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [getResolutionSettings()](#getResolutionSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [getSource()](#getSource--) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [getXmpData()](#getXmpData--) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [hasTrailer()](#hasTrailer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer. |
| [hashCode()](#hashCode--) |  |
| [isPaletteSorted()](#isPaletteSorted--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται η διόρθωση παλέτας. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά pixel. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Οι επιλογές πολλαπλών σελίδων |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GifOptions.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.psd.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης GifOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.psd.imageoptions/gifoptions) | Οι επιλογές GIF. |

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
### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF.

**Returns:**
byte - Ο δείκτης χρώματος φόντου GIF.
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
### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF.

**Returns:**
byte - Η ανάλυση χρώματος.

Color Resolution - Αριθμός δυαδικών ψηφίων ανά πρωτεύον χρώμα που είναι διαθέσιμα στην αρχική εικόνα, μείον 1. Αυτή η τιμή αντιπροσωπεύει το μέγεθος ολόκληρης της παλέτας από την οποία επιλέχθηκαν τα χρώματα του γραφικού, όχι τον αριθμό των χρωμάτων που χρησιμοποιήθηκαν πραγματικά στο γραφικό. Για παράδειγμα, εάν η τιμή σε αυτό το πεδίο είναι 3, τότε η παλέτα της αρχικής εικόνας είχε 4 δυαδικά ψηφία ανά πρωτεύον χρώμα διαθέσιμα για τη δημιουργία της εικόνας. Αυτή η τιμή πρέπει να οριστεί για να υποδεικνύει την πλούσια της αρχικής παλέτας, ακόμη και αν δεν είναι διαθέσιμο κάθε χρώμα από ολόκληρη την παλέτα στο μηχάνημα προέλευσης.
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
### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται η διόρθωση παλέτας.

**Returns:**
boolean -  true  εάν εφαρμόζεται διόρθωση παλέτας· διαφορετικά,  false .

Palette correction σημαίνει ότι κάθε φορά που η εικόνα εξάγεται σε GIF, τα χρώματα της πηγαίας εικόνας θα αναλυθούν προκειμένου να δημιουργηθεί η πιο κατάλληλη παλέτα (σε περίπτωση που η παλέτα της εικόνας δεν υπάρχει ή δεν έχει καθοριστεί στις επιλογές). Η διαδικασία ανάλυσης διαρκεί κάποιο χρόνο, ωστόσο η τελική εικόνα θα έχει την πιο κατάλληλη χρωματική παλέτα και το αποτέλεσμα θα είναι οπτικά καλύτερο.
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
### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη.

**Returns:**
boolean
### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά εικονοστοιχείου. Εάν είναι μεγαλύτερη του μηδενός, θα χρησιμοποιηθεί συμπίεση με απώλειες. Η προτεινόμενη τιμή για βέλτιστη συμπίεση με απώλειες είναι 80. Το 30 είναι πολύ ελαφριά συμπίεση, το 200 είναι βαριά. Λειτουργεί καλύτερα όταν εισάγεται μόνο μικρή απώλεια, και λόγω περιορισμού του αλγορίθμου συμπίεσης πολύ υψηλά επίπεδα απώλειας δεν προσφέρουν τόσο κέρδος. Η κλίμακα των επιτρεπόμενων τιμών είναι [0, 1000].

**Returns:**
int - Η κλίμακα των επιτρεπόμενων τιμών.
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
### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF.

Pixel Aspect Ratio - Συντελεστής που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης του λόγου διαστάσεων του εικονοστοιχείου στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση του λόγου διαστάσεων υπολογίζεται βάσει του τύπου: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Το Pixel Aspect Ratio ορίζεται ως το πηλίκο του πλάτους του εικονοστοιχείου προς το ύψος του. Η κλίμακα τιμών σε αυτό το πεδίο επιτρέπει τον καθορισμό του πιο πλατύ εικονοστοιχείου 4:1 έως του πιο ψηλού 1:4 με βήματα 1/64. Τιμές : 0 - Δεν παρέχονται πληροφορίες λόγου διαστάσεων. 1..255 - Τιμή που χρησιμοποιείται στον υπολογισμό.

**Returns:**
byte - Ο λόγος διαστάσεων εικονοστοιχείου GIF.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer.

**Returns:**
boolean -  true  εάν το GIF έχει trailer· διαφορετικά,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες.

**Returns:**
boolean -  true  εάν οι καταχωρήσεις της παλέτας είναι ταξινομημένες· διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου GIF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte | Ο δείκτης χρώματος φόντου GIF. |

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

### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Λαμβάνει ή ορίζει την ανάλυση χρώματος GIF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte | Η ανάλυση χρώματος. |

Color Resolution - Αριθμός δυαδικών ψηφίων ανά πρωτεύον χρώμα που είναι διαθέσιμα στην αρχική εικόνα, μείον 1. Αυτή η τιμή αντιπροσωπεύει το μέγεθος ολόκληρης της παλέτας από την οποία επιλέχθηκαν τα χρώματα του γραφικού, όχι τον αριθμό των χρωμάτων που χρησιμοποιήθηκαν πραγματικά στο γραφικό. Για παράδειγμα, εάν η τιμή σε αυτό το πεδίο είναι 3, τότε η παλέτα της αρχικής εικόνας είχε 4 δυαδικά ψηφία ανά πρωτεύον χρώμα διαθέσιμα για τη δημιουργία της εικόνας. Αυτή η τιμή πρέπει να οριστεί για να υποδεικνύει την πλούσια της αρχικής παλέτας, ακόμη και αν δεν είναι διαθέσιμο κάθε χρώμα από ολόκληρη την παλέτα στο μηχάνημα προέλευσης. |

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

### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται η διόρθωση παλέτας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  εάν εφαρμόζεται διόρθωση παλέτας· διαφορετικά,  false . |

Palette correction σημαίνει ότι κάθε φορά που η εικόνα εξάγεται σε GIF, τα χρώματα της πηγαίας εικόνας θα αναλυθούν προκειμένου να δημιουργηθεί η πιο κατάλληλη παλέτα (σε περίπτωση που η παλέτα της εικόνας δεν υπάρχει ή δεν έχει καθοριστεί στις επιλογές). Η διαδικασία ανάλυσης διαρκεί κάποιο χρόνο, ωστόσο η τελική εικόνα θα έχει την πιο κατάλληλη χρωματική παλέτα και το αποτέλεσμα θα είναι οπτικά καλύτερο. |

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

### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Αληθές εάν η εικόνα πρέπει να είναι διαπλεγμένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά εικονοστοιχείου. Εάν είναι μεγαλύτερη του μηδενός, θα χρησιμοποιηθεί συμπίεση με απώλειες. Η προτεινόμενη τιμή για βέλτιστη συμπίεση με απώλειες είναι 80. Το 30 είναι πολύ ελαφριά συμπίεση, το 200 είναι βαριά. Λειτουργεί καλύτερα όταν εισάγεται μόνο μικρή απώλεια, και λόγω περιορισμού του αλγορίθμου συμπίεσης πολύ υψηλά επίπεδα απώλειας δεν προσφέρουν τόσο κέρδος. Η κλίμακα των επιτρεπόμενων τιμών είναι [0, 1000].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η κλίμακα των επιτρεπόμενων τιμών. |

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

### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις παλέτας είναι ταξινομημένες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν οι καταχωρήσεις της παλέτας είναι ταξινομημένες· διαφορετικά,  false . |

### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel GIF.

Pixel Aspect Ratio - Συντελεστής που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης του λόγου διαστάσεων του εικονοστοιχείου στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση του λόγου διαστάσεων υπολογίζεται βάσει του τύπου: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Το Pixel Aspect Ratio ορίζεται ως το πηλίκο του πλάτους του εικονοστοιχείου προς το ύψος του. Η κλίμακα τιμών σε αυτό το πεδίο επιτρέπει τον καθορισμό του πιο πλατύ εικονοστοιχείου 4:1 έως του πιο ψηλού 1:4 με βήματα 1/64. Τιμές : 0 - Δεν παρέχονται πληροφορίες λόγου διαστάσεων. 1..255 - Τιμή που χρησιμοποιείται στον υπολογισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte | Ο λόγος διαστάσεων εικονοστοιχείου GIF. |

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

### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν το GIF έχει trailer· διαφορετικά,  false . |

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

