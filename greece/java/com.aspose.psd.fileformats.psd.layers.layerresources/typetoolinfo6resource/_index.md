---
title: "TypeToolInfo6Resource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Οι πληροφορίες του εργαλείου τύπου."
type: docs
weight: 78
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

Οι πληροφορίες του εργαλείου τύπου. Για έκδοση PSD ίση ή μεγαλύτερη από 6.0.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource). |
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
| [getBottom()](#getBottom--) | Λαμβάνει ή ορίζει τη θέση στο κάτω μέρος. |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | Λαμβάνει ή ορίζει τα όρια του κειμένου στο πλαίσιο κειμένου. |
| [getBounds_internalized()](#getBounds-internalized--) | Λαμβάνει ή ορίζει τα όρια του πλαισίου κειμένου. |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [getClassName()](#getClassName--) | Λαμβάνει ή ορίζει το όνομα της κλάσης. |
| [getDescriptorVersion()](#getDescriptorVersion--) | Λαμβάνει ή ορίζει την έκδοση του περιγραφέα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getItems()](#getItems--) | Λαμβάνει ή ορίζει τα στοιχεία. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLeft()](#getLeft--) | Λαμβάνει ή ορίζει τη θέση αριστερά. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | Αναλύει τα ακατέργαστα δεδομένα σε μια παρουσία της κλάσης TyShRoot. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | Αποκτά το [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) στοιχείο εάν υπάρχει. |
| [getRight()](#getRight--) | Αποκτά ή ορίζει τη δεξιά θέση. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | Αποκτά τον δείκτη του κειμένου σε αυτόν τον πόρο. |
| [getTextVersion()](#getTextVersion--) | Αποκτά ή ορίζει την έκδοση του κειμένου. |
| [getTop()](#getTop--) | Αποκτά ή ορίζει την κορυφαία θέση. |
| [getTransformMatrix()](#getTransformMatrix--) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| [getVersion()](#getVersion--) | Αποκτά ή ορίζει την έκδοση του εργαλείου τύπου. |
| [getWarpClassID()](#getWarpClassID--) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [getWarpClassName()](#getWarpClassName--) | Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης. |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης. |
| [getWarpItems()](#getWarpItems--) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [getWarpVersion()](#getWarpVersion--) | Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setBottom(int value)](#setBottom-int-) | Λαμβάνει ή ορίζει τη θέση στο κάτω μέρος. |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | Λαμβάνει ή ορίζει τα όρια του κειμένου στο πλαίσιο κειμένου. |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [setClassName(String value)](#setClassName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της κλάσης. |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | Λαμβάνει ή ορίζει την έκδοση του περιγραφέα. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει τα στοιχεία. |
| [setLeft(int value)](#setLeft-int-) | Λαμβάνει ή ορίζει τη θέση αριστερά. |
| [setRight(int value)](#setRight-int-) | Αποκτά ή ορίζει τη δεξιά θέση. |
| [setTextVersion(short value)](#setTextVersion-short-) | Αποκτά ή ορίζει την έκδοση του κειμένου. |
| [setTop(int value)](#setTop-int-) | Αποκτά ή ορίζει την κορυφαία θέση. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| [setVersion(short value)](#setVersion-short-) | Αποκτά ή ορίζει την έκδοση του εργαλείου τύπου. |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης. |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης. |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| [setWarpVersion(short value)](#setWarpVersion-short-) | Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | Σειριοποιεί τα δεδομένα TyShRoot σε ακατέργαστο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό της κλάσης. |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό κλάσης warp. |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Λαμβάνει ή ορίζει τη θέση στο κάτω μέρος.

Τιμή: Η κάτω θέση.

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


Λαμβάνει ή ορίζει τα όρια του κειμένου στο πλαίσιο κειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


Λαμβάνει ή ορίζει τα όρια του πλαισίου κειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


Λαμβάνει ή ορίζει το όνομα της κλάσης.

Τιμή: Το όνομα της κλάσης.

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


Λαμβάνει ή ορίζει την έκδοση του περιγραφέα.

Τιμή: Η έκδοση του descriptor.

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


Λαμβάνει ή ορίζει τα στοιχεία.

Τιμή: Τα στοιχεία.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


Λαμβάνει το κλειδί πόρου της στρώσης.

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Λαμβάνει ή ορίζει τη θέση αριστερά.

Τιμή: Η αριστερή θέση.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Λαμβάνει το μήκος του πόρου της στρώσης σε bytes.

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


Αναλύει τα ακατέργαστα δεδομένα σε μια παρουσία της κλάσης TyShRoot.

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - Τα ακατέργαστα δεδομένα ως αντικείμενο κλάσης TyShRoot.
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
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


Αποκτά το [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) στοιχείο εάν υπάρχει.

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


Αποκτά ή ορίζει τη δεξιά θέση.

Τιμή: Η δεξιά θέση.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


Αποκτά τον δείκτη του κειμένου σε αυτόν τον πόρο.

**Returns:**
int - Επιστρέφει τον δείκτη του κειμένου σε αυτόν τον πόρο.
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


Αποκτά ή ορίζει την έκδοση του κειμένου.

Τιμή: Η έκδοση του κειμένου.

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


Αποκτά ή ορίζει την κορυφαία θέση.

Τιμή: Η κορυφαία θέση.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού.

Τιμή: Ο μετασχηματιστικός πίνακας.

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Αποκτά ή ορίζει την έκδοση του εργαλείου τύπου.

Τιμή: Η έκδοση του εργαλείου τύπου.

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης.

Τιμή: Το όνομα κλάσης παραμόρφωσης.

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης.

Τιμή: Η έκδοση περιγραφέα παραμόρφωσης.

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης.

Τιμή: Η έκδοση παραμόρφωσης.

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

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Λαμβάνει ή ορίζει τη θέση στο κάτω μέρος.

Τιμή: Η κάτω θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


Λαμβάνει ή ορίζει τα όρια του κειμένου στο πλαίσιο κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


Λαμβάνει ή ορίζει το όνομα της κλάσης.

Τιμή: Το όνομα της κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση του περιγραφέα.

Τιμή: Η έκδοση του descriptor.

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


Λαμβάνει ή ορίζει τα στοιχεία.

Τιμή: Τα στοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Λαμβάνει ή ορίζει τη θέση αριστερά.

Τιμή: Η αριστερή θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Αποκτά ή ορίζει τη δεξιά θέση.

Τιμή: Η δεξιά θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


Αποκτά ή ορίζει την έκδοση του κειμένου.

Τιμή: Η έκδοση του κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Αποκτά ή ορίζει την κορυφαία θέση.

Τιμή: Η κορυφαία θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Αποκτά ή ορίζει την έκδοση του εργαλείου τύπου.

Τιμή: Η έκδοση του εργαλείου τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης.

Τιμή: Το αναγνωριστικό κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


Λαμβάνει ή ορίζει το όνομα κλάσης παραμόρφωσης.

Τιμή: Το όνομα κλάσης παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση περιγραφέα παραμόρφωσης.

Τιμή: Η έκδοση περιγραφέα παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης.

Τιμή: Τα στοιχεία παραμόρφωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


Λαμβάνει ή ορίζει την έκδοση παραμόρφωσης.

Τιμή: Η έκδοση παραμόρφωσης.

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
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


Σειριοποιεί τα δεδομένα TyShRoot σε ακατέργαστο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataModel | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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

