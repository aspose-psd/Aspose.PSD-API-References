---
title: DisplaceSmartFilter
second_title: Aspose.PSD for Java API Reference
description: The Displace smart filter.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/displacesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class DisplaceSmartFilter extends SmartFilter
```

The Displace smart filter.
## Constructors

| Constructor | Description |
| --- | --- |
| [DisplaceSmartFilter(String displaceMapPath, boolean isDisplacementMapEmbedded)](#DisplaceSmartFilter-java.lang.String-boolean-) | Initializes a new instance of the [DisplaceSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/displacesmartfilter) class. |
## Fields

| Field | Description |
| --- | --- |
| [FilterType](#FilterType) | The identifier of current smart filter (class ID "Dspl"). |
## Methods

| Method | Description |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Applies the current filter to input  RasterImage  image. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Applies the current filter to input [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) mask data. |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Makes the memberwise clone of the current instance of the type. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Gets or sets the blending mode. |
| [getClass()](#getClass--) |  |
| [getDisplaceMapData()](#getDisplaceMapData--) | Gets or sets the embedded displacement map data (DspD). |
| [getDisplacementMapPath()](#getDisplacementMapPath--) | Gets the displacement map full path extracted from the DspF structure, or null if not found. |
| [getDisplacementMethod()](#getDisplacementMethod--) | Gets or sets the displacement method. |
| [getFilterId()](#getFilterId--) | Gets the smart filter type identifier. |
| [getHorizontalScale()](#getHorizontalScale--) | Gets or sets the horizontal scale (percent). |
| [getName()](#getName--) | Gets the smart filter name. |
| [getOpacity()](#getOpacity--) | Gets or sets the opacity value of smart filter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | The source descriptor structure with smart filter data. |
| [getUndefinedAreas()](#getUndefinedAreas--) | Gets or sets the missing file handling method. |
| [getVerticalScale()](#getVerticalScale--) | Gets or sets the vertical scale (percent). |
| [hashCode()](#hashCode--) |  |
| [isDisplacementMapEmbedded()](#isDisplacementMapEmbedded--) | Gets or sets the embedded flag (EmbF) value. |
| [isEnabled()](#isEnabled--) | Gets or sets the is enabled status of the smart filter. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Gets or sets the blending mode. |
| [setDisplacementMethod(int value)](#setDisplacementMethod-int-) | Gets or sets the displacement method. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Gets or sets the is enabled status of the smart filter. |
| [setHorizontalScale(double value)](#setHorizontalScale-double-) | Gets or sets the horizontal scale (percent). |
| [setOpacity(double value)](#setOpacity-double-) | Gets or sets the opacity value of smart filter. |
| [setUndefinedAreas(int value)](#setUndefinedAreas-int-) | Gets or sets the missing file handling method. |
| [setVerticalScale(double value)](#setVerticalScale-double-) | Gets or sets the vertical scale (percent). |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Serialises the filter back to a descriptor structure. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DisplaceSmartFilter(String displaceMapPath, boolean isDisplacementMapEmbedded) {#DisplaceSmartFilter-java.lang.String-boolean-}
```
public DisplaceSmartFilter(String displaceMapPath, boolean isDisplacementMapEmbedded)
```


Initializes a new instance of the [DisplaceSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/displacesmartfilter) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displaceMapPath | java.lang.String | The displacement map file path. |
| isDisplacementMapEmbedded | boolean | if set to  true  the displacement map is embedded. |

### FilterType {#FilterType}
```
public static final int FilterType
```


The identifier of current smart filter (class ID "Dspl").

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

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static DisplaceSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[DisplaceSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/displacesmartfilter)
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
### getDisplaceMapData() {#getDisplaceMapData--}
```
public final byte[] getDisplaceMapData()
```


Gets or sets the embedded displacement map data (DspD).

**Returns:**
byte[]
### getDisplacementMapPath() {#getDisplacementMapPath--}
```
public final String getDisplacementMapPath()
```


Gets the displacement map full path extracted from the DspF structure, or null if not found.

**Returns:**
java.lang.String
### getDisplacementMethod() {#getDisplacementMethod--}
```
public final int getDisplacementMethod()
```


Gets or sets the displacement method.

**Returns:**
int
### getFilterId() {#getFilterId--}
```
public int getFilterId()
```


Gets the smart filter type identifier.

**Returns:**
int
### getHorizontalScale() {#getHorizontalScale--}
```
public final double getHorizontalScale()
```


Gets or sets the horizontal scale (percent).

**Returns:**
double
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
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


The source descriptor structure with smart filter data.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getUndefinedAreas() {#getUndefinedAreas--}
```
public final int getUndefinedAreas()
```


Gets or sets the missing file handling method.

**Returns:**
int
### getVerticalScale() {#getVerticalScale--}
```
public final double getVerticalScale()
```


Gets or sets the vertical scale (percent).

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisplacementMapEmbedded() {#isDisplacementMapEmbedded--}
```
public final boolean isDisplacementMapEmbedded()
```


Gets or sets the embedded flag (EmbF) value.

**Returns:**
boolean
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

### setDisplacementMethod(int value) {#setDisplacementMethod-int-}
```
public final void setDisplacementMethod(int value)
```


Gets or sets the displacement method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Gets or sets the is enabled status of the smart filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHorizontalScale(double value) {#setHorizontalScale-double-}
```
public final void setHorizontalScale(double value)
```


Gets or sets the horizontal scale (percent).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Gets or sets the opacity value of smart filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setUndefinedAreas(int value) {#setUndefinedAreas-int-}
```
public final void setUndefinedAreas(int value)
```


Gets or sets the missing file handling method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalScale(double value) {#setVerticalScale-double-}
```
public final void setVerticalScale(double value)
```


Gets or sets the vertical scale (percent).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Serialises the filter back to a descriptor structure.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
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

