---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές αυτόματης μάσκας GraphCut."
type: docs
weight: 12
url: /el/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Οι επιλογές αυτόματης μάσκας GraphCut.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Αρχικοποιεί μια νέα παρουσία της [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) κλάσης. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Ο αριθμός του αντικειμένου φόντου |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Προσθέτει τα επιχειρήματα αυτόματης μάσκας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Συμπληρώνει τις προεπιλεγμένες γραμμές. |
| [getArgs()](#getArgs--) | Λαμβάνει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης. |
| [getAssumedObjects()](#getAssumedObjects--) | Λαμβάνει τα υποτιθέμενα αντικείμενα. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Λαμβάνει το χρώμα αντικατάστασης φόντου. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν οι προεπιλεγμένες γραμμές. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Λαμβάνει το ορθογώνιο των συνδυασμένων αντικειμένων. |
| [getDecompose()](#getDecompose--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Λαμβάνει τις προεπιλεγμένες γραμμές φόντου. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Λαμβάνει τις προ-υπολογισμένες προεπιλεγμένες γραμμές προσκηνίου. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Λαμβάνει τα προεπιλεγμένα ορθογώνια των αντικειμένων. |
| [getExportOptions()](#getExportOptions--) | Λαμβάνει τις επιλογές εξαγωγής εικόνας. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Λαμβάνει την ακτίνα θολώματος. |
| [getMaskingArea()](#getMaskingArea--) | Λαμβάνει την περιοχή μάσκας. |
| [getMethod()](#getMethod--) | Λαμβάνει τη μέθοδο τμηματοποίησης. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Λαμβάνει τον διαχειριστή συμβάντος προόδου της διαδικασίας προ-υπολογισμού των προεπιλεγμένων σημείων. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Ορίζει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Ορίζει τα υποτιθέμενα αντικείμενα. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Ορίζει το χρώμα αντικατάστασης φόντου. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν οι προεπιλεγμένες γραμμές. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Το ορθογώνιο των συνδυασμένων αντικειμένων. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Τα προεπιλεγμένα στίγματα φόντου. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Τα προ-υπολογισμένα προεπιλεγμένα στίγματα προσκηνίου. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Τα προεπιλεγμένα ορθογώνια αντικειμένων. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Ορίζει τις επιλογές εξαγωγής εικόνας. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Ορίζει την ακτίνα εξομάλυνσης. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Ορίζει την περιοχή μάσκας. |
| [setMethod(int value)](#setMethod-int-) | Ορίζει τη μέθοδο τμηματοποίησης. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ορίζει τον προεπιλεγμένο διαχειριστή συμβάντος προόδου της διαδικασίας προ-υπολογισμού σημείων. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Αρχικοποιεί μια νέα παρουσία της [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) κλάσης.

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Ο αριθμός του αντικειμένου φόντου

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Προσθέτει τα επιχειρήματα αυτόματης μάσκας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Συμπληρώνει τις προεπιλεγμένες γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Η εικόνα. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Λαμβάνει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

Τιμή: Τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Λαμβάνει τα υποτιθέμενα αντικείμενα.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - τα υποτιθέμενα αντικείμενα.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Λαμβάνει το χρώμα αντικατάστασης φόντου.

Τιμή: Το χρώμα αντικατάστασης φόντου. Αυτό το χρώμα θα χρησιμοποιηθεί ως χρώμα φόντου στις τελικές εικόνες.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν οι προεπιλεγμένες γραμμές.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν τα προεπιλεγμένα στίγματα.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Λαμβάνει το ορθογώνιο των συνδυασμένων αντικειμένων.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Λαμβάνει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο.

Τιμή:  true  αν αποσυνθέσει· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Λαμβάνει τις προεπιλεγμένες γραμμές φόντου.

**Returns:**
com.aspose.psd.Point[] - τα προεπιλεγμένα στίγματα φόντου.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Λαμβάνει τις προ-υπολογισμένες προεπιλεγμένες γραμμές προσκηνίου.

**Returns:**
com.aspose.psd.Point[] - τα προ-υπολογισμένα προεπιλεγμένα στίγματα προσκηνίου.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Λαμβάνει τα προεπιλεγμένα ορθογώνια των αντικειμένων.

**Returns:**
com.aspose.psd.Rectangle[] - τα προεπιλεγμένα ορθογώνια αντικειμένων.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Λαμβάνει τις επιλογές εξαγωγής εικόνας.

Τιμή: Οι επιλογές εξαγωγής εικόνας που θα χρησιμοποιηθούν για τη δημιουργία των τελικών εικόνων.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Λαμβάνει την ακτίνα θολώματος.

**Returns:**
int - η ακτίνα εξομάλυνσης.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Λαμβάνει την περιοχή μάσκας.

Τιμή: Η περιοχή μάσκας που είναι μια μερική περιοχή της πηγαίας εικόνας. Η τιμή Rectangle.Empty σημαίνει πλήρη περιοχή πηγαίας εικόνας.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Λαμβάνει τη μέθοδο τμηματοποίησης.

Τιμή: Η μέθοδος τμηματοποίησης.

**Returns:**
int - η μέθοδος τμηματοποίησης.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Λαμβάνει τον διαχειριστή συμβάντος προόδου της διαδικασίας προ-υπολογισμού των προεπιλεγμένων σημείων.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Ορίζει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

Τιμή: Τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Ορίζει τα υποτιθέμενα αντικείμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | τα υποτιθέμενα αντικείμενα. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Ορίζει το χρώμα αντικατάστασης φόντου.

Τιμή: Το χρώμα αντικατάστασης φόντου. Αυτό το χρώμα θα χρησιμοποιηθεί ως χρώμα φόντου στις τελικές εικόνες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | το χρώμα αντικατάστασης φόντου. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν οι προεπιλεγμένες γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν πρέπει να υπολογιστούν τα προεπιλεγμένα στίγματα. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Το ορθογώνιο των συνδυασμένων αντικειμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | το συνδυασμένο ορθογώνιο αντικειμένων. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο.

Τιμή:  true  αν αποσυνθέσει· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν είναι περιττό να διαχωριστεί κάθε Shape από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενιαίο αντικείμενο από τη μάσκα που διαχωρίζεται από το φόντο. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Τα προεπιλεγμένα στίγματα φόντου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | τα προεπιλεγμένα στίγματα φόντου. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Τα προ-υπολογισμένα προεπιλεγμένα στίγματα προσκηνίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | τα προ-υπολογισμένα προεπιλεγμένα στίγματα προσκηνίου. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Τα προεπιλεγμένα ορθογώνια αντικειμένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | τα προεπιλεγμένα ορθογώνια αντικειμένων. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Ορίζει τις επιλογές εξαγωγής εικόνας.

Τιμή: Οι επιλογές εξαγωγής εικόνας που θα χρησιμοποιηθούν για τη δημιουργία των τελικών εικόνων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | οι επιλογές εξαγωγής εικόνας. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Ορίζει την ακτίνα εξομάλυνσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | η ακτίνα εξομάλυνσης. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν η συλλογή υποτιθέμενων αντικειμένων περιέχει ανθρώπινα αντικείμενα. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Ορίζει την περιοχή μάσκας.

Τιμή: Η περιοχή μάσκας που είναι μια μερική περιοχή της πηγαίας εικόνας. Η τιμή Rectangle.Empty σημαίνει πλήρη περιοχή πηγαίας εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | η περιοχή μάσκας. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Ορίζει τη μέθοδο τμηματοποίησης.

Τιμή: Η μέθοδος τμηματοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | η μέθοδος τμηματοποίησης. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Ορίζει τον προεπιλεγμένο διαχειριστή συμβάντος προόδου της διαδικασίας προ-υπολογισμού σημείων.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | ο προεπιλεγμένος διαχειριστής συμβάντος προόδου της διαδικασίας προ-υπολογισμού σημείων. |

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

