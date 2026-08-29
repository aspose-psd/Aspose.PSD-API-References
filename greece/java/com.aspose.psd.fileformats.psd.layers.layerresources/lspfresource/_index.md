---
title: "LspfResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ρυθμίσεις προστασίας στρώσης"
type: docs
weight: 57
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

Ρυθμίσεις προστασίας στρώσης
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
| [LspfResource()](#LspfResource--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Η υπογραφή πόρου ειδική για PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSD |
| [ResourceSignature](#ResourceSignature) | Η κοινή υπογραφή πόρου. |
| [TypeToolKey](#TypeToolKey) | Το κλειδί πληροφοριών τύπου εργαλείου 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | Η άδεια venture. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getLockType()](#getLockType--) | Λαμβάνει ή ορίζει τον τύπο του κλειδώματος. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο από σύνθεση. |
| [isPositionProtected()](#isPositionProtected--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο θέσης. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [isTransparencyProtected()](#isTransparencyProtected--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο διαφάνειας. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο από σύνθεση. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setLockType(int value)](#setLockType-int-) | Λαμβάνει ή ορίζει τον τύπο του κλειδώματος. |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο θέσης. |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο διαφάνειας. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource). Με προσαρμοσμένη ή άγνωστη τιμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα δεδομένα του πόρου. |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isTransparencyProtected | boolean | αν οριστεί σε  true  [είναι προστατευμένο διαφάνειας]. |
| isCompositeProtected | boolean | αν οριστεί σε  true  [είναι προστατευμένο σύνθεσης]. |
| isPositionProtected | boolean | αν οριστεί σε  true  [είναι προστατευμένο θέσης]. |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Η έκδοση κεφαλίδας PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Η υπογραφή πόρου ειδική για PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Η έκδοση κεφαλίδας PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Η κοινή υπογραφή πόρου.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Το κλειδί πληροφοριών τύπου εργαλείου 1819504742

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Η άδεια venture.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. Κάποιοι πόροι δεν αναγνωρίζονται προς το παρόν, αλλά διαθέτουμε πλήρη λίστα πόρων ειδικών για PSB που αλλάζουν τη συμπεριφορά τους κατά την αποθήκευση. Έτσι, πρέπει τουλάχιστον να ελέγξουμε αυτό στο UnknownResource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί. |

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Λαμβάνει το κλειδί πόρου της στρώσης.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει το μήκος του πόρου της στρώσης σε bytes.

**Returns:**
int
### getLockType() {#getLockType--}
```
public final int getLockType()
```


Λαμβάνει ή ορίζει τον τύπο του κλειδώματος.

Τιμή: Ο τύπος του κλειδώματος.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Λαμβάνει το μήκος του προθέματος. Η προεπιλεγμένη τιμή είναι 12 για πόρους 8BIM και 16 για 8B64.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| psdVersion | int | Η έκδοση PSD. |

**Returns:**
int - Το μήκος του προθέματος.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για πόρο στρώσης. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο από σύνθεση.

Τιμή:  true  εάν αυτή η παρουσία είναι σύνθετα προστατευμένη· διαφορετικά,  false .

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο θέσης.

Τιμή:  true  εάν αυτή η παρουσία είναι προστατευμένη θέσης· διαφορετικά,  false .

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Καθορίζει εάν ο πόρος είναι ειδικός για PSB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί του πόρου. |

**Returns:**
boolean -  true  αν ο πόρος είναι ειδικός για PSB· διαφορετικά,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB.

Τιμή:  true  αν αυτή η παρουσία είναι πόρος ειδικός για PSB· διαφορετικά,  false .

**Returns:**
boolean
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο διαφάνειας.

Τιμή:  true  εάν αυτή η παρουσία είναι προστατευμένη διαφάνειας· διαφορετικά,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psdVersion | int | Η έκδοση PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| υπογραφή | int | Η υπογραφή. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
| υπογραφή | int | Η υπογραφή. |
| isLengthLong | boolean | αν οριστεί σε  true  το μήκος είναι μεγάλο. |

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο από σύνθεση.

Τιμή:  true  εάν αυτή η παρουσία είναι σύνθετα προστατευμένη· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Λαμβάνει ή ορίζει τον τύπο του κλειδώματος.

Τιμή: Ο τύπος του κλειδώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο θέσης.

Τιμή:  true  εάν αυτή η παρουσία είναι προστατευμένη θέσης· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι προστατευμένο διαφάνειας.

Τιμή:  true  εάν αυτή η παρουσία είναι προστατευμένη διαφάνειας· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο.

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει αυτήν την παρουσία.
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

