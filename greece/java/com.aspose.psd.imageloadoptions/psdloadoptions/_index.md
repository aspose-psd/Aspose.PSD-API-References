---
title: "PsdLoadOptions"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Επιλογές φόρτωσης Psd"
type: docs
weight: 12
url: /el/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Επιλογές φόρτωσης Psd
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Οι προσαρμοσμένες πηγές γραμματοσειρών |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του στρώματος κατά την απόδοση εάν το στρώμα δεν έχει τροποποιηθεί. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Λαμβάνει την υπόδειξη μεγέθους του buffer, η οποία ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Λαμβάνει το  Image  background  Color . |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Λαμβάνει τη λειτουργία ανάκτησης δεδομένων. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σταθερό πλάτος του στρώματος κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [load effects resource] (προεπιλογή: ο πόρος δεν φορτώνεται). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Λαμβάνει το χειριστή συμβάντος προόδου. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use disk for load effects resource] (προεπιλογή: χρησιμοποιείται δίσκος για τη φόρτωση των πόρων εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι αρκετή ορίζοντας αυτή την τιμή σε false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Λαμβάνει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του στρώματος κατά την απόδοση εάν το στρώμα δεν έχει τροποποιηθεί. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Ορίζει την υπόδειξη μεγέθους buffer, η οποία ορίζεται ως το μέγιστο επιτρεπτό μέγεθος για όλα τα εσωτερικά buffers. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Ορίζει το  Image  φόντο  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Ορίζει τη λειτουργία ανάκτησης δεδομένων. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σταθερό πλάτος του στρώματος κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [load effects resource] (προεπιλογή: ο πόρος δεν φορτώνεται). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Λαμβάνει ή ορίζει το memory MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ορίζει το χειριστή συμβάντος προόδου. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use disk for load effects resource] (προεπιλογή: χρησιμοποιείται δίσκος για τη φόρτωση των πόρων εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι αρκετή ορίζοντας αυτή την τιμή σε false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν πρέπει να εφαρμοστεί η μετατροπή προφίλ ICC. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Αυτό αποτελεί μέρος του προτύπου αδειοδότησης venture. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του στρώματος κατά την απόδοση εάν το στρώμα δεν έχει τροποποιηθεί.

Τιμή:  true  για διατήρηση των αρχικών pixel των αμετάβλητων στρωμάτων· διαφορετικά,  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση.

Τιμή:  true  απόδοση εικόνας με παραμόρφωση  false .

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
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [ignore alpha channel].

Τιμή:  true  εάν [ignore alpha channel]; διαφορετικά,  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σταθερό πλάτος του στρώματος κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText.

Τιμή:  true  εάν [ignore text layer width]; διαφορετικά,  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [load effects resource] (προεπιλογή: ο πόρος δεν φορτώνεται). Όταν οριστεί, μόνο τα υποστηριζόμενα εφέ θα αποδοθούν στην τελική συγχωνευμένη εικόνα.

Τιμή:  true  εάν [load effects resource]; διαφορετικά,  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Λαμβάνει το χειριστή συμβάντος προόδου.

Τιμή: Ο χειριστής συμβάντος προόδου.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use read only mode]. Αυτή είναι λειτουργία μόνο για ανάγνωση, υποστηριζόμενη για πλήρη συμβατότητα με το Adobe Photoshop. Όταν αυτή η επιλογή οριστεί, όλες οι αλλαγές που εφαρμόζονται στα στρώματα δεν θα αποθηκευτούν στην τελική εικόνα. Όλα τα δεδομένα χρησιμοποιούνται από την ενότητα ImageData, έτσι είναι πανομοιότυπα με το Photoshop. Προεπιλογή: όλες οι φορτωμένες εικόνες δεν είναι πλήρως συμβατές με το Adobe Photoshop.

Τιμή:  true  εάν [use photoshop compatibility mode]; διαφορετικά,  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD.

Τιμή: Μία από τις τιμές του ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use disk for load effects resource] (προεπιλογή: χρησιμοποιείται δίσκος για τη φόρτωση των πόρων εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι αρκετή ορίζοντας αυτή την τιμή σε false).

Τιμή:  true  εάν [use disk for load effects resource]; διαφορετικά,  false .

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Λαμβάνει ή ορίζει αν διατηρηθούν τα αρχικά pixel του στρώματος κατά την απόδοση εάν το στρώμα δεν έχει τροποποιηθεί.

Τιμή:  true  για διατήρηση των αρχικών pixel των αμετάβλητων στρωμάτων· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Λαμβάνει ή ορίζει αν αποθηκευτεί με την αποδοθείσα εικόνα, με ή χωρίς παραμόρφωση.

Τιμή:  true  απόδοση εικόνας με παραμόρφωση  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [ignore alpha channel].

Τιμή:  true  εάν [ignore alpha channel]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το σταθερό πλάτος του στρώματος κειμένου PSD θα αγνοηθεί κατά την εκτέλεση της λειτουργίας UpdateText.

Τιμή:  true  εάν [ignore text layer width]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [load effects resource] (προεπιλογή: ο πόρος δεν φορτώνεται). Όταν οριστεί, μόνο τα υποστηριζόμενα εφέ θα αποδοθούν στην τελική συγχωνευμένη εικόνα.

Τιμή:  true  εάν [load effects resource]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use read only mode]. Αυτή είναι λειτουργία μόνο για ανάγνωση, υποστηριζόμενη για πλήρη συμβατότητα με το Adobe Photoshop. Όταν αυτή η επιλογή οριστεί, όλες οι αλλαγές που εφαρμόζονται στα στρώματα δεν θα αποθηκευτούν στην τελική εικόνα. Όλα τα δεδομένα χρησιμοποιούνται από την ενότητα ImageData, έτσι είναι πανομοιότυπα με το Photoshop. Προεπιλογή: όλες οι φορτωμένες εικόνες δεν είναι πλήρως συμβατές με το Adobe Photoshop.

Τιμή:  true  εάν [use photoshop compatibility mode]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD.

Τιμή: Μία από τις τιμές του ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)):

 *  
 *  
 *  

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [use disk for load effects resource] (προεπιλογή: χρησιμοποιείται δίσκος για τη φόρτωση των πόρων εφέ, αλλά μπορεί να χρησιμοποιηθεί μνήμη εάν είναι αρκετή ορίζοντας αυτή την τιμή σε false).

Τιμή:  true  εάν [use disk for load effects resource]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

