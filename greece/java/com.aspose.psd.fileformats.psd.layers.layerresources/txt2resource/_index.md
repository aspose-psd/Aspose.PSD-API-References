---
title: "Txt2Resource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση πόρου Txt2"
type: docs
weight: 76
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

Κλάση πόρου Txt2
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource). |
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
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το αναγνωριστικό της εγγραφής κειμένου. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Λαμβάνει αν ο πόρος είναι συμπιεσμένος. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | Αναλύει τα δεδομένα txt2 σε μια παρουσία της κλάσης Txt2DataRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getTextData()](#getTextData--) | Λαμβάνει την εγγραφή κειμένου από τα δεδομένα του πόρου. |
| [getText_internalized()](#getText-internalized--) | Λαμβάνει ή ορίζει το όνομα. |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | Λαμβάνει το TXT2 από το αναλυμένο δέντρο. |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | Λαμβάνει το αναλυμένο δέντρο του TXT2. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | Αφαιρεί την εγγραφή κειμένου από το Resource. |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει το καθορισμένο δοχείο ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setData(byte[] value)](#setData-byte---) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | Ενημερώνει την εγγραφή κειμένου με το δείκτη κειμένου χρησιμοποιώντας νέα προεπιλεγμένα δεδομένα κειμένου και νέο κείμενο, μέγεθος γραμματοσειράς και χρώμα. |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | Ενημερώνει τα δεδομένα txt2 από το μοντέλο Txt2DataRoot. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource).

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

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το αναγνωριστικό της εγγραφής κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | Το κείμενο της εγγραφής. |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | Τα όρια. |

**Returns:**
int - Επιστρέφει το Id της εγγραφής κειμένου για το resource
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
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Λαμβάνει αν ο πόρος είναι συμπιεσμένος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δέντρο | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | Το δέντρο. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - Επιστρέφει αντικείμενο με κλειδιά.
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει το μήκος του πόρου της στρώσης σε bytes.

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


Αναλύει τα δεδομένα txt2 σε μια παρουσία της κλάσης Txt2DataRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - Τα δεδομένα txt2 ως παρουσία της κλάσης Txt2DataRoot.
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
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


Λαμβάνει την εγγραφή κειμένου από τα δεδομένα του πόρου.

**Returns:**
java.lang.String[] - Πίνακας εγγραφών κειμένου
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


Λαμβάνει ή ορίζει το όνομα.

Τιμή: Το όνομα.

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


Λαμβάνει το TXT2 από το αναλυμένο δέντρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δέντρο | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | Το δέντρο δεδομένων. |

**Returns:**
java.lang.String - Τα δεδομένα Txt2.
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


Λαμβάνει το αναλυμένο δέντρο του TXT2.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - Αναλυμένο δέντρο
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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


Αφαιρεί την εγγραφή κειμένου από το Resource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textIndex | int | Ο δείκτης της εγγραφής κειμένου προς αφαίρεση. |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Αποθηκεύει το καθορισμένο δοχείο ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής. |
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

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


Λαμβάνει ή ορίζει τα δεδομένα.

Τιμή: Τα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

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

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


Λαμβάνει ή ορίζει το όνομα.

Τιμή: Το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο.

**Returns:**
java.lang.String - Ένα String που αντιπροσωπεύει αυτήν την παρουσία.
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


Ενημερώνει την εγγραφή κειμένου με το δείκτη κειμένου χρησιμοποιώντας νέα προεπιλεγμένα δεδομένα κειμένου και νέο κείμενο, μέγεθος γραμματοσειράς και χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textIndex | int | Ο δείκτης της εγγραφής κειμένου στα δεδομένα πόρου txt2. |
| newText | java.lang.String | Το νέο κείμενο. |
| fontSize | double | το νέο μέγεθος γραμματοσειράς. |
| color | [Color](../../com.aspose.psd/color) | Το νέο χρώμα κειμένου. |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


Ενημερώνει τα δεδομένα txt2 από το μοντέλο Txt2DataRoot.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | Το μοντέλο δεδομένων txt2. |

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

