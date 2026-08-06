---
title: "GridAndGuidesResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مورد الشبكة والإرشادات."
type: docs
weight: 20
url: /ar/java/com.aspose.psd.fileformats.psd.resources/gridandguidesresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class GridAndGuidesResource extends ResourceBlock
```

يمثل مورد الشبكة والإرشادات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GridAndGuidesResource()](#GridAndGuidesResource--) | ينشئ مثلاً جديداً من الفئة [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | توقيع المورد لـ ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | توقيع مورد Photoshop العادي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | يحصل على حجم بيانات المورد بالبايت. |
| [getGridCycleX()](#getGridCycleX--) | يحصل أو يعيّن دورة الشبكة الأفقية. |
| [getGridCycleY()](#getGridCycleY--) | يحصل أو يعيّن دورة الشبكة العمودية. |
| [getGuideCount()](#getGuideCount--) | يحصل على عدد كتل مورد الدليل. |
| [getGuides()](#getGuides--) | يحصل أو يعيّن الأدلة. |
| [getHeaderVersion()](#getHeaderVersion--) | يحصل أو يعيّن نسخة الرأس. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setGridCycleX(int value)](#setGridCycleX-int-) | يحصل أو يعيّن دورة الشبكة الأفقية. |
| [setGridCycleY(int value)](#setGridCycleY-int-) | يحصل أو يعيّن دورة الشبكة العمودية. |
| [setGuides(GuideResource[] value)](#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---) | يحصل أو يعيّن الأدلة. |
| [setHeaderVersion(int value)](#setHeaderVersion-int-) | يحصل أو يعيّن نسخة الرأس. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GridAndGuidesResource() {#GridAndGuidesResource--}
```
public GridAndGuidesResource()
```


ينشئ مثلاً جديداً من الفئة [GridAndGuidesResource](../../com.aspose.psd.fileformats.psd.resources/gridandguidesresource).

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
### getGridCycleX() {#getGridCycleX--}
```
public final int getGridCycleX()
```


يحصل أو يضبط دورة الشبكة الأفقية. القيمة الافتراضية هي 576.

القيمة: دورة الشبكة الأفقية.

**Returns:**
int
### getGridCycleY() {#getGridCycleY--}
```
public final int getGridCycleY()
```


يحصل أو يضبط دورة الشبكة العمودية. القيمة الافتراضية هي 576.

القيمة: دورة الشبكة العمودية.

**Returns:**
int
### getGuideCount() {#getGuideCount--}
```
public final int getGuideCount()
```


يحصل على عدد كتل مورد الدليل.

القيمة: عدد كتل موارد الدليل.

**Returns:**
int
### getGuides() {#getGuides--}
```
public final GuideResource[] getGuides()
```


يحصل أو يعيّن الأدلة.

القيمة: الأدلة.

**Returns:**
com.aspose.psd.fileformats.psd.resources.GuideResource[]
### getHeaderVersion() {#getHeaderVersion--}
```
public final int getHeaderVersion()
```


يحصل أو يضبط إصدار الرأس. يجب أن تكون هذه القيمة دائمًا 1.

القيمة: إصدار الرأس.

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

### setGridCycleX(int value) {#setGridCycleX-int-}
```
public final void setGridCycleX(int value)
```


يحصل أو يضبط دورة الشبكة الأفقية. القيمة الافتراضية هي 576.

القيمة: دورة الشبكة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGridCycleY(int value) {#setGridCycleY-int-}
```
public final void setGridCycleY(int value)
```


يحصل أو يضبط دورة الشبكة العمودية. القيمة الافتراضية هي 576.

القيمة: دورة الشبكة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setGuides(GuideResource[] value) {#setGuides-com.aspose.psd.fileformats.psd.resources.GuideResource---}
```
public final void setGuides(GuideResource[] value)
```


يحصل أو يعيّن الأدلة.

القيمة: الأدلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GuideResource\[\]](../../com.aspose.psd.fileformats.psd.resources/guideresource) |  |

### setHeaderVersion(int value) {#setHeaderVersion-int-}
```
public final void setHeaderVersion(int value)
```


يحصل أو يضبط إصدار الرأس. يجب أن تكون هذه القيمة دائمًا 1.

القيمة: إصدار الرأس.

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

