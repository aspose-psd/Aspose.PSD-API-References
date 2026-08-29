---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD 的 Java API 参考"
description: "AddNoise 智能过滤器。"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats/psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

AddNoise 智能过滤器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | 初始化 [AddNoiseSmartFilter](../../com.aspose.psd.fileformats/psd.layers.smartfilters.filters/addnoisesmartfilter) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [FilterType](#FilterType) | 当前智能过滤器的标识符。 |
## Methods

| Method | 描述 |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | 将当前过滤器应用于输入的 RasterImage 图像。 |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | 将当前过滤器应用于输入的 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 掩码数据。 |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | 对当前实例进行成员级克隆。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | 获取或设置噪声值的数量。 |
| [getBlendMode()](#getBlendMode--) | 获取或设置混合模式。 |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | 获取或设置噪声过滤器的分布。 |
| [getFilterId()](#getFilterId--) | 获取智能过滤器类型标识符。 |
| [getName()](#getName--) | 获取智能过滤器名称。 |
| [getOpacity()](#getOpacity--) | 获取或设置智能过滤器的不透明度值。 |
| [getSourceDescriptor()](#getSourceDescriptor--) | 包含智能过滤器数据的源描述符结构。 |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | 获取或设置智能过滤器的启用状态。 |
| [isMonochromatic()](#isMonochromatic--) | 获取或设置单色的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | 获取或设置噪声值的数量。 |
| [setBlendMode(long value)](#setBlendMode-long-) | 获取或设置混合模式。 |
| [setDistribution(int value)](#setDistribution-int-) | 获取或设置噪声过滤器的分布。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 获取或设置智能过滤器的启用状态。 |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | 获取或设置单色的值。 |
| [setOpacity(double value)](#setOpacity-double-) | 获取或设置智能过滤器的不透明度值。 |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | 将智能过滤器信息保存到 [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) 数据并返回。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


初始化 [AddNoiseSmartFilter](../../com.aspose.psd.fileformats/psd.layers.smartfilters.filters/addnoisesmartfilter) 类的新实例。

### FilterType {#FilterType}
```
public static final int FilterType
```


当前智能过滤器的标识符。

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


将当前过滤器应用于输入的 RasterImage 图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | 光栅图像。 |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


将当前过滤器应用于输入的 [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) 掩码数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 带有掩码数据的图层。 |

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


对当前实例进行成员级克隆。

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


获取或设置噪声值的数量。

**Returns:**
double
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


获取或设置混合模式。

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


获取或设置噪声过滤器的分布。

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


获取智能过滤器类型标识符。

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


获取智能过滤器名称。

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


获取或设置智能过滤器的不透明度值。

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


包含智能过滤器数据的源描述符结构。

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


获取或设置智能过滤器的启用状态。

**Returns:**
boolean
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


获取或设置单色的值。

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


获取或设置噪声值的数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


获取或设置混合模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


获取或设置噪声过滤器的分布。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


获取或设置智能过滤器的启用状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


获取或设置单色的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


获取或设置智能过滤器的不透明度值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


将智能过滤器信息保存到 [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) 数据并返回。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

