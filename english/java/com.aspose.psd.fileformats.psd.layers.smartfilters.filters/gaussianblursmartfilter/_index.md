---
title: GaussianBlurSmartFilter
second_title: Aspose.PSD for Java API Reference
description: The GaussianBlur smart filter.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class GaussianBlurSmartFilter extends SmartFilter
```

The GaussianBlur smart filter.
## Constructors

| Constructor | Description |
| --- | --- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter--) | Initializes a new instance of the [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) class. |
## Fields

| Field | Description |
| --- | --- |
| [FilterType](#FilterType) | The identifier of current smart filter. |
## Methods

| Method | Description |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Applies the current filter to input  RasterImage  image. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Applies the current filter to input [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) mask data. |
| [crate_internalized(DescriptorStructure sourceDescriptor)](#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Makes the memberwise clone of the current instance of the type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Gets or sets the blending mode. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Gets the smart filter type identifier. |
| [getName()](#getName--) | Gets the smart filter name. |
| [getOpacity()](#getOpacity--) | Gets or sets the opacity value of smart filter. |
| [getRadius()](#getRadius--) | Gets or sets the radius of gaussian smart filter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | The source descriptor structure with smart filter data. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Gets or sets the is enabled status of the smart filter. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Gets or sets the blending mode. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Gets or sets the is enabled status of the smart filter. |
| [setOpacity(double value)](#setOpacity-double-) | Gets or sets the opacity value of smart filter. |
| [setRadius(double value)](#setRadius-double-) | Gets or sets the radius of gaussian smart filter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Saves the smart filter information to [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) data and return. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussianBlurSmartFilter() {#GaussianBlurSmartFilter--}
```
public GaussianBlurSmartFilter()
```


Initializes a new instance of the [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) class.

### FilterType {#FilterType}
```
public static final int FilterType
```


The identifier of current smart filter.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Applies the current filter to input  RasterImage  image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | The raster image. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Applies the current filter to input [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) mask data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | The layer with mask data. |

### crate_internalized(DescriptorStructure sourceDescriptor) {#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static GaussianBlurSmartFilter crate_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Makes the memberwise clone of the current instance of the type.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Gets or sets the blending mode.

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
public int getFilterId()
```


Gets the smart filter type identifier.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Gets the smart filter name.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Gets or sets the opacity value of smart filter.

**Returns:**
double
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Gets or sets the radius of gaussian smart filter.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


The source descriptor structure with smart filter data.

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


Gets or sets the is enabled status of the smart filter.

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


Gets or sets the blending mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Gets or sets the is enabled status of the smart filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Gets or sets the opacity value of smart filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Gets or sets the radius of gaussian smart filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Saves the smart filter information to [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) data and return.

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

