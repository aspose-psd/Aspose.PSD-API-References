---
title: "PattResourceData"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة لتخزين بيانات النمط للموارد."
type: docs
weight: 67
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

الفئة لتخزين بيانات النمط للموارد [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | ينشئ مثيلاً جديدًا للفئة [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | يعيد رمز طريقة الضغط المستخرج من قنوات النمط. |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | ينشئ بيانات النمط الافتراضية. |
| [getHeight()](#getHeight--) | يحصل على الارتفاع. |
| [getImageMode()](#getImageMode--) | يحصل على وضع الصورة. |
| [getLength()](#getLength--) | يحصل على طول النمط. |
| [getName()](#getName--) | يحصل أو يضبط الاسم. |
| [getPatternData()](#getPatternData--) | يحصل على بيانات النمط. |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | قائمة مصفوفة الذاكرة. |
| [getPatternId()](#getPatternId--) | يحصل أو يعيّن معرف النمط. |
| [getVersion()](#getVersion--) | يحصل على الإصدار. |
| [getWidth()](#getWidth--) | يحصل على العرض. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | يحفظ بيانات النمط. |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | يحصل على الارتفاع. |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | يحصل على وضع الصورة. |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | يحصل أو يضبط جدول ألوان الفهرس. |
| [setName(String value)](#setName-java.lang.String-) | يحصل أو يضبط الاسم. |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | يضبط مخزن بكسل النمط وحجم الهدف، ويحدّث العرض ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / الارتفاع ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))، ويخزن البيانات للحفظ باستخدام وضع الضغط الافتراضي (0). |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | قائمة مصفوفة الذاكرة. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | يحصل أو يعيّن معرف النمط. |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | يضبط مخزن بكسل النمط وحجم الهدف، ويحدّث العرض ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / الارتفاع ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))، ويخزن البيانات للحفظ باستخدام وضع الضغط المحدد. |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | يحصل على الإصدار. |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | يحصل على العرض. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


ينشئ مثيلاً جديدًا للفئة [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


يعيد رمز طريقة الضغط المستخرج من قنوات النمط.

**Returns:**
بايت - رمز الضغط: 0 \\u2014 غير مضغوط/خام; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


ينشئ بيانات النمط الافتراضية.

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


يحصل على الارتفاع.

القيمة: الارتفاع.

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


يحصل على وضع الصورة.

القيمة: وضع الصورة.

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


يحصل على طول النمط.

القيمة: طول النمط.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


يحصل أو يضبط الاسم.

القيمة: الاسم.

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


يحصل على بيانات النمط.

القيمة: بيانات النمط.

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


قائمة مصفوفة الذاكرة.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


يحصل أو يعيّن معرف النمط.

القيمة: معرّف النمط.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


يحصل على الإصدار.

القيمة: الإصدار.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


يحصل على العرض.

القيمة: العرض.

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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


يحفظ بيانات النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | حاوية الدفق التي سيتم الحفظ إليها. |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


يحصل على الارتفاع.

القيمة: الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


يحصل على وضع الصورة.

القيمة: وضع الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


يحصل أو يضبط جدول ألوان الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل أو يضبط الاسم.

القيمة: الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


يضبط مخزن بكسل النمط وحجم الهدف، ويحدّث العرض ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / الارتفاع ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))، ويخزن البيانات للحفظ باستخدام وضع الضغط الافتراضي (0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | بكسلات 32-بت بتنسيق 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود بكسل النمط. |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


قائمة مصفوفة الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


يحصل أو يعيّن معرف النمط.

القيمة: معرّف النمط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


يضبط مخزن بكسل النمط وحجم الهدف، ويحدّث العرض ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / الارتفاع ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-))، ويخزن البيانات للحفظ باستخدام وضع الضغط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بكسلات | int[] | بكسلات 32-بت بتنسيق 0xAARRGGBB. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | حدود بكسل النمط. |
| compressionMode | byte | وضع الضغط المستخدم لتحديد ضغط بيانات النمط عند حفظ ملف psd. |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


يحصل على الإصدار.

القيمة: الإصدار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


يحصل على العرض.

القيمة: العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

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

