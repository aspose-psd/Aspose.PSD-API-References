---
title: "GraphCutMaskingOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές αυτόματης μάσκας GraphCut."
type: docs
weight: 14
url: /el/java/com.aspose.psd.masking.options/graphcutmaskingoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

Οι επιλογές αυτόματης μάσκας GraphCut.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Ο αριθμός του αντικειμένου φόντου |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Λαμβάνει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Λαμβάνει το χρώμα αντικατάστασης φόντου. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Λαμβάνει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο. |
| [getExportOptions()](#getExportOptions--) | Λαμβάνει τις επιλογές εξαγωγής εικόνας. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Λαμβάνει την ακτίνα θολώματος. |
| [getMaskingArea()](#getMaskingArea--) | Λαμβάνει την περιοχή μάσκας. |
| [getMethod()](#getMethod--) | Λαμβάνει τη μέθοδο τμηματοποίησης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Ορίζει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Ορίζει το χρώμα αντικατάστασης φόντου. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Ορίζει τις επιλογές εξαγωγής εικόνας. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Ορίζει την ακτίνα εξομάλυνσης. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Ορίζει την περιοχή μάσκας. |
| [setMethod(int value)](#setMethod-int-) | Ορίζει τη μέθοδο τμηματοποίησης. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Ο αριθμός του αντικειμένου φόντου

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Λαμβάνει τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

Τιμή: Τα επιχειρήματα για τον αλγόριθμο τμηματοποίησης.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Λαμβάνει το χρώμα αντικατάστασης φόντου.

Τιμή: Το χρώμα αντικατάστασης φόντου. Αυτό το χρώμα θα χρησιμοποιηθεί ως χρώμα φόντου στις τελικές εικόνες.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Λαμβάνει μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο.

Τιμή:  true  αν αποσυνθέσει· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει αν είναι περιττό να διαχωριστεί κάθε σχήμα από τη μάσκα ως μεμονωμένο αντικείμενο ή ως ενωμένο αντικείμενο από τη μάσκα, διαχωρισμένο από το φόντο.
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

