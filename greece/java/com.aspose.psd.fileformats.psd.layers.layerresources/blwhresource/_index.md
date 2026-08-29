---
title: "BlwhResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η κλάση BlwhResource είναι πόρος της στρώσης προσαρμογής ασπρόμαυρου."
type: docs
weight: 15
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

Η κλάση BlwhResource είναι πόρος της στρώσης προσαρμογής ασπρόμαυρου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource). |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Λαμβάνει ή ορίζει το όνομα αρχείου προεπιλογής ασπρόμαυρου. |
| [getBlues()](#getBlues--) | Λαμβάνει ή ορίζει την τιμή των μπλε. |
| [getBwPresetKind()](#getBwPresetKind--) | Λαμβάνει ή ορίζει την τιμή του τύπου προεπιλογής ασπρόμαυρου. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Λαμβάνει ή ορίζει την τιμή των κυανών. |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getGreens()](#getGreens--) | Λαμβάνει ή ορίζει την τιμή των πράσινων. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getMagentas()](#getMagentas--) | Λαμβάνει ή ορίζει την τιμή των ματζέντα. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getReds()](#getReds--) | Λαμβάνει ή ορίζει την τιμή των κόκκινων. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getTintColor()](#getTintColor--) | Λαμβάνει το χρώμα απόχρωσης ARGB. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Λαμβάνει ή ορίζει την διπλή τιμή του Blue Tint Color. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Λαμβάνει ή ορίζει την διπλή τιμή του Green Tint Color. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Λαμβάνει ή ορίζει την διπλή τιμή του Red Tint Color. |
| [getUseTint()](#getUseTint--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [tint color] χρησιμοποιείται. |
| [getYellows()](#getYellows--) | Λαμβάνει ή ορίζει την τιμή των κίτρινων. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα αρχείου προεπιλογής ασπρόμαυρου. |
| [setBlues(int value)](#setBlues-int-) | Λαμβάνει ή ορίζει την τιμή των μπλε. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Λαμβάνει ή ορίζει την τιμή του τύπου προεπιλογής ασπρόμαυρου. |
| [setCyans(int value)](#setCyans-int-) | Λαμβάνει ή ορίζει την τιμή των κυανών. |
| [setGreens(int value)](#setGreens-int-) | Λαμβάνει ή ορίζει την τιμή των πράσινων. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setMagentas(int value)](#setMagentas-int-) | Λαμβάνει ή ορίζει την τιμή των ματζέντα. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Ορίζει την τιμή της ιδιότητας με δομή τύπου. |
| [setReds(int value)](#setReds-int-) | Λαμβάνει ή ορίζει την τιμή των κόκκινων. |
| [setTintColor(int value)](#setTintColor-int-) | Ορίζει το χρώμα απόχρωσης. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Λαμβάνει ή ορίζει την διπλή τιμή του Blue Tint Color. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Λαμβάνει ή ορίζει την διπλή τιμή του Green Tint Color. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Λαμβάνει ή ορίζει την διπλή τιμή του Red Tint Color. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [tint color] χρησιμοποιείται. |
| [setYellows(int value)](#setYellows-int-) | Λαμβάνει ή ορίζει την τιμή των κίτρινων. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource).

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Λαμβάνει ή ορίζει το όνομα αρχείου προεπιλογής ασπρόμαυρου.

Τιμή: Το όνομα αρχείου προεπιλογής ασπρόμαυρου.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Λαμβάνει ή ορίζει την τιμή των μπλε.

Τιμή: Η τιμή των μπλε.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Λαμβάνει ή ορίζει την τιμή του τύπου προεπιλογής ασπρόμαυρου.

Τιμή: Η τιμή του τύπου προεπιλογής ασπρόμαυρου.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Λαμβάνει ή ορίζει την τιμή των κυανών.

Τιμή: Η τιμή των κυανών.

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
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Λαμβάνει ή ορίζει την τιμή των πράσινων.

Τιμή: Η τιμή των πράσινων.

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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Λαμβάνει ή ορίζει την τιμή των ματζέντα.

Τιμή: Η τιμή των ματζέντα.

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
### getReds() {#getReds--}
```
public final int getReds()
```


Λαμβάνει ή ορίζει την τιμή των κόκκινων.

Τιμή: Η τιμή των κόκκινων.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


Λαμβάνει το χρώμα απόχρωσης ARGB.

**Returns:**
int - Το χρώμα απόχρωσης ARGB.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Λαμβάνει ή ορίζει την διπλή τιμή του Blue Tint Color.

Τιμή: Η διπλή τιμή του Blue Tint Color.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Λαμβάνει ή ορίζει την διπλή τιμή του Green Tint Color.

Τιμή: Η Green Tint Color διπλή τιμή.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Λαμβάνει ή ορίζει την διπλή τιμή του Red Tint Color.

Τιμή: Η Red Tint Color διπλή τιμή.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [tint color] χρησιμοποιείται.

Τιμή:  true  εάν χρησιμοποιείται [tint color]; διαφορετικά,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Λαμβάνει ή ορίζει την τιμή των κίτρινων.

Τιμή: Η yellows τιμή.

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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Λαμβάνει ή ορίζει το όνομα αρχείου προεπιλογής ασπρόμαυρου.

Τιμή: Το όνομα αρχείου προεπιλογής ασπρόμαυρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Λαμβάνει ή ορίζει την τιμή των μπλε.

Τιμή: Η τιμή των μπλε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Λαμβάνει ή ορίζει την τιμή του τύπου προεπιλογής ασπρόμαυρου.

Τιμή: Η τιμή του τύπου προεπιλογής ασπρόμαυρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Λαμβάνει ή ορίζει την τιμή των κυανών.

Τιμή: Η τιμή των κυανών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Λαμβάνει ή ορίζει την τιμή των πράσινων.

Τιμή: Η τιμή των πράσινων.

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Λαμβάνει ή ορίζει την τιμή των ματζέντα.

Τιμή: Η τιμή των ματζέντα.

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

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Λαμβάνει ή ορίζει την τιμή των κόκκινων.

Τιμή: Η τιμή των κόκκινων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Ορίζει το χρώμα απόχρωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η τιμή. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Λαμβάνει ή ορίζει την διπλή τιμή του Blue Tint Color.

Τιμή: Η διπλή τιμή του Blue Tint Color.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Λαμβάνει ή ορίζει την διπλή τιμή του Green Tint Color.

Τιμή: Η Green Tint Color διπλή τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Λαμβάνει ή ορίζει την διπλή τιμή του Red Tint Color.

Τιμή: Η Red Tint Color διπλή τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [tint color] χρησιμοποιείται.

Τιμή:  true  εάν χρησιμοποιείται [tint color]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Λαμβάνει ή ορίζει την τιμή των κίτρινων.

Τιμή: Η yellows τιμή.

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

