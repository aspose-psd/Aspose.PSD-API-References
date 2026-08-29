---
title: "BlncResource"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η κλάση BlncResource είναι πόρος της στρώσης προσαρμογής χρώματος."
type: docs
weight: 14
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlncResource extends AdjustmentLayerResource
```

Η κλάση BlncResource είναι πόρος της στρώσης προσαρμογής χρώματος.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BlncResource()](#BlncResource--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DataLength_internalized](#DataLength-internalized) | Το αναμενόμενο μήκος δεδομένων. |
| [HighlightsCyanRedBalanceExceptionMessage_internalized](#HighlightsCyanRedBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των φωτεινών σημείων εκτός εύρους. |
| [HighlightsMagentaGreenBalanceExceptionMessage_internalized](#HighlightsMagentaGreenBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των φωτεινών σημείων εκτός εύρους |
| [HighlightsYellowBlueBalanceExceptionMessage_internalized](#HighlightsYellowBlueBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των φωτεινών σημείων εκτός εύρους. |
| [MidtonesCyanRedBalanceExceptionMessage_internalized](#MidtonesCyanRedBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των μεσαίων τόνων εκτός εύρους. |
| [MidtonesMagentaGreenBalanceExceptionMessage_internalized](#MidtonesMagentaGreenBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των μεσαίων τόνων εκτός εύρους. |
| [MidtonesYellowBlueBalanceExceptionMessage_internalized](#MidtonesYellowBlueBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των μεσαίων τόνων εκτός εύρους. |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Η υπογραφή πόρου ειδική για PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Η έκδοση κεφαλίδας PSD |
| [ResourceSignature](#ResourceSignature) | Η κοινή υπογραφή πόρου. |
| [ShadowsCyanRedBalanceExceptionMessage_internalized](#ShadowsCyanRedBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των σκιών εκτός εύρους. |
| [ShadowsMagentaGreenBalanceExceptionMessage_internalized](#ShadowsMagentaGreenBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των σκιών εκτός εύρους. |
| [ShadowsYellowBlueBalanceExceptionMessage_internalized](#ShadowsYellowBlueBalanceExceptionMessage-internalized) | Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των σκιών εκτός εύρους. |
| [TypeToolKey](#TypeToolKey) | Το κλειδί πληροφοριών εργαλείου τύπου. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Η άδεια venture. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Ελέγχει και ορίζει αν ο πόρος είναι ειδικός για PSB. |
| [create_internalized(byte[] data)](#create-internalized-byte---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Λαμβάνει ή ορίζει τα δεδομένα. |
| [getHeader_internalized()](#getHeader-internalized--) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [getHighlightsCyanRedBalance()](#getHighlightsCyanRedBalance--) | Λαμβάνει ή ορίζει το Highlights Cyan Red Balance. |
| [getHighlightsMagentaGreenBalance()](#getHighlightsMagentaGreenBalance--) | Λαμβάνει ή ορίζει το Highlights Magenta Green Balance. |
| [getHighlightsYellowBlueBalance()](#getHighlightsYellowBlueBalance--) | Λαμβάνει ή ορίζει το Highlights Yellow Blue Balance. |
| [getKey()](#getKey--) | Λαμβάνει το κλειδί πόρου της στρώσης. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος του πόρου της στρώσης σε bytes. |
| [getMidtonesCyanRedBalance()](#getMidtonesCyanRedBalance--) | Λαμβάνει ή ορίζει το Midtones Cyan Red Balance. |
| [getMidtonesMagentaGreenBalance()](#getMidtonesMagentaGreenBalance--) | Λαμβάνει ή ορίζει το Midtones Magenta Green Balance. |
| [getMidtonesYellowBlueBalance()](#getMidtonesYellowBlueBalance--) | Λαμβάνει ή ορίζει το Midtones Yellow Blue Balance. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Λαμβάνει το μήκος του προθέματος. |
| [getPreserveLuminosity()](#getPreserveLuminosity--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) διατηρεί τη φωτεινότητα. |
| [getPsdVersion()](#getPsdVersion--) | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο της στρώσης. |
| [getShadowsCyanRedBalance()](#getShadowsCyanRedBalance--) | Λαμβάνει ή ορίζει το Shadows Cyan Red Balance. |
| [getShadowsMagentaGreenBalance()](#getShadowsMagentaGreenBalance--) | Λαμβάνει ή ορίζει το Shadows Magenta Green Balance. |
| [getShadowsYellowBlueBalance()](#getShadowsYellowBlueBalance--) | Αποκτά ή ορίζει την Ισορροπία Σκιών Κίτρινο Μπλε. |
| [getSignature()](#getSignature--) | Λαμβάνει την υπογραφή του πόρου της στρώσης. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Καθορίζει εάν ο πόρος είναι ειδικός για PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι πόρος ειδικός για PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Αποθηκεύει την προσαρμοσμένη κεφαλίδα πόρου. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Αποθηκεύει την υπογραφή της κεφαλίδας, το αναγνωριστικό και το μήκος. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Λαμβάνει ή ορίζει την κεφαλίδα. |
| [setHighlightsCyanRedBalance(short value)](#setHighlightsCyanRedBalance-short-) | Λαμβάνει ή ορίζει το Highlights Cyan Red Balance. |
| [setHighlightsMagentaGreenBalance(short value)](#setHighlightsMagentaGreenBalance-short-) | Λαμβάνει ή ορίζει το Highlights Magenta Green Balance. |
| [setHighlightsYellowBlueBalance(short value)](#setHighlightsYellowBlueBalance-short-) | Λαμβάνει ή ορίζει το Highlights Yellow Blue Balance. |
| [setMidtonesCyanRedBalance(short value)](#setMidtonesCyanRedBalance-short-) | Λαμβάνει ή ορίζει το Midtones Cyan Red Balance. |
| [setMidtonesMagentaGreenBalance(short value)](#setMidtonesMagentaGreenBalance-short-) | Λαμβάνει ή ορίζει το Midtones Magenta Green Balance. |
| [setMidtonesYellowBlueBalance(short value)](#setMidtonesYellowBlueBalance-short-) | Λαμβάνει ή ορίζει το Midtones Yellow Blue Balance. |
| [setPreserveLuminosity(boolean value)](#setPreserveLuminosity-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) διατηρεί τη φωτεινότητα. |
| [setShadowsCyanRedBalance(short value)](#setShadowsCyanRedBalance-short-) | Λαμβάνει ή ορίζει το Shadows Cyan Red Balance. |
| [setShadowsMagentaGreenBalance(short value)](#setShadowsMagentaGreenBalance-short-) | Λαμβάνει ή ορίζει το Shadows Magenta Green Balance. |
| [setShadowsYellowBlueBalance(short value)](#setShadowsYellowBlueBalance-short-) | Αποκτά ή ορίζει την Ισορροπία Σκιών Κίτρινο Μπλε. |
| [toString()](#toString--) | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlncResource() {#BlncResource--}
```
public BlncResource()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource).

