---
title: "CurvesDiscreteManager"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Curves Adjustment Layer के लिए मैनेजर जो पिक्सेल मानचित्र को बदलता है"
type: docs
weight: 25
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

कर्व्स एडजस्टमेंट लेयर के लिए मैनेजर जो पिक्सेल्स का मैप मैनीपुलेट करता है
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | नया उदाहरण प्रारंभ करता है [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | रिसोर्स के लिए बाइट्स प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | फ़िल्टर प्रोसेसिंग के लिए मानचित्र प्राप्त करता है |
| [getMaxChannelCount()](#getMaxChannelCount--) | अधिकतम चैनल गिनती प्राप्त करता है। |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | स्थिति में मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | बाइट्स से डेटा लोड करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | स्थिति में डिफ़ॉल्ट मान सेट करता है। |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | स्थिति में मान सेट करता है। |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | पूरे चैनल का मान सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


नया उदाहरण प्रारंभ करता है [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxChannelCount | int | अधिकतम चैनल गिनती। |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


फ़िल्टर प्रोसेसिंग के लिए मानचित्र प्राप्त करता है

**Returns:**
byte[][] - ट्रांसफ़ॉर्मेशन मानचित्र
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


अधिकतम चैनल गिनती प्राप्त करता है।

मान: अधिकतम चैनल गिनती।

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


स्थिति में मान प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| position | byte | स्थिति। |

**Returns:**
byte - उसकी स्थिति द्वारा कर्व का मान
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


स्थिति में डिफ़ॉल्ट मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| position | byte | स्थिति। |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


स्थिति में मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| position | byte | स्थिति। |
| मान | byte | मान। |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


पूरे चैनल का मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelIndex | int | चैनल का सूचकांक। |
| channelValue | byte[] | चैनल मान। |

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

