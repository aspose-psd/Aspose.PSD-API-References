---
title: "SmartFilter"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الفئة لمعالجة المنطق الأساسي للمرشحات الذكية."
type: docs
weight: 13
url: /ar/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

الفئة لمعالجة المنطق الأساسي للمرشحات الذكية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | يُنشئ مثلاً جديداً من الفئة [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | يطبق الفلتر الحالي على صورة RasterImage المدخلة. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | يطبق الفلتر الحالي على بيانات قناع [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) المدخلة. |
| [deepClone()](#deepClone--) | ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | يحصل على معرف نوع المرشح الذكي. |
| [getName()](#getName--) | يحصل على اسم المرشح الذكي. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط قيمة الشفافية للمرشح الذكي. |
| [getSourceDescriptor()](#getSourceDescriptor--) | هيكل الوصف المصدر مع بيانات المرشح الذكي. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | يحصل أو يضبط حالة التمكين للمرشح الذكي. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | يحصل أو يضبط حالة التمكين للمرشح الذكي. |
| [setOpacity(double value)](#setOpacity-double-) | يحصل أو يضبط قيمة الشفافية للمرشح الذكي. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | يحفظ معلومات المرشح الذكي إلى بيانات [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) ثم يرجع. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


يُنشئ مثلاً جديداً من الفئة [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) class.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


يطبق الفلتر الحالي على صورة RasterImage المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | الصورة النقطية. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


يطبق الفلتر الحالي على بيانات قناع [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | الطبقة مع بيانات القناع. |

### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


يحصل أو يضبط وضع المزج.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


يحصل على معرف نوع المرشح الذكي.

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
```


يحصل على اسم المرشح الذكي.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


يحصل أو يضبط قيمة الشفافية للمرشح الذكي.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


هيكل الوصف المصدر مع بيانات المرشح الذكي.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


يحصل أو يضبط حالة التمكين للمرشح الذكي.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


يحصل أو يضبط وضع المزج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


يحصل أو يضبط حالة التمكين للمرشح الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


يحصل أو يضبط قيمة الشفافية للمرشح الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


يحفظ معلومات المرشح الذكي إلى بيانات [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) ثم يرجع.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

