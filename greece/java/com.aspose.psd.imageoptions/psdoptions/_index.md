---
title: "PsdOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές δημιουργίας μορφής αρχείου psd."
type: docs
weight: 21
url: /el/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Οι επιλογές δημιουργίας μορφής αρχείου psd.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Κλωνοποιεί αυτήν την παρουσία. |
| [deepClone_internalized()](#deepClone-internalized--) | Κλωνοποιεί αυτήν την παρουσία. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Λαμβάνει ή ορίζει τον αριθμό των bits ανά κανάλι χρώματος. |
| [getChannelsCount()](#getChannelsCount--) | Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd. |
| [getCompressionMethod()](#getCompressionMethod--) | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFullFrame()](#getFullFrame--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι [πλήρες πλαίσιο]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Οι επιλογές πολλαπλών σελίδων |
| [getPalette()](#getPalette--) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν - Αφαίρεση του παγκόσμιου πόρου μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών). |
| [getResolutionSettings()](#getResolutionSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [getResources()](#getResources--) | Λαμβάνει ή ορίζει τους πόρους του psd. |
| [getSource()](#getSource--) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση αρχείου psd. |
| [getXmpData()](#getXmpData--) | Λάβετε ή ορίστε το δοχείο δεδομένων XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Εμφανίζει αν η ιδιότητα ColorMode έχει ανατεθεί. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Λαμβάνει ή ορίζει το χρώμα του φόντου. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Λαμβάνει ή ορίζει τον αριθμό των bits ανά κανάλι χρώματος. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος. |
| [setColorMode(short value)](#setColorMode-short-) | Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Λαμβάνει ή ορίζει τη προεπιλεγμένη γραμματοσειρά αντικατάστασης (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα αγνοηθεί μετά τη δημιουργία του συμβάντος. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Οι επιλογές πολλαπλών σελίδων |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος προόδου. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν - Αφαίρεση του παγκόσμιου πόρου μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Λαμβάνει ή ορίζει τους πόρους του psd. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει ή ορίζει την έκδοση αρχείου psd. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Λάβετε ή ορίστε το δοχείο δεδομένων XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Οι επιλογές. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Η εικόνα. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Λαμβάνει ή ορίζει το χρώμα του φόντου. Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Λαμβάνει ή ορίζει τον αριθμό των bits ανά κανάλι χρώματος.

Τιμή: Ο αριθμός των bits ανά κανάλι χρώματος.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος.

Τιμή: Ο αριθμός των καναλιών χρώματος.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd.

Τιμή: Η λειτουργία χρώματος.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd.

Τιμή: Η μέθοδος συμπίεσης.

**Returns:**
short
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
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB.

Τιμή: Η έκδοση μορφής αρχείου.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD. Παρακαλώ σημειώστε ότι η σχεδίαση στρωμάτων κειμένου στο τελικό layout δεν υποστηρίζεται για την πλατφόρμα Compact Framework.

Τιμή:  true  αν [refresh image preview data]; διαφορετικά,  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν - Αφαίρεση του παγκόσμιου πόρου μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών). Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να εκτελέσει τα εξής στο αρχείο που άνοιξε στο Photoshop: Μενού "Text" -> "Process absent fonts". Μετά από αυτή τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά. Παρακαλώ σημειώστε ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες αλλαγές στο τελικό layout.

Τιμή:  true  αν [remove global text engine resource]; διαφορετικά,  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Λαμβάνει ή ορίζει τους πόρους του psd. Εάν η τιμή: NULL - τότε αποθηκεύει τους αρχικούς ImageResources (προεπιλεγμένη συμπεριφορά) Not Empty - τότε αποθηκεύει τους πόρους που περάστηκαν σε αυτήν την ιδιότητα + [required resources] Empty - τότε αποθηκεύονται μόνο [required resources]. Απαιτούμενοι πόροι: ResolutionInfoResource, XmpResource.

Τιμή: Οι πόροι του psd.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας.

Τιμή: Η πηγή για τη δημιουργία της εικόνας.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [update metadata]. Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας.

Τιμή:  true  αν [update metadata]; διαφορετικά,  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Λαμβάνει ή ορίζει την έκδοση αρχείου psd.

Τιμή: Η έκδοση αρχείου psd.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Λάβετε ή ορίστε το δοχείο δεδομένων XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Εμφανίζει αν η ιδιότητα ColorMode έχει ανατεθεί.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
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


Λαμβάνει ή ορίζει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως το μέγιστο επιτρεπόμενο μέγεθος για όλους τους εσωτερικούς buffers.

Τιμή: Η υπόδειξη μεγέθους buffer, σε megabytes. Μη θετική τιμή σημαίνει ότι δεν υπάρχει περιορισμός μνήμης για εσωτερικά buffers

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Λαμβάνει ή ορίζει τον αριθμό των bits ανά κανάλι χρώματος.

Τιμή: Ο αριθμός των bits ανά κανάλι χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος.

Τιμή: Ο αριθμός των καναλιών χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd.

Τιμή: Η λειτουργία χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd.

Τιμή: Η μέθοδος συμπίεσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB.

Τιμή: Η έκδοση μορφής αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD. Παρακαλώ σημειώστε ότι η σχεδίαση στρωμάτων κειμένου στο τελικό layout δεν υποστηρίζεται για την πλατφόρμα Compact Framework.

Τιμή:  true  αν [refresh image preview data]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν - Αφαίρεση του παγκόσμιου πόρου μηχανής κειμένου - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών). Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να εκτελέσει τα εξής στο αρχείο που άνοιξε στο Photoshop: Μενού "Text" -> "Process absent fonts". Μετά από αυτή τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά. Παρακαλώ σημειώστε ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες αλλαγές στο τελικό layout.

Τιμή:  true  αν [remove global text engine resource]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Λαμβάνει ή ορίζει τους πόρους του psd. Εάν η τιμή: NULL - τότε αποθηκεύει τους αρχικούς ImageResources (προεπιλεγμένη συμπεριφορά) Not Empty - τότε αποθηκεύει τους πόρους που περάστηκαν σε αυτήν την ιδιότητα + [required resources] Empty - τότε αποθηκεύονται μόνο [required resources]. Απαιτούμενοι πόροι: ResolutionInfoResource, XmpResource.

Τιμή: Οι πόροι του psd.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [update metadata]. Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας.

Τιμή:  true  αν [update metadata]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Λαμβάνει ή ορίζει τις επιλογές διανυσματικής rasterization.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση αρχείου psd.

Τιμή: Η έκδοση αρχείου psd.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Λάβετε ή ορίστε το δοχείο δεδομένων XMP

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

