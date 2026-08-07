---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι πληροφορίες του εργαλείου τύπου."
type: docs
weight: 79
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

Οι πληροφορίες του εργαλείου τύπου. Για έκδοση PSD μικρότερη από 6.0.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
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
| [getAComponent()](#getAComponent--) | Λαμβάνει ή ορίζει ένα στοιχείο. |
| [getBComponent()](#getBComponent--) | Λαμβάνει ή ορίζει το στοιχείο b. |
| [getCharacterCount()](#getCharacterCount--) | Λαμβάνει ή ορίζει τον αριθμό χαρακτήρων. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Λαμβάνει ή ορίζει την τιμή του χρωματικού χώρου. |
| [getFontVersion()](#getFontVersion--) | Ανακτά ή ορίζει την έκδοση γραμματοσειράς. |
| [getFonts()](#getFonts--) | Λαμβάνει ή ορίζει τις γραμματοσειρές. |
| [getFontsCount()](#getFontsCount--) | Λαμβάνει τον αριθμό των γραμματοσειρών. |
| [getGComponent()](#getGComponent--) | Λαμβάνει ή ορίζει το στοιχείο g. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Λαμβάνει ή ορίζει την οριζόντια τοποθέτηση. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getLineCount()](#getLineCount--) | Λαμβάνει τον αριθμό των γραμμών. |
| [getLines()](#getLines--) | Λαμβάνει ή ορίζει τις γραμμές. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getRComponent()](#getRComponent--) | Λαμβάνει ή ορίζει το στοιχείο r. |
| [getScaleFactor()](#getScaleFactor--) | Λαμβάνει ή ορίζει τον συντελεστή κλίμακας. |
| [getSelectionEnd()](#getSelectionEnd--) | Λαμβάνει ή ορίζει το τέλος της επιλογής. |
| [getSelectionStart()](#getSelectionStart--) | Λαμβάνει ή ορίζει την αρχή επιλογής. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getStyles()](#getStyles--) | Λαμβάνει ή ορίζει τα στυλ γραμματοσειράς. |
| [getStylesCount()](#getStylesCount--) | Λαμβάνει τον αριθμό των στυλ. |
| [getTransformMatrix()](#getTransformMatrix--) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| [getTypeValue()](#getTypeValue--) | Λαμβάνει ή ορίζει την τιμή τύπου. |
| [getVersion()](#getVersion--) | Λαμβάνει ή ορίζει την έκδοση. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Λαμβάνει ή ορίζει την κατακόρυφη τοποθέτηση. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει το καθορισμένο δοχείο ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setAComponent(short value)](#setAComponent-short-) | Λαμβάνει ή ορίζει ένα στοιχείο. |
| [setBComponent(short value)](#setBComponent-short-) | Λαμβάνει ή ορίζει το στοιχείο b. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Λαμβάνει ή ορίζει τον αριθμό χαρακτήρων. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Λαμβάνει ή ορίζει τα ακατέργαστα δεδομένα χρώματος. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Λαμβάνει ή ορίζει την τιμή του χρωματικού χώρου. |
| [setFontVersion(short value)](#setFontVersion-short-) | Ανακτά ή ορίζει την έκδοση γραμματοσειράς. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Λαμβάνει ή ορίζει τις γραμματοσειρές. |
| [setGComponent(short value)](#setGComponent-short-) | Λαμβάνει ή ορίζει το στοιχείο g. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Λαμβάνει ή ορίζει την οριζόντια τοποθέτηση. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Λαμβάνει ή ορίζει τις γραμμές. |
| [setRComponent(short value)](#setRComponent-short-) | Λαμβάνει ή ορίζει το στοιχείο r. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Λαμβάνει ή ορίζει τον συντελεστή κλίμακας. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Λαμβάνει ή ορίζει το τέλος της επιλογής. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Λαμβάνει ή ορίζει την αρχή επιλογής. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Λαμβάνει ή ορίζει τα στυλ γραμματοσειράς. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| [setTypeValue(short value)](#setTypeValue-short-) | Λαμβάνει ή ορίζει την τιμή τύπου. |
| [setVersion(short value)](#setVersion-short-) | Λαμβάνει ή ορίζει την έκδοση. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Λαμβάνει ή ορίζει την κατακόρυφη τοποθέτηση. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Λαμβάνει ή ορίζει ένα στοιχείο.

Τιμή: ένα στοιχείο.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Λαμβάνει ή ορίζει το στοιχείο b.

Τιμή: Το στοιχείο b.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Λαμβάνει ή ορίζει τον αριθμό χαρακτήρων.

Τιμή: Ο αριθμός χαρακτήρων.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


Λαμβάνει ή ορίζει την τιμή του χρωματικού χώρου.

Τιμή: Η τιμή του χρωματικού χώρου.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Ανακτά ή ορίζει την έκδοση γραμματοσειράς.

Τιμή: Η έκδοση γραμματοσειράς.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Λαμβάνει ή ορίζει τις γραμματοσειρές.

Τιμή: Οι γραμματοσειρές.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Λαμβάνει τον αριθμό των γραμματοσειρών.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Λαμβάνει ή ορίζει το στοιχείο g.

Τιμή: Το στοιχείο g.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Λαμβάνει ή ορίζει την οριζόντια τοποθέτηση.

Τιμή: Η οριζόντια τοποθέτηση.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Λαμβάνει τον αριθμό των γραμμών.

Τιμή: Ο αριθμός γραμμών.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Λαμβάνει ή ορίζει τις γραμμές.

Τιμή: Οι γραμμές.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Λαμβάνει ή ορίζει το στοιχείο r.

Τιμή: Το στοιχείο r.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Λαμβάνει ή ορίζει τον συντελεστή κλίμακας.

Τιμή: Ο συντελεστής κλίμακας.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Λαμβάνει ή ορίζει το τέλος της επιλογής.

Τιμή: Το τέλος επιλογής.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Λαμβάνει ή ορίζει την αρχή επιλογής.

Τιμή: Η αρχή επιλογής.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Λαμβάνει ή ορίζει τα στυλ γραμματοσειράς.

Τιμή: Τα στυλ γραμματοσειράς.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Λαμβάνει τον αριθμό των στυλ.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού.

Τιμή: Ο μετασχηματιστικός πίνακας.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Λαμβάνει ή ορίζει την τιμή τύπου.

Τιμή: Η τιμή τύπου.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Λαμβάνει ή ορίζει την κατακόρυφη τοποθέτηση.

Τιμή: Η κατακόρυφη τοποθέτηση.

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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Λαμβάνει ή ορίζει ένα στοιχείο.

Τιμή: ένα στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Λαμβάνει ή ορίζει το στοιχείο b.

Τιμή: Το στοιχείο b.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Λαμβάνει ή ορίζει τον αριθμό χαρακτήρων.

Τιμή: Ο αριθμός χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Λαμβάνει ή ορίζει τα ακατέργαστα δεδομένα χρώματος.

Τιμή: Τα ακατέργαστα δεδομένα χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Λαμβάνει ή ορίζει την τιμή του χρωματικού χώρου.

Τιμή: Η τιμή του χρωματικού χώρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Ανακτά ή ορίζει την έκδοση γραμματοσειράς.

Τιμή: Η έκδοση γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Λαμβάνει ή ορίζει τις γραμματοσειρές.

Τιμή: Οι γραμματοσειρές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Λαμβάνει ή ορίζει το στοιχείο g.

Τιμή: Το στοιχείο g.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Λαμβάνει ή ορίζει την οριζόντια τοποθέτηση.

Τιμή: Η οριζόντια τοποθέτηση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Λαμβάνει ή ορίζει τις γραμμές.

Τιμή: Οι γραμμές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Λαμβάνει ή ορίζει το στοιχείο r.

Τιμή: Το στοιχείο r.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Λαμβάνει ή ορίζει τον συντελεστή κλίμακας.

Τιμή: Ο συντελεστής κλίμακας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Λαμβάνει ή ορίζει το τέλος της επιλογής.

Τιμή: Το τέλος επιλογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Λαμβάνει ή ορίζει την αρχή επιλογής.

Τιμή: Η αρχή επιλογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Λαμβάνει ή ορίζει τα στυλ γραμματοσειράς.

Τιμή: Τα στυλ γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού.

Τιμή: Ο μετασχηματιστικός πίνακας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Λαμβάνει ή ορίζει την τιμή τύπου.

Τιμή: Η τιμή τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Λαμβάνει ή ορίζει την έκδοση.

Τιμή: Η έκδοση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Λαμβάνει ή ορίζει την κατακόρυφη τοποθέτηση.

Τιμή: Η κατακόρυφη τοποθέτηση.

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

