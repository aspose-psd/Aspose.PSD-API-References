---
title: "DataStreamSupporter"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Το δοχείο ροής δεδομένων"
type: docs
weight: 38
url: /el/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Το δοχείο ροής δεδομένων
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Συμβαίνει όταν η εικόνα φορτώθηκε ή αποθηκεύτηκε |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Συμβαίνει όταν χρησιμοποιήθηκε η πίστωση |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [cacheData()](#cacheData--) | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer. |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Αποθηκεύει τα δεδομένα του αντικειμένου στον τρέχοντα  DataStreamSupporter . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(String filePath)](#save-java.lang.String-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ορίζει τη ροή δεδομένων του αντικειμένου. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ορίζει μια τιμή που υποδεικνύει αν [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και διασφαλίζει ότι δεν θα γίνει πρόσθετη φόρτωση δεδομένων από το υποκείμενο DataStreamSupporter.DataStreamContainer.

### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Λαμβάνει τη ροή δεδομένων του αντικειμένου.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Λαμβάνει τη διαδρομή αρχείου της πηγαίας εικόνας εάν υπάρχει. Επιστρέφει μια κενή συμβολοσειρά εάν δεν μπορεί να βρεθεί η πηγαία διαδρομή.

**Returns:**
java.lang.String - Η διαδρομή αρχείου της πηγαίας εικόνας.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης

Τιμή:  true  εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης· διαφορετικά,  false .

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν το αντικείμενο χρησιμοποιεί στρατηγική βελτιστοποίησης μνήμης
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Αποθηκεύει τα δεδομένα του αντικειμένου στον τρέχοντα  DataStreamSupporter .

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχείο | java.io.RandomAccessFile | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

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

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ορίζει τη ροή δεδομένων του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή δεδομένων του αντικειμένου. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει αν [ignore after save].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | true  εάν [ignore after save]; διαφορετικά,  false . |

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

