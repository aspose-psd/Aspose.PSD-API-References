---
title: "WorkingPathResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Πόρος διαδρομής εργασίας."
type: docs
weight: 43
url: /el/java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Πόρος διαδρομής εργασίας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource). |
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
| [getMinimalVersion()](#getMinimalVersion--) | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [getPaths()](#getPaths--) | Λαμβάνει ή ορίζει τις εγγραφές διαδρομής. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος του μπλοκ πόρου σε bytes, συμπεριλαμβανομένων των δεδομένων του. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη. |
| [isInverted()](#isInverted--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ανεστραμμένη. |
| [isNotLinked()](#isNotLinked--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία δεν είναι συνδεδεμένη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη. |
| [setID(short value)](#setID-short-) | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| [setInverted(boolean value)](#setInverted-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ανεστραμμένη. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Λαμβάνει ή ορίζει τις πληροφορίες layer και mask. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του πόρου. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία δεν είναι συνδεδεμένη. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Λαμβάνει ή ορίζει τις εγγραφές διαδρομής. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Λαμβάνει ή ορίζει την κατάσταση του μπλοκ πόρου. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει ή ορίζει την έκδοση. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Επικυρώνει τις τιμές του πόρου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataBytes | byte[] | Τα δεδομένα της διανυσματικής διαδρομής. |

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
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Λαμβάνει ή ορίζει τις εγγραφές διαδρομής.

Τιμή: Οι διαδρομές.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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
public final int getVersion()
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη.

Τιμή:  true  αν αυτή η παρουσία είναι απενεργοποιημένη· διαφορετικά,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ανεστραμμένη.

Τιμή:  true  αν αυτή η παρουσία είναι ανεστραμμένη· διαφορετικά,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία δεν είναι συνδεδεμένη.

Τιμή:  true  αν αυτή η παρουσία δεν είναι συνδεδεμένη· διαφορετικά,  false .

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Αποθηκεύει το μπλοκ πόρου στο καθορισμένο stream.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Η ροή για αποθήκευση του μπλοκ πόρου. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι απενεργοποιημένη.

Τιμή:  true  αν αυτή η παρουσία είναι απενεργοποιημένη· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ανεστραμμένη.

Τιμή:  true  αν αυτή η παρουσία είναι ανεστραμμένη· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία δεν είναι συνδεδεμένη.

Τιμή:  true  αν αυτή η παρουσία δεν είναι συνδεδεμένη· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Λαμβάνει ή ορίζει τις εγγραφές διαδρομής.

Τιμή: Οι διαδρομές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

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