### DataLength_internalized {#DataLength-internalized}
```
public static final int DataLength_internalized
```


Το αναμενόμενο μήκος δεδομένων.

### HighlightsCyanRedBalanceExceptionMessage_internalized {#HighlightsCyanRedBalanceExceptionMessage-internalized}
```
public static final String HighlightsCyanRedBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των φωτεινών σημείων εκτός εύρους.

### HighlightsMagentaGreenBalanceExceptionMessage_internalized {#HighlightsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String HighlightsMagentaGreenBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των φωτεινών σημείων εκτός εύρους

### HighlightsYellowBlueBalanceExceptionMessage_internalized {#HighlightsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String HighlightsYellowBlueBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των φωτεινών σημείων εκτός εύρους.

### MidtonesCyanRedBalanceExceptionMessage_internalized {#MidtonesCyanRedBalanceExceptionMessage-internalized}
```
public static final String MidtonesCyanRedBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των μεσαίων τόνων εκτός εύρους.

### MidtonesMagentaGreenBalanceExceptionMessage_internalized {#MidtonesMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String MidtonesMagentaGreenBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των μεσαίων τόνων εκτός εύρους.

### MidtonesYellowBlueBalanceExceptionMessage_internalized {#MidtonesYellowBlueBalanceExceptionMessage-internalized}
```
public static final String MidtonesYellowBlueBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των μεσαίων τόνων εκτός εύρους.

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

### ShadowsCyanRedBalanceExceptionMessage_internalized {#ShadowsCyanRedBalanceExceptionMessage-internalized}
```
public static final String ShadowsCyanRedBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κυανό-κόκκινου των σκιών εκτός εύρους.

