---
title: "CgEdResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση CgEdResource."
type: docs
weight: 18
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class CgEdResource extends AdjustmentLayerResource
```

Κλάση CgEdResource. Πρόσθετα δεδομένα δημιουργού περιεχομένου (Photoshop CS5)
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CgEdResource()](#CgEdResource--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). |
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
| [getAuto()](#getAuto--) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) είναι αυτόματο. |
| [getBrightness()](#getBrightness--) | Λαμβάνει ή ορίζει το brightness. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Λαμβάνει ή ορίζει την αντίθεση. |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLabColor()](#getLabColor--) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται το [lab color]. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getMeanValueForBrightnessAndContrast()](#getMeanValueForBrightnessAndContrast--) | Ανακτά ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPropertyValueByTypeStructure_internalized(String structureName)](#getPropertyValueByTypeStructure-internalized-java.lang.String-) | Ανακτά την τιμή της ιδιότητας με βάση τη δομή τύπου. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getUseLegacy()](#getUseLegacy--) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται [use legacy]. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setAuto(boolean value)](#setAuto-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) είναι αυτόματο. |
| [setBrightness(int value)](#setBrightness-int-) | Λαμβάνει ή ορίζει το brightness. |
| [setContrast(int value)](#setContrast-int-) | Λαμβάνει ή ορίζει την αντίθεση. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setLabColor(boolean value)](#setLabColor-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται το [lab color]. |
| [setMeanValueForBrightnessAndContrast(int value)](#setMeanValueForBrightnessAndContrast-int-) | Ανακτά ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ορίζει την τιμή της ιδιότητας με δομή τύπου. |
| [setUseLegacy(boolean value)](#setUseLegacy-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται [use legacy]. |
| [setVersion(int value)](#setVersion-int-) | Λαμβάνει ή ορίζει την έκδοση. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgEdResource() {#CgEdResource--}
```
public CgEdResource()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource). Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 4 Έκδοση Περιγραφέα (= 16) Περιγραφέας μεταβλητού μήκους επιπλέον δεδομένων. Πρόταση: μπορεί να μην χρησιμοποιείται σε παλαιότερες εκδόσεις του PS (πριν το CS5).

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
### getAuto() {#getAuto--}
```
public final boolean getAuto()
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) είναι αυτόματο.

Τιμή:  true  εάν αυτόματο; διαφορετικά,  false .

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Λαμβάνει ή ορίζει το brightness.

Τιμή: Το brightness.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public final int getContrast()
```


Λαμβάνει ή ορίζει την αντίθεση.

Τιμή: η αντίθεση.

**Returns:**
int
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
### getLabColor() {#getLabColor--}
```
public final boolean getLabColor()
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται το [lab color].

Τιμή:  true  εάν χρησιμοποιείται [lab color]; διαφορετικά,  false .

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει το μήκος του πόρου της στρώσης σε bytes.

**Returns:**
int
### getMeanValueForBrightnessAndContrast() {#getMeanValueForBrightnessAndContrast--}
```
public final int getMeanValueForBrightnessAndContrast()
```


Ανακτά ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση.

Τιμή: Η μέση τιμή για τη φωτεινότητα και την αντίθεση.

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
### getPropertyValueByTypeStructure_internalized(String structureName) {#getPropertyValueByTypeStructure-internalized-java.lang.String-}
```
public final Object getPropertyValueByTypeStructure_internalized(String structureName)
```


Λαμβάνει την τιμή της ιδιότητας με δομή τύπου. Χρησιμοποιείται μόνο για UnitTests.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structureName | java.lang.String | Όνομα της δομής. |

**Returns:**
java.lang.Object - δομή OSType για εύκολη unit-testing
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
### getUseLegacy() {#getUseLegacy--}
```
public final boolean getUseLegacy()
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται [use legacy].

Τιμή:  true  εάν [use legacy]; διαφορετικά,  false .

**Returns:**
boolean
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

### setAuto(boolean value) {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν αυτό το [CgEdResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/cgedresource) είναι αυτόματο.

Τιμή:  true  εάν αυτόματο; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Λαμβάνει ή ορίζει το brightness.

Τιμή: Το brightness.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Λαμβάνει ή ορίζει την αντίθεση.

Τιμή: η αντίθεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

### setLabColor(boolean value) {#setLabColor-boolean-}
```
public final void setLabColor(boolean value)
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται το [lab color].

Τιμή:  true  εάν χρησιμοποιείται [lab color]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMeanValueForBrightnessAndContrast(int value) {#setMeanValueForBrightnessAndContrast-int-}
```
public final void setMeanValueForBrightnessAndContrast(int value)
```


Ανακτά ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση.

Τιμή: Η μέση τιμή για τη φωτεινότητα και την αντίθεση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Ορίζει την τιμή της ιδιότητας με δομή τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Η δομή. |

### setUseLegacy(boolean value) {#setUseLegacy-boolean-}
```
public final void setUseLegacy(boolean value)
```


Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν χρησιμοποιείται [use legacy].

Τιμή:  true  εάν [use legacy]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

