---
title: "ResolutionInfoResource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "مورد معلومات الدقة"
type: docs
weight: 33
url: /ar/java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

مورد معلومات الدقة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | ينشئ مثيلًا جديدًا للفئة [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource). |
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
| [getHDpi()](#getHDpi--) | دقة أفقية DPI. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | وحدات العرض لدقة الأفقية. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | يحصل أو يضبط وحدة عرض الارتفاع. |
| [getID()](#getID--) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [getMinimalVersion()](#getMinimalVersion--) | يحصل على الحد الأدنى المطلوب لإصدار PSD. |
| [getName()](#getName--) | يحصل على أو يعيّن اسم المورد. |
| [getSignature()](#getSignature--) | يحصل على توقيع المورد. |
| [getSize()](#getSize--) | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |
| [getVDpi()](#getVDpi--) | دقة عمودية DPI. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | وحدات العرض لدقة العمودية. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | يحصل أو يضبط وحدة عرض العرض. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | يحفظ كتلة المورد إلى الدفق المحدد. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | دقة أفقية DPI. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | وحدات العرض لدقة الأفقية. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | يحصل أو يضبط وحدة عرض الارتفاع. |
| [setID(short value)](#setID-short-) | يحصل أو يعيّن المعرف الفريد للمورد. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | يحصل على أو يعيّن معلومات الطبقة والقناع. |
| [setName(String value)](#setName-java.lang.String-) | يحصل على أو يعيّن اسم المورد. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | يحصل على أو يعيّن حالة كتلة المورد. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | دقة عمودية DPI. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | وحدات العرض لدقة العمودية. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | يحصل أو يضبط وحدة عرض العرض. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | يُحقق من صحة قيم المورد. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


ينشئ مثيلًا جديدًا للفئة [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource).

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
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


دقة أفقية DPI.

القيمة: دقة الأفقية dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


وحدات العرض لدقة الأفقية. هذا يؤثر فقط على واجهة المستخدم؛ لا تزال الدقة مخزنة في ملف PSD كوحدات بكسل/إنش.

القيمة: وحدة عرض دقة الأفقية.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


يحصل أو يضبط وحدة عرض الارتفاع.

القيمة: وحدة عرض الارتفاع.

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


يحصل على الحد الأدنى المطلوب لإصدار PSD.

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
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


دقة عمودية DPI.

القيمة: دقة العمودية dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


وحدات العرض لدقة العمودية.

القيمة: وحدة عرض دقة العمودية.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


يحصل أو يضبط وحدة عرض العرض.

القيمة: وحدة عرض العرض.

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

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


دقة أفقية DPI.

القيمة: دقة الأفقية dpi.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


وحدات العرض لدقة الأفقية. هذا يؤثر فقط على واجهة المستخدم؛ لا تزال الدقة مخزنة في ملف PSD كوحدات بكسل/إنش.

القيمة: وحدة عرض دقة الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


يحصل أو يضبط وحدة عرض الارتفاع.

القيمة: وحدة عرض الارتفاع.

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

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


دقة عمودية DPI.

القيمة: دقة العمودية dpi.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


وحدات العرض لدقة العمودية.

القيمة: وحدة عرض دقة العمودية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


يحصل أو يضبط وحدة عرض العرض.

القيمة: وحدة عرض العرض.

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