### ShadowsMagentaGreenBalanceExceptionMessage_internalized {#ShadowsMagentaGreenBalanceExceptionMessage-internalized}
```
public static final String ShadowsMagentaGreenBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία ματζέντα-πράσινου των σκιών εκτός εύρους.

### ShadowsYellowBlueBalanceExceptionMessage_internalized {#ShadowsYellowBlueBalanceExceptionMessage-internalized}
```
public static final String ShadowsYellowBlueBalanceExceptionMessage_internalized
```


Το μήνυμα εξαίρεσης: η ισορροπία κίτρινο-μπλε των σκιών εκτός εύρους.

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

### create_internalized(byte[] data) {#create-internalized-byte---}
```
public static BlncResource create_internalized(byte[] data)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] |  |

**Returns:**
[BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource)
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
### getHighlightsCyanRedBalance() {#getHighlightsCyanRedBalance--}
```
public final short getHighlightsCyanRedBalance()
```


Λαμβάνει ή ορίζει το Highlights Cyan Red Balance.

Τιμή: Η Ισορροπία Φωτεινών Κυανό-Κόκκινου.

**Returns:**
short
### getHighlightsMagentaGreenBalance() {#getHighlightsMagentaGreenBalance--}
```
public final short getHighlightsMagentaGreenBalance()
```


Λαμβάνει ή ορίζει το Highlights Magenta Green Balance.

Τιμή: Η Ισορροπία Φωτεινών Ματζέντα-Πράσινου.

**Returns:**
short
### getHighlightsYellowBlueBalance() {#getHighlightsYellowBlueBalance--}
```
public final short getHighlightsYellowBlueBalance()
```


Λαμβάνει ή ορίζει το Highlights Yellow Blue Balance.

Τιμή: Η Ισορροπία Φωτεινών Κίτρινο-Μπλε.

**Returns:**
short
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
### getMidtonesCyanRedBalance() {#getMidtonesCyanRedBalance--}
```
public final short getMidtonesCyanRedBalance()
```


Λαμβάνει ή ορίζει το Midtones Cyan Red Balance.

Τιμή: Η Ισορροπία Μεσαίων Κυανό-Κόκκινου.

**Returns:**
short
### getMidtonesMagentaGreenBalance() {#getMidtonesMagentaGreenBalance--}
```
public final short getMidtonesMagentaGreenBalance()
```


Λαμβάνει ή ορίζει το Midtones Magenta Green Balance.

Τιμή: Η Ισορροπία Μεσαίων Ματζέντα-Πράσινου.

**Returns:**
short
### getMidtonesYellowBlueBalance() {#getMidtonesYellowBlueBalance--}
```
public final short getMidtonesYellowBlueBalance()
```


Λαμβάνει ή ορίζει το Midtones Yellow Blue Balance.

Τιμή: Η Ισορροπία Μεσαίων Κίτρινο-Μπλε.

**Returns:**
short
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


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) διατηρεί τη φωτεινότητα.

Τιμή:  true  εάν διατηρεί τη φωτεινότητα· διαφορετικά,  false .

**Returns:**
boolean
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για πόρο στρώσης. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί.

**Returns:**
int
### getShadowsCyanRedBalance() {#getShadowsCyanRedBalance--}
```
public final short getShadowsCyanRedBalance()
```


Λαμβάνει ή ορίζει το Shadows Cyan Red Balance.

Τιμή: Η Ισορροπία Σκιών Κυανό-Κόκκινου.

