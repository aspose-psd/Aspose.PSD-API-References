---
title: "CurvesDiscreteManager"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مدير طبقة تعديل المنحنيات التي تُعدّل خريطة البكسلات"
type: docs
weight: 25
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

مدير طبقة تعديل المنحنيات الذي يتحكم في خريطة البكسلات
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | ينشئ مثلاً جديداً من الفئة [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | يحصل على البايتات للمورد. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | يحصل على الخريطة لمعالجة الفلتر. |
| [getMaxChannelCount()](#getMaxChannelCount--) | يحصل على الحد الأقصى لعدد القنوات. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | يحصل على القيمة في الموضع. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | يحمّل البيانات من البايتات. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | يضبط إلى القيمة الافتراضية في الموضع. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | يضبط القيمة في الموضع. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | يضبط قيمة القناة بالكامل. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


ينشئ مثلاً جديداً من الفئة [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxChannelCount | int | العدد الأقصى للقنوات. |

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
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


يحصل على الخريطة لمعالجة الفلتر.

**Returns:**
byte[][] - خريطة التحويل
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


يحصل على الحد الأقصى لعدد القنوات.

القيمة: العدد الأقصى للقنوات.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


يحصل على القيمة في الموضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| position | byte | الموضع. |

**Returns:**
byte - قيمة المنحنى حسب موضعه
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




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


يضبط إلى القيمة الافتراضية في الموضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| position | byte | الموضع. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


يضبط القيمة في الموضع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| position | byte | الموضع. |
| القيمة | byte | القيمة. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


يضبط قيمة القناة بالكامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelIndex | int | فهرس القناة. |
| channelValue | byte[] | قيمة القناة. |

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

