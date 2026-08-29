---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Διαχειριστής για τη στρώση προσαρμογής καμπυλών που χειρίζεται τις καμπύλες"
type: docs
weight: 24
url: /el/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

Διαχειριστής για τη στρώση προσαρμογής καμπυλών που χειρίζεται τις καμπύλες
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | Προσθέτει το σημείο της καμπύλης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Λαμβάνει τα byte για τον πόρο. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | Λαμβάνει το σημείο της καμπύλης κατά δείκτη. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | Λαμβάνει τον αριθμό σημείων της καμπύλης. |
| [getMap_internalized()](#getMap-internalized--) | Λαμβάνει τον χάρτη για το φίλτρο επεξεργασίας. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Λαμβάνει τον μέγιστο αριθμό καναλιών. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Φορτώνει δεδομένα από bytes. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | Αφαιρεί το σημείο της καμπύλης. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | Ενημερώνει το σημείο της καμπύλης. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxChannelCount | int | Ο μέγιστος αριθμός καναλιών. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


Προσθέτει το σημείο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| x | byte | Η θέση x. |
| y | byte | Η θέση y. |

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
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


Λαμβάνει το σημείο της καμπύλης κατά δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| pointIndex | int | Δείκτης του σημείου. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


Λαμβάνει τον αριθμό σημείων της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |

**Returns:**
int - Αριθμός σημείων καμπύλης στο κανάλι
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Λαμβάνει τον χάρτη για το φίλτρο επεξεργασίας.

**Returns:**
byte[][] - Χάρτης για την επεξεργασία του καναλιού.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Λαμβάνει τον μέγιστο αριθμό καναλιών.

Τιμή: Ο μέγιστος αριθμός καναλιών.

**Returns:**
int
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




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


Αφαιρεί το σημείο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| pointIndex | int | Δείκτης του σημείου. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


Ενημερώνει το σημείο της καμπύλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| channelIndex | int | Δείκτης του καναλιού. |
| pointIndex | int | Δείκτης του σημείου. |
| x | byte | Η θέση x. |
| y | byte | Η θέση y. |

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