**Returns:**
short
### getShadowsMagentaGreenBalance() {#getShadowsMagentaGreenBalance--}
```
public final short getShadowsMagentaGreenBalance()
```


Λαμβάνει ή ορίζει το Shadows Magenta Green Balance.

Τιμή: Η Ισορροπία Σκιών Ματζέντα-Πράσινου.

**Returns:**
short
### getShadowsYellowBlueBalance() {#getShadowsYellowBlueBalance--}
```
public final short getShadowsYellowBlueBalance()
```


Αποκτά ή ορίζει την Ισορροπία Σκιών Κίτρινο Μπλε.

Τιμή: Η Ισορροπία Σκιών Κίτρινο-Μπλε.

**Returns:**
short
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

### setHighlightsCyanRedBalance(short value) {#setHighlightsCyanRedBalance-short-}
```
public final void setHighlightsCyanRedBalance(short value)
```


Λαμβάνει ή ορίζει το Highlights Cyan Red Balance.

Τιμή: Η Ισορροπία Φωτεινών Κυανό-Κόκκινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setHighlightsMagentaGreenBalance(short value) {#setHighlightsMagentaGreenBalance-short-}
```
public final void setHighlightsMagentaGreenBalance(short value)
```


Λαμβάνει ή ορίζει το Highlights Magenta Green Balance.

Τιμή: Η Ισορροπία Φωτεινών Ματζέντα-Πράσινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setHighlightsYellowBlueBalance(short value) {#setHighlightsYellowBlueBalance-short-}
```
public final void setHighlightsYellowBlueBalance(short value)
```


Λαμβάνει ή ορίζει το Highlights Yellow Blue Balance.

Τιμή: Η Ισορροπία Φωτεινών Κίτρινο-Μπλε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setMidtonesCyanRedBalance(short value) {#setMidtonesCyanRedBalance-short-}
```
public final void setMidtonesCyanRedBalance(short value)
```


Λαμβάνει ή ορίζει το Midtones Cyan Red Balance.

Τιμή: Η Ισορροπία Μεσαίων Κυανό-Κόκκινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setMidtonesMagentaGreenBalance(short value) {#setMidtonesMagentaGreenBalance-short-}
```
public final void setMidtonesMagentaGreenBalance(short value)
```


Λαμβάνει ή ορίζει το Midtones Magenta Green Balance.

Τιμή: Η Ισορροπία Μεσαίων Ματζέντα-Πράσινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setMidtonesYellowBlueBalance(short value) {#setMidtonesYellowBlueBalance-short-}
```
public final void setMidtonesYellowBlueBalance(short value)
```


Λαμβάνει ή ορίζει το Midtones Yellow Blue Balance.

Τιμή: Η Ισορροπία Μεσαίων Κίτρινο-Μπλε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setPreserveLuminosity(boolean value) {#setPreserveLuminosity-boolean-}
```
public final void setPreserveLuminosity(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BlncResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blncresource) διατηρεί τη φωτεινότητα.

Τιμή:  true  εάν διατηρεί τη φωτεινότητα· διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setShadowsCyanRedBalance(short value) {#setShadowsCyanRedBalance-short-}
```
public final void setShadowsCyanRedBalance(short value)
```


Λαμβάνει ή ορίζει το Shadows Cyan Red Balance.

Τιμή: Η Ισορροπία Σκιών Κυανό-Κόκκινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setShadowsMagentaGreenBalance(short value) {#setShadowsMagentaGreenBalance-short-}
```
public final void setShadowsMagentaGreenBalance(short value)
```


Λαμβάνει ή ορίζει το Shadows Magenta Green Balance.

Τιμή: Η Ισορροπία Σκιών Ματζέντα-Πράσινου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setShadowsYellowBlueBalance(short value) {#setShadowsYellowBlueBalance-short-}
```
public final void setShadowsYellowBlueBalance(short value)
```


Αποκτά ή ορίζει την Ισορροπία Σκιών Κίτρινο Μπλε.

Τιμή: Η Ισορροπία Σκιών Κίτρινο-Μπλε.

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

