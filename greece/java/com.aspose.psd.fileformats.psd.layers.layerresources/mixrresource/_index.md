---
title: "MixrResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση MixrResource."
type: docs
weight: 61
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public final class MixrResource extends AdjustmentLayerResource
```

Κλάση MixrResource. Πόρος του Στρώματος προσαρμογής Channel Mixer
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MixrResource()](#MixrResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource). |
| [MixrResource(byte[] data)](#MixrResource-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Η υπογραφή πόρου ειδική για PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSD |
| [ResourceSignature](#ResourceSignature) | Η κοινή υπογραφή πόρου. |
| [TypeToolKey](#TypeToolKey) | Το κλειδί πληροφοριών εργαλείου τύπου. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Η άδεια venture. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelInfo(int channelIndex)](#getChannelInfo-int-) | Λαμβάνει τα ακατέργαστα δεδομένα πληροφοριών καναλιού. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getMonochrome()](#getMonochrome--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) είναι μονόχρωμο. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setChannelInfo(int channelIndex, byte[] value)](#setChannelInfo-int-byte---) | Ορίζει τις πληροφορίες καναλιού. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setMonochrome(boolean value)](#setMonochrome-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) είναι μονόχρωμο. |
| [setVersion(short value)](#setVersion-short-) | Λαμβάνει ή ορίζει την έκδοση. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MixrResource() {#MixrResource--}
```
public MixrResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource). Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 2 Έκδοση ( = 1) 2 Μονόχρωμο 20 RGB ή CMYK χρώμα συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 byte χρώματος με 2 byte σταθερά.

### MixrResource(byte[] data) {#MixrResource-byte---}
```
public MixrResource(byte[] data)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource). Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 2 Έκδοση ( = 1) 2 Μονόχρωμο 20 RGB ή CMYK χρώμα συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 byte χρώματος με 2 byte σταθερά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] | Τα δεδομένα του πόρου. |

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


Το κλειδί πληροφοριών εργαλείου τύπου.

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
### getChannelInfo(int channelIndex) {#getChannelInfo-int-}
```
public final byte[] getChannelInfo(int channelIndex)
```


Λαμβάνει τα ακατέργαστα δεδομένα πληροφοριών καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |

**Returns:**
byte[] - Ακατέργαστος πίνακας byte των πληροφοριών καναλιού.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public final byte[] getData()
```


Λαμβάνει ή ορίζει τα δεδομένα.

Τιμή: Τα δεδομένα.

**Returns:**
byte[]
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
### getMonochrome() {#getMonochrome--}
```
public final boolean getMonochrome()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) είναι μονόχρωμο.

Τιμή:  true  εάν είναι μονόχρωμο· διαφορετικά,  false .

**Returns:**
boolean
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
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση. Η προεπιλεγμένη τιμή είναι 1

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setChannelInfo(int channelIndex, byte[] value) {#setChannelInfo-int-byte---}
```
public final void setChannelInfo(int channelIndex, byte[] value)
```


Ορίζει τις πληροφορίες καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| τιμή | byte[] | Η τιμή. |

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

### setMonochrome(boolean value) {#setMonochrome-boolean-}
```
public final void setMonochrome(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) είναι μονόχρωμο.

Τιμή:  true  εάν είναι μονόχρωμο· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση. Η προεπιλεγμένη τιμή είναι 1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

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

