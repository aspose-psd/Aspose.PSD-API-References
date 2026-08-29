---
title: "ArtBResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Τα δεδομένα πληροφοριών του Artboard για το Layer.Resources/"
type: docs
weight: 11
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtBResource extends BaseArtboardInfoResource
```

Τα δεδομένα πληροφοριών του Artboard για το  Layer.Resources ([Layer.getResources](../../com.aspose.psd.fileformats.psd.layers/layer\#getResources)/[Layer.setResources(LayerResource[])](../../com.aspose.psd.fileformats.psd.layers/layer\#setResources-LayerResource---)).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ArtBResource()](#ArtBResource--) | Δημιουργεί μια νέα παρουσία της κλάσης [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource). |
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
| [getArtboardBackgroundType()](#getArtboardBackgroundType--) | Λαμβάνει ή ορίζει το  ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [getArtboardPresetName_internalized()](#getArtboardPresetName-internalized--) | Λαμβάνει ή ορίζει το  ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [getArtboardRect_internalized()](#getArtboardRect-internalized--) | Λαμβάνει ή ορίζει το  ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου. |
| [getClassName_internalized()](#getClassName-internalized--) | Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου. |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το  Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [getGuideIndeces_internalized()](#getGuideIndeces-internalized--) | Λαμβάνει ή ορίζει το  GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getItems()](#getItems--) | Λαμβάνει ή ορίζει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στοιχεία. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) |    |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getVersion_internalized()](#getVersion-internalized--) | Λαμβάνει ή ορίζει την έκδοση του πόρου. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setArtboardBackgroundType(int value)](#setArtboardBackgroundType-int-) | Λαμβάνει ή ορίζει το  ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-)) |
| [setArtboardPresetName_internalized(String value)](#setArtboardPresetName-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το  ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-)) |
| [setArtboardRect_internalized(RectangleF value)](#setArtboardRect-internalized-com.aspose.psd.RectangleF-) | Λαμβάνει ή ορίζει το  ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--)) |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Λαμβάνει ή ορίζει το  Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--)) |
| [setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)](#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--) | Λαμβάνει ή ορίζει το  GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--)) |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Λαμβάνει ή ορίζει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στοιχεία. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Λαμβάνει ή ορίζει την έκδοση του πόρου. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtBResource() {#ArtBResource--}
```
public ArtBResource()
```


Δημιουργεί μια νέα παρουσία της κλάσης [ArtBResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artbresource).

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
### getArtboardBackgroundType() {#getArtboardBackgroundType--}
```
public final int getArtboardBackgroundType()
```


Λαμβάνει ή ορίζει το  ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Returns:**
int
### getArtboardPresetName_internalized() {#getArtboardPresetName-internalized--}
```
public final String getArtboardPresetName_internalized()
```


Λαμβάνει ή ορίζει το  ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Returns:**
java.lang.String
### getArtboardRect_internalized() {#getArtboardRect-internalized--}
```
public final RectangleF getArtboardRect_internalized()
```


Λαμβάνει ή ορίζει το  ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου.

**Returns:**
java.lang.String
### getColor() {#getColor--}
```
public final Color getColor()
```


Λαμβάνει ή ορίζει το  Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Returns:**
[Color](../../com.aspose.psd/color)
### getGuideIndeces_internalized() {#getGuideIndeces-internalized--}
```
public final System.Collections.Generic.List<OSTypeStructure> getGuideIndeces_internalized()
```


Λαμβάνει ή ορίζει το  GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure>
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


Λαμβάνει ή ορίζει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στοιχεία.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
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
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Λαμβάνει ή ορίζει την έκδοση του πόρου.

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

### setArtboardBackgroundType(int value) {#setArtboardBackgroundType-int-}
```
public final void setArtboardBackgroundType(int value)
```


Λαμβάνει ή ορίζει το  ArtboardBackgroundType ([.getArtboardBackgroundType\_internalized](../../null/\#getArtboardBackgroundType-internalized)/[.setArtboardBackgroundType\_internalized(int)](../../null/\#setArtboardBackgroundType-internalized-int-))

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setArtboardPresetName_internalized(String value) {#setArtboardPresetName-internalized-java.lang.String-}
```
public final void setArtboardPresetName_internalized(String value)
```


Λαμβάνει ή ορίζει το  ArtboardPresetName ([.getArtboardPresetName\_internalized](../../null/\#getArtboardPresetName-internalized)/[.setArtboardPresetName\_internalized(String)](../../null/\#setArtboardPresetName-internalized-String-))

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setArtboardRect_internalized(RectangleF value) {#setArtboardRect-internalized-com.aspose.psd.RectangleF-}
```
public final void setArtboardRect_internalized(RectangleF value)
```


Λαμβάνει ή ορίζει το  ArtboardRect ([.getArtboardRect\_internalized](../../null/\#getArtboardRect-internalized)/[.setArtboardRect()](../../null/\#setArtboardRect--))

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Λαμβάνει ή ορίζει το όνομα της κλάσης πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Λαμβάνει ή ορίζει το  Color ([.getColor\_internalized](../../null/\#getColor-internalized)/[.setColor()](../../null/\#setColor--))

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value) {#setGuideIndeces-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure--}
```
public final void setGuideIndeces_internalized(System.Collections.Generic.List<OSTypeStructure> value)
```


Λαμβάνει ή ορίζει το  GuideIndeces ([.getGuideIndeces\_internalized](../../null/\#getGuideIndeces-internalized)/[.setGuideIndeces\_internalized(List)](../../null/\#setGuideIndeces-internalized-List-OSTypeStructure--))

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> |  |

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


Λαμβάνει ή ορίζει το [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) στοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Λαμβάνει ή ορίζει την έκδοση του πόρου.

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

