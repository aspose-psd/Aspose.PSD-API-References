---
title: "PhflResourceVersion2"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση PhflResource."
type: docs
weight: 69
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.PhflResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresource)
```
public class PhflResourceVersion2 extends PhflResource
```

Κλάση PhflResource. Πόρος του Επιπέδου Ρύθμισης Έκθεσης 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 bytes για κάθε χρώμα XYZ (Μόνο στην Έκδοση 3) 10 2 bytes χρωματικού χώρου ακολουθούμενα από 4 \* 2 bytes στοιχείο χρώματος (Μόνο στην Έκδοση 2) 4 Πυκνότητα 1 Διατήρηση Φωτεινότητας
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PhflResourceVersion2()](#PhflResourceVersion2--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
| [PhflResourceVersion2(byte[] data)](#PhflResourceVersion2-byte---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2). |
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
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Λαμβάνει το χρωματικό χώρο. |
| [getComponentA()](#getComponentA--) | Λαμβάνει ή ορίζει το στοιχείο A του χρώματος |
| [getComponentB()](#getComponentB--) | Λαμβάνει ή ορίζει το στοιχείο B |
| [getComponentL()](#getComponentL--) | Λαμβάνει ή ορίζει το στοιχείο L του χρώματος |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getDensity()](#getDensity--) | Λαμβάνει ή ορίζει την πυκνότητα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν [preserve luminosity]. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getRgbColor()](#getRgbColor--) | Λαμβάνει το χρώμα. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getVersion()](#getVersion--) | Αποκτά την έκδοση. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setColorSpace(short value)](#setColorSpace-short-) | Λαμβάνει το χρωματικό χώρο. |
| [setComponentA(short value)](#setComponentA-short-) | Λαμβάνει ή ορίζει το στοιχείο A του χρώματος |
| [setComponentB(short value)](#setComponentB-short-) | Λαμβάνει ή ορίζει το στοιχείο B |
| [setComponentL(short value)](#setComponentL-short-) | Λαμβάνει ή ορίζει το στοιχείο L του χρώματος |
| [setDensity(int value)](#setDensity-int-) | Λαμβάνει ή ορίζει την πυκνότητα. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν [preserve luminosity]. |
| [setRgbColor(Color color)](#setRgbColor-com.aspose.psd.Color-) | Ορίζει το χρώμα RGB. |
| [setVersion(short value)](#setVersion-short-) | Αποκτά την έκδοση. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhflResourceVersion2() {#PhflResourceVersion2--}
```
public PhflResourceVersion2()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

### PhflResourceVersion2(byte[] data) {#PhflResourceVersion2-byte---}
```
public PhflResourceVersion2(byte[] data)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](../../com.aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2).

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpace() {#getColorSpace--}
```
public final short getColorSpace()
```


Λαμβάνει το χρωματικό χώρο.

Τιμή: ο χρωματικός χώρος.

**Returns:**
short
### getComponentA() {#getComponentA--}
```
public final short getComponentA()
```


Λαμβάνει ή ορίζει το στοιχείο A του χρώματος

**Returns:**
short
### getComponentB() {#getComponentB--}
```
public final short getComponentB()
```


Λαμβάνει ή ορίζει το στοιχείο B

**Returns:**
short
### getComponentL() {#getComponentL--}
```
public final short getComponentL()
```


Λαμβάνει ή ορίζει το στοιχείο L του χρώματος

**Returns:**
short
### getData() {#getData--}
```
public final byte[] getData()
```


Λαμβάνει ή ορίζει τα δεδομένα.

Τιμή: Τα δεδομένα.

**Returns:**
byte[]
### getDensity() {#getDensity--}
```
public final int getDensity()
```


Λαμβάνει ή ορίζει την πυκνότητα.

Τιμή: Η πυκνότητα.

**Returns:**
int
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
### getPreserveLuminosity() {#getPreserveLuminosity--}
```
public final boolean getPreserveLuminosity()
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν [preserve luminosity].

Value:  true  εάν [preserve luminosity]; διαφορετικά,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για πόρο στρώσης. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί.

**Returns:**
int
### getRgbColor() {#getRgbColor--}
```
public Color getRgbColor()
```


Λαμβάνει το χρώμα.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB color
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getVersion() {#getVersion--}
```
public short getVersion()
```


Αποκτά την έκδοση.

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

### setColorSpace(short value) {#setColorSpace-short-}
```
public void setColorSpace(short value)
```


Λαμβάνει το χρωματικό χώρο.

Τιμή: ο χρωματικός χώρος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setComponentA(short value) {#setComponentA-short-}
```
public final void setComponentA(short value)
```


Λαμβάνει ή ορίζει το στοιχείο A του χρώματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setComponentB(short value) {#setComponentB-short-}
```
public final void setComponentB(short value)
```


Λαμβάνει ή ορίζει το στοιχείο B

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setComponentL(short value) {#setComponentL-short-}
```
public final void setComponentL(short value)
```


Λαμβάνει ή ορίζει το στοιχείο L του χρώματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setDensity(int value) {#setDensity-int-}
```
public final void setDensity(int value)
```


Λαμβάνει ή ορίζει την πυκνότητα.

Τιμή: Η πυκνότητα.

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

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν [preserve luminosity].

Value:  true  εάν [preserve luminosity]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRgbColor(Color color) {#setRgbColor-com.aspose.psd.Color-}
```
public void setRgbColor(Color color)
```


Ορίζει το χρώμα RGB.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Το χρώμα. |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Αποκτά την έκδοση.

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

