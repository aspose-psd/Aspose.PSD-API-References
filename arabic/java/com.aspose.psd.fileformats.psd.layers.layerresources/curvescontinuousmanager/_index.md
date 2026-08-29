---
title: "CurvesContinuousManager"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مدير طبقة تعديل المنحنيات الذي يتحكم في المنحنيات"
type: docs
weight: 24
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

مدير طبقة تعديل المنحنيات الذي يتحكم في المنحنيات
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | ينشئ مثيلًا جديدًا للفئة [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | يضيف نقطة المنحنى. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | يحصل على البايتات للمورد. |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | يحصل على نقطة المنحنى حسب الفهرس. |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | يحصل على عدد نقاط المنحنى. |
| [getMap_internalized()](#getMap-internalized--) | يحصل على الخريطة لمعالجة الفلتر. |
| [getMaxChannelCount()](#getMaxChannelCount--) | يحصل على الحد الأقصى لعدد القنوات. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | يحمّل البيانات من البايتات. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | يزيل نقطة المنحنى. |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | يحدّث نقطة المنحنى. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


ينشئ مثيلًا جديدًا للفئة [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxChannelCount | int | العدد الأقصى للقنوات. |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


يضيف نقطة المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| س | byte | موقع x. |
| ص | byte | موقع y. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


يحصل على البايتات للمورد.

**Returns:**
byte[] - بايتات لتكوين CurvResource
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


يحصل على نقطة المنحنى حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| pointIndex | int | فهرس النقطة. |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


يحصل على عدد نقاط المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |

**Returns:**
int - عدد Curve Point في القناة
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


يحصل على الخريطة لمعالجة الفلتر.

**Returns:**
byte[][] - خريطة لمعالجة القناة.
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


يحصل على الحد الأقصى لعدد القنوات.

القيمة: العدد الأقصى للقنوات.

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


يحمّل البيانات من البايتات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات. |

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


يزيل نقطة المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| pointIndex | int | فهرس النقطة. |

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


يحدّث نقطة المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| pointIndex | int | فهرس النقطة. |
| س | byte | موقع x. |
| ص | byte | موقع y. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

