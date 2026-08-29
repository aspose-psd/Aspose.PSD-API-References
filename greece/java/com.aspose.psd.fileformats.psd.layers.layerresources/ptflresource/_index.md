---
title: "PtFlResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση PtFlResource."
type: docs
weight: 72
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class PtFlResource extends FillLayerResource
```

Κλάση PtFlResource. Περιέχει δεδομένα στρώματος γεμίσματος προτύπου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PtFlResource()](#PtFlResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource). |
| [PtFlResource(String patternName, String patternId)](#PtFlResource-java.lang.String-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource). |
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
| [getAlignWithLayer()](#getAlignWithLayer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [getAngle()](#getAngle--) | Λαμβάνει ή ορίζει τη γωνία. |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getOffset()](#getOffset--) | Λαμβάνει ή ορίζει τη μετατόπιση. |
| [getPatternId()](#getPatternId--) | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| [getPatternName()](#getPatternName--) | Λαμβάνει ή ορίζει το όνομα του μοτίβου. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getScale()](#getScale--) | Λαμβάνει ή ορίζει την κλίμακα. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [hashCode()](#hashCode--) |  |
| [isLinkedWithLayer()](#isLinkedWithLayer--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Λαμβάνει ή ορίζει τη γωνία. |
| [setClassNameAndId_internalized(String className, ClassID classID)](#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Ορίζει το όνομα της κλάσης και το αναγνωριστικό. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setLinkedWithLayer(boolean value)](#setLinkedWithLayer-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα. |
| [setOffset(Point value)](#setOffset-com.aspose.psd.Point-) | Λαμβάνει ή ορίζει τη μετατόπιση. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα του μοτίβου. |
| [setScale(double value)](#setScale-double-) | Λαμβάνει ή ορίζει την κλίμακα. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PtFlResource() {#PtFlResource--}
```
public PtFlResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource).

### PtFlResource(String patternName, String patternId) {#PtFlResource-java.lang.String-java.lang.String-}
```
public PtFlResource(String patternName, String patternId)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PtFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/ptflresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| patternName | java.lang.String | Όνομα του μοτίβου. |
| patternId | java.lang.String | Το αναγνωριστικό προτύπου. |

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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Returns:**
double
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
### getOffset() {#getOffset--}
```
public final Point getOffset()
```


Λαμβάνει ή ορίζει τη μετατόπιση.

Τιμή: Η μετατόπιση.

**Returns:**
[Point](../../com.aspose.psd/point)
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου.

Τιμή: Το αναγνωριστικό του μοτίβου.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Λαμβάνει ή ορίζει το όνομα του μοτίβου.

Τιμή: Το όνομα του μοτίβου.

**Returns:**
java.lang.String
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
### getScale() {#getScale--}
```
public final double getScale()
```


Λαμβάνει ή ορίζει την κλίμακα.

Τιμή: Η κλίμακα.

**Returns:**
double
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
### isLinkedWithLayer() {#isLinkedWithLayer--}
```
public final boolean isLinkedWithLayer()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα.

Τιμή:  true  αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα· διαφορετικά,  false .

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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer].

Τιμή:  true  εάν [align with layer]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Λαμβάνει ή ορίζει τη γωνία.

Τιμή: Η γωνία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setClassNameAndId_internalized(String className, ClassID classID) {#setClassNameAndId-internalized-java.lang.String-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassNameAndId_internalized(String className, ClassID classID)
```


Ορίζει το όνομα της κλάσης και το αναγνωριστικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| className | java.lang.String | Όνομα της κλάσης. |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό της κλάσης. |

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

### setLinkedWithLayer(boolean value) {#setLinkedWithLayer-boolean-}
```
public final void setLinkedWithLayer(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα.

Τιμή:  true  αν αυτή η παρουσία είναι συνδεδεμένη με το στρώμα· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setOffset(Point value) {#setOffset-com.aspose.psd.Point-}
```
public final void setOffset(Point value)
```


Λαμβάνει ή ορίζει τη μετατόπιση.

Τιμή: Η μετατόπιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου.

Τιμή: Το αναγνωριστικό του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Λαμβάνει ή ορίζει το όνομα του μοτίβου.

Τιμή: Το όνομα του μοτίβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Λαμβάνει ή ορίζει την κλίμακα.

Τιμή: Η κλίμακα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

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

