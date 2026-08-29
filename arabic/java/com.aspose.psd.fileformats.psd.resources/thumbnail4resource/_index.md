---
title: "Thumbnail4Resource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مورد الصورة المصغرة لـ psd 4.0."
type: docs
weight: 34
url: /ar/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

يمثل مورد الصورة المصغرة لـ psd 4.0.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | ينشئ مثيلاً جديدًا للفئة [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | توقيع المورد لـ ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | توقيع مورد Photoshop العادي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | يحصل أو يضبط عدد البتات لكل بكسل. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات المورد بالبايت. |
| [getFormat()](#getFormat--) | يحصل أو يضبط تنسيق بيانات الصورة المصغرة. |
| [getHeight()](#getHeight--) | يحصل أو يضبط ارتفاع الصورة المصغرة بالبكسل. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getJpegOptions()](#getJpegOptions--) | يحصل أو يضبط خيارات JPEG. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getPlanesCount()](#getPlanesCount--) | يحصل أو يضبط عدد المستويات. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | يحصل أو يضبط الحجم بعد الضغط. |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | يحصل أو يضبط بيانات الصورة المصغرة 32-بت ARGB. |
| [getThumbnailData()](#getThumbnailData--) | يحصل أو يضبط بيانات الصورة المصغرة. |
| [getTotalSize()](#getTotalSize--) | يحصل على إجمالي حجم البيانات. |
| [getWidth()](#getWidth--) | يحصل أو يضبط عرض الصورة المصغرة بالبكسل. |
| [getWidthBytes()](#getWidthBytes--) | يحصل على عرض الصف بالبايت. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setBitsPixel(short value)](#setBitsPixel-short-) | يحصل أو يضبط عدد البتات لكل بكسل. |
| [setFormat(int value)](#setFormat-int-) | يحصل أو يضبط تنسيق بيانات الصورة المصغرة. |
| [setHeight(int value)](#setHeight-int-) | يحصل أو يضبط ارتفاع الصورة المصغرة بالبكسل. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | يحصل أو يضبط خيارات JPEG. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setPlanesCount(short value)](#setPlanesCount-short-) | يحصل أو يضبط عدد المستويات. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | يحصل أو يضبط بيانات الصورة المصغرة 32-بت ARGB. |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | يحصل أو يضبط بيانات الصورة المصغرة. |
| [setWidth(int value)](#setWidth-int-) | يحصل أو يضبط عرض الصورة المصغرة بالبكسل. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


ينشئ مثيلاً جديدًا للفئة [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource).

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


توقيع المورد لـ ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


توقيع مورد Photoshop العادي.

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


يحصل أو يضبط عدد البتات لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة المصغرة.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


يحصل على حجم بيانات المورد بالبايت.

القيمة: حجم بيانات المورد.

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


يحصل أو يضبط تنسيق بيانات الصورة المصغرة.

القيمة: تنسيق بيانات الصورة المصغرة.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل أو يضبط ارتفاع الصورة المصغرة بالبكسل.

القيمة: ارتفاع الصورة المصغرة.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


يحصل أو يعيّن المعرف الفريد للمورد.

القيمة: المعرف الفريد للمورد.

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


يحصل أو يضبط خيارات JPEG. مناسب عندما يتم حفظ مورد الصورة المصغرة بتنسيق ملف JPEG فقط. هذا الخيار لا يؤثر عندما يكون التنسيق RAW محددًا.

القيمة: خيارات JPEG.

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


يحصل على الحد الأدنى لإصدار PSD المطلوب.

القيمة: الحد الأدنى لإصدار PSD.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


يحصل على أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لجعل الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0).

القيمة: اسم المورد.

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


يحصل أو يضبط عدد المستويات.

القيمة: عدد مستويات الصورة المصغرة.

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'.

القيمة: توقيع المورد.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها.

القيمة: حجم كتلة المورد.

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


يحصل أو يضبط الحجم بعد الضغط. يُستخدم للتحقق من التناسق.

القيمة: الحجم بعد الضغط.

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


يحصل أو يضبط بيانات الصورة المصغرة 32-بت ARGB.

القيمة: بيانات الصورة المصغرة 32-بت ARGB.

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


يحصل أو يضبط بيانات الصورة المصغرة.

القيمة: بيانات الصورة المصغرة.

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


يحصل على إجمالي حجم البيانات.

القيمة: إجمالي حجم البيانات.

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل أو يضبط عرض الصورة المصغرة بالبكسل.

القيمة: عرض الصورة المصغرة.

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


يحصل على عرض الصف بالبايت.

القيمة: عرض الصف بالبايت.

**Returns:**
int
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


يحفظ كتلة المورد إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | الدفق لحفظ كتلة المورد إليه. |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


يحصل أو يضبط عدد البتات لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


يحصل أو يضبط تنسيق بيانات الصورة المصغرة.

القيمة: تنسيق بيانات الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يحصل أو يضبط ارتفاع الصورة المصغرة بالبكسل.

القيمة: ارتفاع الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


يحصل أو يعيّن المعرف الفريد للمورد.

القيمة: المعرف الفريد للمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


يحصل أو يضبط خيارات JPEG. مناسب عندما يتم حفظ مورد الصورة المصغرة بتنسيق ملف JPEG فقط. هذا الخيار لا يؤثر عندما يكون التنسيق RAW محددًا.

القيمة: خيارات JPEG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


يحصل على أو يعيّن معلومات الطبقة والقناع.

القيمة: معلومات الطبقة والقناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل على أو يعيّن اسم المورد. سلسلة باسكال، مملوءة لجعل الحجم زوجيًا (اسم فارغ يتكون من بايتين قيمتهما 0).

القيمة: اسم المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


يحصل أو يضبط عدد المستويات.

القيمة: عدد مستويات الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التوقيع | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


يحصل على أو يعيّن حالة كتلة المورد.

القيمة: حالة كتلة المورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


يحصل أو يضبط بيانات الصورة المصغرة 32-بت ARGB.

القيمة: بيانات الصورة المصغرة 32-بت ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


يحصل أو يضبط بيانات الصورة المصغرة.

القيمة: بيانات الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يحصل أو يضبط عرض الصورة المصغرة بالبكسل.

القيمة: عرض الصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


يُحقق من صحة قيم المورد.

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

