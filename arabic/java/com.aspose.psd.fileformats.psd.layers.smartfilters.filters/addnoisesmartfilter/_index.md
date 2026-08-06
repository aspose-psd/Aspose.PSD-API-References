---
title: "AddNoiseSmartFilter"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "المرشح الذكي AddNoise."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

المرشح الذكي AddNoise.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | يُنشئ مثيلاً جديدًا للفئة [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [FilterType](#FilterType) | معرف المرشح الذكي الحالي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | يطبق الفلتر الحالي على صورة RasterImage المدخلة. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | يطبق الفلتر الحالي على بيانات قناع [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) المدخلة. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | ينشئ نسخة مستنسخة عضوًا من المثيل الحالي للنوع. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | يحصل أو يضبط مقدار قيمة الضوضاء. |
| [getBlendMode()](#getBlendMode--) | يحصل أو يضبط وضع المزج. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | يحصل أو يضبط توزيع مرشح الضوضاء. |
| [getFilterId()](#getFilterId--) | يحصل على معرف نوع المرشح الذكي. |
| [getName()](#getName--) | يحصل على اسم المرشح الذكي. |
| [getOpacity()](#getOpacity--) | يحصل أو يضبط قيمة الشفافية للمرشح الذكي. |
| [getSourceDescriptor()](#getSourceDescriptor--) | هيكل الوصف المصدر مع بيانات المرشح الذكي. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | يحصل أو يضبط حالة التمكين للمرشح الذكي. |
| [isMonochromatic()](#isMonochromatic--) | يحصل أو يضبط قيمة أحادية اللون. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | يحصل أو يضبط مقدار قيمة الضوضاء. |
| [setBlendMode(long value)](#setBlendMode-long-) | يحصل أو يضبط وضع المزج. |
| [setDistribution(int value)](#setDistribution-int-) | يحصل أو يضبط توزيع مرشح الضوضاء. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | يحصل أو يضبط حالة التمكين للمرشح الذكي. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | يحصل أو يضبط قيمة أحادية اللون. |
| [setOpacity(double value)](#setOpacity-double-) | يحصل أو يضبط قيمة الشفافية للمرشح الذكي. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | يحفظ معلومات المرشح الذكي إلى بيانات [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) ثم يرجع. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


يُنشئ مثيلاً جديدًا للفئة [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter).

### FilterType {#FilterType}
```
public static final int FilterType
```


معرف المرشح الذكي الحالي.

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

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


يحصل أو يضبط مقدار قيمة الضوضاء.

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


يحصل أو يضبط توزيع مرشح الضوضاء.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


يحصل على معرف نوع المرشح الذكي.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


يحصل أو يضبط قيمة أحادية اللون.

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


يحصل أو يضبط مقدار قيمة الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


يحصل أو يضبط وضع المزج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


يحصل أو يضبط توزيع مرشح الضوضاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


يحصل أو يضبط حالة التمكين للمرشح الذكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


يحصل أو يضبط قيمة أحادية اللون.

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

