---
title: "CurvesContinuousManager"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "कर्व्स एडजस्टमेंट लेयर के लिए मैनेजर जो कर्व्स को मैनीपुलेट करता है"
type: docs
weight: 24
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

कर्व्स एडजस्टमेंट लेयर के लिए मैनेजर जो कर्व्स को मैनीपुलेट करता है
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | नया उदाहरण प्रारंभ करता है [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | वक्र का बिंदु जोड़ता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | रिसोर्स के लिए बाइट्स प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | इंडेक्स द्वारा वक्र बिंदु प्राप्त करता है। |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | वक्र बिंदु की गिनती प्राप्त करता है। |
| [getMap_internalized()](#getMap-internalized--) | प्रोसेसिंग फ़िल्टर के लिए मानचित्र प्राप्त करता है। |
| [getMaxChannelCount()](#getMaxChannelCount--) | अधिकतम चैनल गिनती प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | बाइट्स से डेटा लोड करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | वक्र का बिंदु हटाता है। |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | वक्र का बिंदु अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


नया उदाहरण प्रारंभ करता है [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxChannelCount | int | अधिकतम चैनल गिनती। |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


वक्र का बिंदु जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| x | byte | x स्थान। |
| y | byte | y स्थान। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


रिसोर्स के लिए बाइट्स प्राप्त करता है।

**Returns:**
byte[] - CurvResource बनाने के लिए बाइट्स
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


इंडेक्स द्वारा वक्र बिंदु प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| pointIndex | int | बिंदु का सूचकांक। |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


वक्र बिंदु की गिनती प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |

**Returns:**
int - चैनल में वक्र बिंदु की गिनती
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


प्रोसेसिंग फ़िल्टर के लिए मानचित्र प्राप्त करता है।

**Returns:**
byte[][] - चैनल प्रोसेसिंग के लिए मानचित्र।
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


अधिकतम चैनल गिनती प्राप्त करता है।

मान: अधिकतम चैनल गिनती।

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


बाइट्स से डेटा लोड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| बाइट्स | byte[] | बाइट्स। |

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


वक्र का बिंदु हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| pointIndex | int | बिंदु का सूचकांक। |

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


वक्र का बिंदु अपडेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| pointIndex | int | बिंदु का सूचकांक। |
| x | byte | x स्थान। |
| y | byte | y स्थान। |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

