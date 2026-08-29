---
title: "PngLoadOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι επιλογές φόρτωσης png."
type: docs
weight: 11
url: /el/java/com.aspose.psd.imageloadoptions/pngloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

Οι επιλογές φόρτωσης png.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης PngLoadOptions. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Οι προσαρμοσμένες πηγές γραμματοσειρών |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Λαμβάνει το  Image  background  Color . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Λαμβάνει τη λειτουργία ανάκτησης δεδομένων. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν [ignore after load]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει το χειριστή συμβάντος προόδου. |
| [getStrictMode()](#getStrictMode--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode]. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Ορίζει το  Image  φόντο  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Ορίζει τη λειτουργία ανάκτησης δεδομένων. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [ignore after load]. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Λαμβάνει ή ορίζει το memory MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ορίζει το χειριστή συμβάντος προόδου. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode]. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης PngLoadOptions.

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Οι προσαρμοσμένες πηγές γραμματοσειρών

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
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Λαμβάνει το  Image  background  Color .

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Κανονικά το χρώμα φόντου ορίζεται όποτε η τιμή του pixel δεν μπορεί να ανακτηθεί λόγω κατεστραμμένων δεδομένων.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Λαμβάνει τη λειτουργία ανάκτησης δεδομένων.

**Returns:**
int - Η λειτουργία ανάκτησης δεδομένων.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν [ignore after load].

**Returns:**
boolean -  true  εάν [ignore after load]; διαφορετικά,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει το χειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode].

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode].
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. Αυτή η τιμή θα οριστεί από το VentureLicenser εάν το venture μας παρέχει ένα αντικείμενο LoadOptions.

**Returns:**
java.lang.Object
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

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Ορίζει το  Image  φόντο  Color .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Το χρώμα φόντου. |

Κανονικά το χρώμα φόντου ορίζεται όποτε η τιμή του pixel δεν μπορεί να ανακτηθεί λόγω κατεστραμμένων δεδομένων. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Ορίζει τη λειτουργία ανάκτησης δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η λειτουργία ανάκτησης δεδομένων |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν [ignore after load].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν [ignore after load]; διαφορετικά,  false . |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Λαμβάνει ή ορίζει το memory MGR.

Τιμή: Η μνήμη MGR.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Ορίζει το χειριστή συμβάντος προόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | ο χειριστής συμβάντος προόδου. |

### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν είναι ενεργή η [strict mode]. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. Αυτή η τιμή θα οριστεί από το VentureLicenser εάν το venture μας παρέχει ένα αντικείμενο LoadOptions.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object |  |

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

