---
title: "VersionInfoResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Πόρος πληροφοριών έκδοσης"
type: docs
weight: 41
url: /el/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

Πόρος πληροφοριών έκδοσης
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | Η υπογραφή πόρου του ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | Η κανονική υπογραφή πόρου του Photoshop. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Λαμβάνει το μέγεθος δεδομένων πόρου σε bytes. |
| [getFileVersion()](#getFileVersion--) | Αποκτά ή ορίζει την έκδοση του αρχείου. |
| [getID()](#getID--) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [getMinimalVersion()](#getMinimalVersion--) | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [getReaderName()](#getReaderName--) | Αποκτά ή ορίζει το όνομα του αναγνώστη. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [getWriterName()](#getWriterName--) | Αποκτά ή ορίζει το όνομα του συγγραφέα. |
| [hasRealMergedData()](#hasRealMergedData--) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream. |
| [setFileVersion(long value)](#setFileVersion-long-) | Αποκτά ή ορίζει την έκδοση του αρχείου. |
| [setID(short value)](#setID-short-) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Λαμβάνει ή ορίζει τις πληροφορίες layer και mask. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | Αποκτά ή ορίζει το όνομα του αναγνώστη. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου. |
| [setVersion(long value)](#setVersion-long-) | Λαμβάνει ή ορίζει την έκδοση. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | Αποκτά ή ορίζει το όνομα του συγγραφέα. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Επικυρώνει τις τιμές του πόρου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


Η υπογραφή πόρου του ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


Η κανονική υπογραφή πόρου του Photoshop.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Λαμβάνει το μέγεθος δεδομένων πόρου σε bytes.

Τιμή: Το μέγεθος δεδομένων του πόρου.

**Returns:**
int
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


Αποκτά ή ορίζει την έκδοση του αρχείου.

Τιμή: Η έκδοση του αρχείου.

**Returns:**
long
### getID() {#getID--}
```
public final short getID()
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο.

Τιμή: Το μοναδικό αναγνωριστικό για τον πόρο.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD.

Τιμή: Η ελάχιστη έκδοση PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, γεμισμένη ώστε το μέγεθος να είναι άρτιο (ένα μηδενικό όνομα αποτελείται από δύο byte του 0).

Τιμή: Το όνομα του πόρου.

**Returns:**
java.lang.String
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


Αποκτά ή ορίζει το όνομα του αναγνώστη.

Τιμή: Το όνομα του αναγνώστη.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Λαμβάνει την υπογραφή του πόρου. Θα πρέπει πάντα να είναι '8BIM'.

Τιμή: Η υπογραφή του πόρου.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του.

Τιμή: Το μέγεθος του μπλοκ πόρου.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


Αποκτά ή ορίζει το όνομα του συγγραφέα.

Τιμή: Το όνομα του συγγραφέα.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα.

Τιμή:  true  εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα· διαφορετικά,  false .

**Returns:**
boolean
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή για αποθήκευση του μπλοκ πόρου. |

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


Αποκτά ή ορίζει την έκδοση του αρχείου.

Τιμή: Η έκδοση του αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο.

Τιμή: Το μοναδικό αναγνωριστικό για τον πόρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Λαμβάνει ή ορίζει τις πληροφορίες layer και mask.

Τιμή: Οι πληροφορίες στρώματος και μάσκας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, γεμισμένη ώστε το μέγεθος να είναι άρτιο (ένα μηδενικό όνομα αποτελείται από δύο byte του 0).

Τιμή: Το όνομα του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


Αποκτά ή ορίζει το όνομα του αναγνώστη.

Τιμή: Το όνομα του αναγνώστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα.

Τιμή:  true  εάν αυτή η παρουσία έχει πραγματικά συγχωνευμένα δεδομένα· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υπογραφή | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου.

Τιμή: Η κατάσταση του μπλοκ πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


Αποκτά ή ορίζει το όνομα του συγγραφέα.

Τιμή: Το όνομα του συγγραφέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


Επικυρώνει τις τιμές του πόρου.

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

