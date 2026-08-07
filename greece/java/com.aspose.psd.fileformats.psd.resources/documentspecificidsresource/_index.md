---
title: "DocumentSpecificIdsResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Πόρος συγκεκριμένων αναγνωριστικών εγγράφου"
type: docs
weight: 16
url: /el/java/com.aspose.psd.fileformats.psd.resources/documentspecificidsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class DocumentSpecificIdsResource extends ResourceBlock
```

Πόρος συγκεκριμένων αναγνωριστικών εγγράφου
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DocumentSpecificIdsResource()](#DocumentSpecificIdsResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [DocumentSpecificIdsResource](../../com.aspose.psd.fileformats.psd.resources/documentspecificidsresource). |
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
| [getID()](#getID--) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [getId()](#getId--) | Αποκτά ή ορίζει το αναγνωριστικό. |
| [getMinimalVersion()](#getMinimalVersion--) | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream. |
| [setID(short value)](#setID-short-) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [setId(int value)](#setId-int-) | Αποκτά ή ορίζει το αναγνωριστικό. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Λαμβάνει ή ορίζει τις πληροφορίες layer και mask. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Επικυρώνει τις τιμές του πόρου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentSpecificIdsResource() {#DocumentSpecificIdsResource--}
```
public DocumentSpecificIdsResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [DocumentSpecificIdsResource](../../com.aspose.psd.fileformats.psd.resources/documentspecificidsresource).

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
### getID() {#getID--}
```
public final short getID()
```


Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο.

Τιμή: Το μοναδικό αναγνωριστικό για τον πόρο.

**Returns:**
short
### getId() {#getId--}
```
public final int getId()
```


Αποκτά ή ορίζει το αναγνωριστικό.

Τιμή: Το αναγνωριστικό.

**Returns:**
int
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

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Αποκτά ή ορίζει το αναγνωριστικό.

Τιμή: Το αναγνωριστικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

