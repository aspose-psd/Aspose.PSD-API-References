---
title: "GlobalLayerMaskInfo"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η ενότητα παγκόσμιας μάσκας επιπέδου."
type: docs
weight: 15
url: /el/java/com.aspose.psd.fileformats.psd.layers/globallayermaskinfo/
---

**Inheritance:**
java.lang.Object
```
public final class GlobalLayerMaskInfo
```

Η ενότητα παγκόσμιας μάσκας επιπέδου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GlobalLayerMaskInfo()](#GlobalLayerMaskInfo--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaMask()](#getAlphaMask--) | Λαμβάνει ή ορίζει τη μάσκα άλφα. |
| [getBlueMask()](#getBlueMask--) | Λαμβάνει ή ορίζει τη μπλε μάσκα. |
| [getClass()](#getClass--) |  |
| [getGreenMask()](#getGreenMask--) | Λαμβάνει ή ορίζει τη πράσινη μάσκα. |
| [getKind()](#getKind--) | Λαμβάνει ή ορίζει τον τύπο. |
| [getLength()](#getLength--) | Λαμβάνει το μήκος της ενότητας παγκόσμιας μάσκας στρώσης σε byte. |
| [getOpacity()](#getOpacity--) | Λαμβάνει ή ορίζει τη διαφάνεια των παγκόσμιων στρώσεων. |
| [getOverlayColorSpace()](#getOverlayColorSpace--) | Λαμβάνει ή ορίζει το χρωματικό χώρο επικάλυψης (ατεκμηρίωτη τιμή). |
| [getRedMask()](#getRedMask--) | Λαμβάνει ή ορίζει τη κόκκινη μάσκα. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Αποθηκεύει τα δεδομένα στο καθορισμένο κοντέινερ ροής. |
| [setAlphaMask(short value)](#setAlphaMask-short-) | Λαμβάνει ή ορίζει τη μάσκα άλφα. |
| [setBlueMask(short value)](#setBlueMask-short-) | Λαμβάνει ή ορίζει τη μπλε μάσκα. |
| [setGreenMask(short value)](#setGreenMask-short-) | Λαμβάνει ή ορίζει τη πράσινη μάσκα. |
| [setKind(byte value)](#setKind-byte-) | Λαμβάνει ή ορίζει τον τύπο. |
| [setOpacity(short value)](#setOpacity-short-) | Λαμβάνει ή ορίζει τη διαφάνεια των παγκόσμιων στρώσεων. |
| [setOverlayColorSpace(short value)](#setOverlayColorSpace-short-) | Λαμβάνει ή ορίζει το χρωματικό χώρο επικάλυψης (ατεκμηρίωτη τιμή). |
| [setRedMask(short value)](#setRedMask-short-) | Λαμβάνει ή ορίζει τη κόκκινη μάσκα. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GlobalLayerMaskInfo() {#GlobalLayerMaskInfo--}
```
public GlobalLayerMaskInfo()
```


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
### getAlphaMask() {#getAlphaMask--}
```
public final short getAlphaMask()
```


Λαμβάνει ή ορίζει τη μάσκα άλφα.

Τιμή: Η μάσκα άλφα.

**Returns:**
short
### getBlueMask() {#getBlueMask--}
```
public final short getBlueMask()
```


Λαμβάνει ή ορίζει τη μπλε μάσκα.

Τιμή: Η μπλε μάσκα.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGreenMask() {#getGreenMask--}
```
public final short getGreenMask()
```


Λαμβάνει ή ορίζει τη πράσινη μάσκα.

Τιμή: Η πράσινη μάσκα.

**Returns:**
short
### getKind() {#getKind--}
```
public final byte getKind()
```


Λαμβάνει ή ορίζει τον τύπο. 0 = Επιλεγμένο χρώμα--δηλαδή αντιστροφή· 1 = Προστατευμένο χρώμα· 128 = χρήση τιμής αποθηκευμένης ανά στρώση. Αυτή η τιμή προτιμάται. Οι άλλες είναι για συμβατότητα με παλαιότερες εκδόσεις beta.

Τιμή: Ο τύπος.

**Returns:**
byte
### getLength() {#getLength--}
```
public final long getLength()
```


Λαμβάνει το μήκος της ενότητας παγκόσμιας μάσκας στρώσης σε byte.

**Returns:**
long
### getOpacity() {#getOpacity--}
```
public final short getOpacity()
```


Λαμβάνει ή ορίζει τη διαφάνεια των παγκόσμιων στρώσεων. 0 = διαυγής, 100 = αδιαφανής.

Τιμή: Η διαφάνεια των παγκόσμιων στρώσεων.

**Returns:**
short
### getOverlayColorSpace() {#getOverlayColorSpace--}
```
public final short getOverlayColorSpace()
```


Λαμβάνει ή ορίζει το χρωματικό χώρο επικάλυψης (ατεκμηρίωτη τιμή).

Τιμή: Ο χρωματικός χώρος επικάλυψης.

**Returns:**
short
### getRedMask() {#getRedMask--}
```
public final short getRedMask()
```


Λαμβάνει ή ορίζει τη κόκκινη μάσκα.

Τιμή: Η κόκκινη μάσκα.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Αποθηκεύει τα δεδομένα στο καθορισμένο κοντέινερ ροής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |

### setAlphaMask(short value) {#setAlphaMask-short-}
```
public final void setAlphaMask(short value)
```


Λαμβάνει ή ορίζει τη μάσκα άλφα.

Τιμή: Η μάσκα άλφα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setBlueMask(short value) {#setBlueMask-short-}
```
public final void setBlueMask(short value)
```


Λαμβάνει ή ορίζει τη μπλε μάσκα.

Τιμή: Η μπλε μάσκα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setGreenMask(short value) {#setGreenMask-short-}
```
public final void setGreenMask(short value)
```


Λαμβάνει ή ορίζει τη πράσινη μάσκα.

Τιμή: Η πράσινη μάσκα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setKind(byte value) {#setKind-byte-}
```
public final void setKind(byte value)
```


Λαμβάνει ή ορίζει τον τύπο. 0 = Επιλεγμένο χρώμα--δηλαδή αντιστροφή· 1 = Προστατευμένο χρώμα· 128 = χρήση τιμής αποθηκευμένης ανά στρώση. Αυτή η τιμή προτιμάται. Οι άλλες είναι για συμβατότητα με παλαιότερες εκδόσεις beta.

Τιμή: Ο τύπος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte |  |

### setOpacity(short value) {#setOpacity-short-}
```
public final void setOpacity(short value)
```


Λαμβάνει ή ορίζει τη διαφάνεια των παγκόσμιων στρώσεων. 0 = διαυγής, 100 = αδιαφανής.

Τιμή: Η διαφάνεια των παγκόσμιων στρώσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setOverlayColorSpace(short value) {#setOverlayColorSpace-short-}
```
public final void setOverlayColorSpace(short value)
```


Λαμβάνει ή ορίζει το χρωματικό χώρο επικάλυψης (ατεκμηρίωτη τιμή).

Τιμή: Ο χρωματικός χώρος επικάλυψης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### setRedMask(short value) {#setRedMask-short-}
```
public final void setRedMask(short value)
```


Λαμβάνει ή ορίζει τη κόκκινη μάσκα.

Τιμή: Η κόκκινη μάσκα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | short |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

