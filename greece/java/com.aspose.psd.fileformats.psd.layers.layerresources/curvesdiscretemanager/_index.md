---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Διαχειριστής για το στρώμα προσαρμογής καμπυλών που χειρίζεται το χάρτη εικονοστοιχείων"
type: docs
weight: 25
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Διαχειριστής για τη στρώση προσαρμογής καμπυλών που χειρίζεται το χάρτη των εικονοστοιχείων
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Λαμβάνει τα byte για τον πόρο. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Λαμβάνει τον χάρτη για το φίλτρο επεξεργασίας |
| [getMaxChannelCount()](#getMaxChannelCount--) | Λαμβάνει τον μέγιστο αριθμό καναλιών. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Λαμβάνει την τιμή στη θέση. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Φορτώνει δεδομένα από bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Ορίζει στην προεπιλεγμένη τιμή στη θέση. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Ορίζει την τιμή στη θέση. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Ορίζει την τιμή ολόκληρου του καναλιού. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxChannelCount | int | Ο μέγιστος αριθμός καναλιών. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Λαμβάνει τα byte για τον πόρο.

**Returns:**
byte[] - Bytes για τη σύνθεση του CurvResource
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Λαμβάνει τον χάρτη για το φίλτρο επεξεργασίας

**Returns:**
byte[][] - Χάρτης μετασχηματισμού
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Λαμβάνει τον μέγιστο αριθμό καναλιών.

Τιμή: Ο μέγιστος αριθμός καναλιών.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Λαμβάνει την τιμή στη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |

**Returns:**
byte - Τιμή της καμπύλης ανά θέση της
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Φορτώνει δεδομένα από bytes.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | byte[] | Τα bytes. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Ορίζει στην προεπιλεγμένη τιμή στη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Ορίζει την τιμή στη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| position | byte | Η θέση. |
| τιμή | byte | Η τιμή. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Ορίζει την τιμή ολόκληρου του καναλιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| channelValue | byte[] | Η τιμή του καναλιού. |

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

