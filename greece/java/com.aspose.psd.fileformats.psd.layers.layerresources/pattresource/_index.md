---
title: "PattResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση PattResource."
type: docs
weight: 66
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class PattResource extends LayerResource
```

Κλάση PattResource. Πόρος με δεδομένα μοτίβου
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PattResource()](#PattResource--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource). |
| [PattResource(int key, PattResourceData[] patterns)](#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Η υπογραφή πόρου ειδική για PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSD |
| [ResourceSignature](#ResourceSignature) | Η κοινή υπογραφή πόρου. |
| [TypeToolKey](#TypeToolKey) | Το κλειδί πληροφοριών εργαλείου τύπου 'Patt' για 8-bit. |
| [TypeToolKey2](#TypeToolKey2) | Το κλειδί πληροφοριών εργαλείου τύπου 'Pat2' για 16-bit. |
| [TypeToolKey3](#TypeToolKey3) | Το κλειδί πληροφοριών εργαλείου τύπου 'Pat3' για 32-bit. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Η άδεια venture. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addNewPattResourceData_internalized(PattResource resource)](#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Ενημερώνει τον πόρο Patt με προεπιλεγμένα δεδομένα. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [createDefaultNotEmptyResource_internalized(int bitDepth)](#createDefaultNotEmptyResource-internalized-int-) | Δημιουργεί τον προεπιλεγμένο μη κενό πόρο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getPatterns()](#getPatterns--) | Ανακτά ή ορίζει τα δεδομένα μοτίβων· |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τα δεδομένα του μπλοκ πόρων. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setPatterns(PattResourceData[] value)](#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---) | Ανακτά ή ορίζει τα δεδομένα μοτίβων· |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [updateOrAddPattern_internalized(IPatternFillSettings patternSettings)](#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-) | Αναζητά το στοιχείο δεδομένων μοτίβου και το ενημερώνει με νέο, διαφορετικά, προσθέτει νέο στο τέλος του πίνακα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResource() {#PattResource--}
```
public PattResource()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).

### PattResource(int key, PattResourceData[] patterns) {#PattResource-int-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public PattResource(int key, PattResourceData[] patterns)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί τύπου πόρου. |
| patterns | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Τα δεδομένα μοτίβων. |

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


Το κλειδί πληροφοριών εργαλείου τύπου 'Patt' για 8-bit.

### TypeToolKey2 {#TypeToolKey2}
```
public static final int TypeToolKey2
```


Το κλειδί πληροφοριών εργαλείου τύπου 'Pat2' για 16-bit.

### TypeToolKey3 {#TypeToolKey3}
```
public static final int TypeToolKey3
```


Το κλειδί πληροφοριών εργαλείου τύπου 'Pat3' για 32-bit.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Η άδεια venture.

### addNewPattResourceData_internalized(PattResource resource) {#addNewPattResourceData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public static void addNewPattResourceData_internalized(PattResource resource)
```


Ενημερώνει τον πόρο Patt με προεπιλεγμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) | Ο πόρος. |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. Κάποιοι πόροι δεν αναγνωρίζονται προς το παρόν, αλλά διαθέτουμε πλήρη λίστα πόρων ειδικών για PSB που αλλάζουν τη συμπεριφορά τους κατά την αποθήκευση. Έτσι, πρέπει τουλάχιστον να ελέγξουμε αυτό στο UnknownResource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | int | Το κλειδί. |

### createDefaultNotEmptyResource_internalized(int bitDepth) {#createDefaultNotEmptyResource-internalized-int-}
```
public static PattResource createDefaultNotEmptyResource_internalized(int bitDepth)
```


Δημιουργεί τον προεπιλεγμένο μη κενό πόρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitDepth | int |  |

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - Created [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource)
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
### getPatterns() {#getPatterns--}
```
public final PattResourceData[] getPatterns()
```


Ανακτά ή ορίζει τα δεδομένα μοτίβων·

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData[]
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


Αποθηκεύει τα δεδομένα του μπλοκ πόρων.

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

### setPatterns(PattResourceData[] value) {#setPatterns-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData---}
```
public final void setPatterns(PattResourceData[] value)
```


Ανακτά ή ορίζει τα δεδομένα μοτίβων·

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PattResourceData\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο.

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει αυτήν την παρουσία.
### updateOrAddPattern_internalized(IPatternFillSettings patternSettings) {#updateOrAddPattern-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings-}
```
public final void updateOrAddPattern_internalized(IPatternFillSettings patternSettings)
```


Αναζητά το στοιχείο δεδομένων μοτίβου και το ενημερώνει με νέο, διαφορετικά, προσθέτει νέο στο τέλος του πίνακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| patternSettings | [IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings) | Το αντικείμενο ρυθμίσεων μοτίβων για την ενημέρωση του στοιχείου μοτίβου. |

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

