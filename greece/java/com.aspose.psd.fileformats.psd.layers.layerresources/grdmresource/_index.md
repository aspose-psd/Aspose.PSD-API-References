---
title: "GrdmResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Κλάση GrdmResource."
type: docs
weight: 35
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

Κλάση GrdmResource. Περιέχει πληροφορίες σχετικά με το επίπεδο Gradient-Map.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | Η προεπιλεγμένη κλίμακα. |
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
| [getColorModel()](#getColorModel--) | Μοντέλο χρώματος. |
| [getColorPoints()](#getColorPoints--) | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getDither()](#getDither--) | Είναι το gradient ντιθέρ. |
| [getExpansionCount()](#getExpansionCount--) | Αριθμός επέκτασης ( = 2 για Photoshop 6.0). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Μήκος(= 32 για Photoshop 6.0) Δεν υπάρχει πληροφορία για το τι είναι υπεύθυνο. |
| [getGradientMode()](#getGradientMode--) | Λειτουργία για αυτό το gradient Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1). |
| [getGradientName()](#getGradientName--) | Όνομα του gradient: συμβολοσειρά Unicode, γεμισμένη. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getInterpolation()](#getInterpolation--) | Παρεμβολή. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getMaximumColor()](#getMaximumColor--) | Μέγιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. |
| [getMinimumColor()](#getMinimumColor--) | Ελάχιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση PSD που απαιτείται για αυτόν τον πόρο. |
| [getReverse()](#getReverse--) | Το gradient είναι αντιστροφή. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για τη διαβάθμιση Θορύβου. |
| [getRoughness()](#getRoughness--) | Συντελεστής τραχύτητας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Roughness' (0 - 2048). |
| [getShowTransparency()](#getShowTransparency--) | Σημαία για εμφάνιση διαφάνειας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Add transparency' σε true. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| [getUseVectorColor()](#getUseVectorColor--) | Σημαία για τη χρήση διανυσματικού χρώματος. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Αρχικοποιεί το μήκος του gradient. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τα δεδομένα του πόρου στο καθορισμένο container ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setColorModel(short value)](#setColorModel-short-) | Μοντέλο χρώματος. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| [setDither(boolean value)](#setDither-boolean-) | Είναι το gradient ντιθέρ. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Αριθμός επέκτασης ( = 2 για Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Λειτουργία για αυτό το gradient Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1). |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Όνομα του gradient: συμβολοσειρά Unicode, γεμισμένη. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setInterpolation(short value)](#setInterpolation-short-) | Παρεμβολή. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Μέγιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Ελάχιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. |
| [setReverse(boolean value)](#setReverse-boolean-) | Το gradient είναι αντιστροφή. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για τη διαβάθμιση Θορύβου. |
| [setRoughness(int value)](#setRoughness-int-) | Συντελεστής τραχύτητας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Roughness' (0 - 2048). |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Σημαία για εμφάνιση διαφάνειας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Add transparency' σε true. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Σημαία για τη χρήση διανυσματικού χρώματος. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| psdVersion | int | Η έκδοση psd του πόρου. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


Η προεπιλεγμένη κλίμακα.

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Μοντέλο χρώματος. Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Color Model' σε RGB/SHB/LAB (3/4/6).

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Λαμβάνει ή ορίζει τα σημεία χρώματος.

Τιμή: Τα σημεία χρώματος.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Λαμβάνει ή ορίζει τα δεδομένα.

Τιμή: Τα δεδομένα.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Είναι το gradient ντιθέρ.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Αριθμός επέκτασης ( = 2 για Photoshop 6.0).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Μήκος(= 32 για Photoshop 6.0) Δεν υπάρχει πληροφορία για το τι είναι υπεύθυνο.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Λειτουργία για αυτό το gradient Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Όνομα του gradient: συμβολοσειρά Unicode, γεμισμένη.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Λαμβάνει ή ορίζει την κεφαλίδα.

Τιμή: Η κεφαλίδα.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Παρεμβολή. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid' (GradientMode = 0).

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Μέγιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Ελάχιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


Λαμβάνει την ελάχιστη έκδοση PSD που απαιτείται για αυτόν τον πόρο. Η έκδοση 3 απαιτείται όταν η μέθοδος παρεμβολής αποθηκεύεται ρητά.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Το gradient είναι αντιστροφή.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για τη διαβάθμιση Θορύβου.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Συντελεστής τραχύτητας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Roughness' (0 - 2048).

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Σημαία για εμφάνιση διαφάνειας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Add transparency' σε true.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Λαμβάνει την υπογραφή του πόρου της στρώσης.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Λαμβάνει ή ορίζει τα σημεία διαφάνειας.

Τιμή: Τα σημεία διαφάνειας.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Σημαία για τη χρήση διανυσματικού χρώματος.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Αρχικοποιεί το μήκος του gradient. Το GradientLength είναι μόνο για ανάγνωση, έτσι μπορεί να οριστεί μόνο μία φορά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short | Η τιμή. |

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


Αποθηκεύει τα δεδομένα του πόρου στο καθορισμένο container ροής.

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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Μοντέλο χρώματος. Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Color Model' σε RGB/SHB/LAB (3/4/6).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Λαμβάνει ή ορίζει τα σημεία χρώματος.

Τιμή: Τα σημεία χρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Είναι το gradient ντιθέρ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Αριθμός επέκτασης ( = 2 για Photoshop 6.0).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Λειτουργία για αυτό το gradient Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Όνομα του gradient: συμβολοσειρά Unicode, γεμισμένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Παρεμβολή. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid' (GradientMode = 0).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Λαμβάνει ή ορίζει τη μέθοδο παρεμβολής για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Μέγιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Ελάχιστο χρώμα της μορφής PixelDataFormat.Rgba64Bpp. Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Το gradient είναι αντιστροφή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για τη διαβάθμιση Θορύβου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Συντελεστής τραχύτητας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Roughness' (0 - 2048).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Σημαία για εμφάνιση διαφάνειας Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε 'Add transparency' σε true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Λαμβάνει ή ορίζει τα σημεία διαφάνειας.

Τιμή: Τα σημεία διαφάνειας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Σημαία για τη χρήση διανυσματικού χρώματος.

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

