---
title: "VstkResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση πόρου VstkResource."
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

Κλάση πόρου VstkResource. Περιέχει πληροφορίες σχετικά με τα δεδομένα Vector Stroke. Ο πόρος πρέπει να αρχικοποιείται είτε μέσω της μεθόδου AssignItems από το resourcedata, είτε μέσω της ανάθεσης τιμών στις ιδιότητες της κλάσης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VstkResource()](#VstkResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource). |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Αναθέτει τις δομές items από τον πόρο Vstk. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Λαμβάνει ή ορίζει την παρουσία ClassID. |
| [getClassName_internalized()](#getClassName-internalized--) | Λαμβάνει ή ορίζει το όνομα της κλάσης. |
| [getFillEnabled()](#getFillEnabled--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το Stroke fill είναι ενεργό. |
| [getFillSettings()](#getFillSettings--) | Λαμβάνει ή ορίζει τις ρυθμίσεις Fill του Stroke. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getStrokeEnabled()](#getStrokeEnabled--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το εφέ stroke είναι ενεργό |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης Stroke. |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | Λαμβάνει ή ορίζει την οντότητα Stroke. |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Λαμβάνει ή ορίζει την ευθυγράμμιση γραμμής του στυλ Stroke. |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | Λαμβάνει ή ορίζει τον τύπο του άκρου γραμμής του στυλ Stroke. |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | Λαμβάνει ή ορίζει το πλάτος άκρου γραμμής Stroke. |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | Λαμβάνει ή ορίζει την απόσταση παύλας γραμμής του στυλ Stroke. |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | Λαμβάνει ή ορίζει τον πίνακα των παύλων γραμμής. |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | Λαμβάνει ή ορίζει τον τύπο σύνδεσης γραμμής του στυλ Stroke. |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke. |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | Λαμβάνει ή ορίζει το όριο μύτης του στυλ Stroke. |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια του στυλ Stroke (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | Λαμβάνει ή ορίζει την ανάλυση του στυλ Stroke. |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Λαμβάνει ή ορίζει το κλείδωμα κλίμακας του στυλ Stroke. |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Λαμβάνει ή ορίζει τη ρύθμιση Stroke. |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | Λαμβάνει ή ορίζει την έκδοση του στυλ Stroke. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Λαμβάνει ή ορίζει την παρουσία ClassID. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της κλάσης. |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το Stroke fill είναι ενεργό. |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Λαμβάνει ή ορίζει τις ρυθμίσεις Fill του Stroke. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το εφέ stroke είναι ενεργό |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης Stroke. |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Λαμβάνει ή ορίζει την οντότητα Stroke. |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Λαμβάνει ή ορίζει την ευθυγράμμιση γραμμής του στυλ Stroke. |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | Λαμβάνει ή ορίζει τον τύπο του άκρου γραμμής του στυλ Stroke. |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | Λαμβάνει ή ορίζει το πλάτος άκρου γραμμής Stroke. |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | Λαμβάνει ή ορίζει την απόσταση παύλας γραμμής του στυλ Stroke. |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | Λαμβάνει ή ορίζει τον πίνακα των παύλων γραμμής. |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | Λαμβάνει ή ορίζει τον τύπο σύνδεσης γραμμής του στυλ Stroke. |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke. |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | Λαμβάνει ή ορίζει το όριο μύτης του στυλ Stroke. |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Λαμβάνει ή ορίζει τη διαφάνεια του στυλ Stroke (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | Λαμβάνει ή ορίζει την ανάλυση του στυλ Stroke. |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Λαμβάνει ή ορίζει το κλείδωμα κλίμακας του στυλ Stroke. |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Λαμβάνει ή ορίζει τη ρύθμιση Stroke. |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | Λαμβάνει ή ορίζει την έκδοση του στυλ Stroke. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource).

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Αναθέτει τις δομές items από τον πόρο Vstk.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Λίστα των αντικειμένων OSTypeStructure. |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Λαμβάνει ή ορίζει την παρουσία ClassID.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Λαμβάνει ή ορίζει το όνομα της κλάσης.

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το Stroke fill είναι ενεργό.

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Λαμβάνει ή ορίζει τις ρυθμίσεις Fill του Stroke.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το εφέ stroke είναι ενεργό

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης Stroke.

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Λαμβάνει ή ορίζει την οντότητα Stroke. Η ιδιότητα καθορίζει τις ρυθμίσεις γεμίσματος του stroke.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Λαμβάνει ή ορίζει την ευθυγράμμιση γραμμής του στυλ Stroke.

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


Λαμβάνει ή ορίζει τον τύπο του άκρου γραμμής του στυλ Stroke.

Τιμή: Ο τύπος του άκρου γραμμής του στυλ stroke.

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


Λαμβάνει ή ορίζει το πλάτος άκρου γραμμής Stroke.

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


Λαμβάνει ή ορίζει την απόσταση παύλας γραμμής του στυλ Stroke.

Τιμή: Η απόσταση παύλας γραμμής του στυλ Stroke.

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


Λαμβάνει ή ορίζει τον πίνακα των παύλων γραμμής.

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


Λαμβάνει ή ορίζει τον τύπο σύνδεσης γραμμής του στυλ Stroke.

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke.

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


Λαμβάνει ή ορίζει το όριο μύτης του στυλ Stroke.

Τιμή: Το όριο μύτης του στυλ stroke.

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια του στυλ Stroke (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


Λαμβάνει ή ορίζει την ανάλυση του στυλ Stroke.

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Λαμβάνει ή ορίζει το κλείδωμα κλίμακας του στυλ Stroke.

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Λαμβάνει ή ορίζει τη ρύθμιση Stroke.

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


Λαμβάνει ή ορίζει την έκδοση του στυλ Stroke.

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Λαμβάνει ή ορίζει την παρουσία ClassID.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Λαμβάνει ή ορίζει το όνομα της κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το Stroke fill είναι ενεργό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Λαμβάνει ή ορίζει τις ρυθμίσεις Fill του Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το εφέ stroke είναι ενεργό

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Λαμβάνει ή ορίζει την οντότητα Stroke. Η ιδιότητα καθορίζει τις ρυθμίσεις γεμίσματος του stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Λαμβάνει ή ορίζει την ευθυγράμμιση γραμμής του στυλ Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


Λαμβάνει ή ορίζει τον τύπο του άκρου γραμμής του στυλ Stroke.

Τιμή: Ο τύπος του άκρου γραμμής του στυλ stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


Λαμβάνει ή ορίζει το πλάτος άκρου γραμμής Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


Λαμβάνει ή ορίζει την απόσταση παύλας γραμμής του στυλ Stroke.

Τιμή: Η απόσταση παύλας γραμμής του στυλ Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


Λαμβάνει ή ορίζει τον πίνακα των παύλων γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


Λαμβάνει ή ορίζει τον τύπο σύνδεσης γραμμής του στυλ Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


Λαμβάνει ή ορίζει το όριο μύτης του στυλ Stroke.

Τιμή: Το όριο μύτης του στυλ stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Λαμβάνει ή ορίζει τη διαφάνεια του στυλ Stroke (0-100%).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


Λαμβάνει ή ορίζει την ανάλυση του στυλ Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Λαμβάνει ή ορίζει το κλείδωμα κλίμακας του στυλ Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Λαμβάνει ή ορίζει τη ρύθμιση Stroke.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


Λαμβάνει ή ορίζει την έκδοση του στυλ Stroke.

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

