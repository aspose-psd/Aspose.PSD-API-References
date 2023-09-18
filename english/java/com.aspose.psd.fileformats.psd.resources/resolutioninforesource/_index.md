---
title: ResolutionInfoResource
second_title: Aspose.PSD for Java API Reference
description: The resolution info resource
type: docs
weight: 33
url: /java/com.aspose.psd.fileformats.psd.resources/resolutioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class ResolutionInfoResource extends ResourceBlock
```

The resolution info resource
## Constructors

| Constructor | Description |
| --- | --- |
| [ResolutionInfoResource()](#ResolutionInfoResource--) | Initializes a new instance of the [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource) class. |
## Fields

| Field | Description |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | The resource signature of ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | The regular Photoshop resource signature. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gets the resource data size in bytes. |
| [getHDpi()](#getHDpi--) | Horizontal DPI. |
| [getHResDisplayUnit()](#getHResDisplayUnit--) | Display units for horizontal resolution. |
| [getHeightDisplayUnit()](#getHeightDisplayUnit--) | Gets or sets the height display unit. |
| [getID()](#getID--) | Gets or sets the unique identifier for the resource. |
| [getMinimalVersion()](#getMinimalVersion--) | Gets the minimal required PSD version. |
| [getName()](#getName--) | Gets or sets the resource name. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [getVDpi()](#getVDpi--) | Vertical DPI. |
| [getVResDisplayUnit()](#getVResDisplayUnit--) | Display units for vertical resolution. |
| [getWidthDisplayUnit()](#getWidthDisplayUnit--) | Gets or sets the width display unit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setHDpi(FixedPointDecimal value)](#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Horizontal DPI. |
| [setHResDisplayUnit(int value)](#setHResDisplayUnit-int-) | Display units for horizontal resolution. |
| [setHeightDisplayUnit(int value)](#setHeightDisplayUnit-int-) | Gets or sets the height display unit. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setVDpi(FixedPointDecimal value)](#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-) | Vertical DPI. |
| [setVResDisplayUnit(int value)](#setVResDisplayUnit-int-) | Display units for vertical resolution. |
| [setWidthDisplayUnit(int value)](#setWidthDisplayUnit-int-) | Gets or sets the width display unit. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionInfoResource() {#ResolutionInfoResource--}
```
public ResolutionInfoResource()
```


Initializes a new instance of the [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource) class.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


The resource signature of ImageReady.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


The regular Photoshop resource signature.

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


Gets the resource data size in bytes.

Value: The resource data size.

**Returns:**
int
### getHDpi() {#getHDpi--}
```
public final FixedPointDecimal getHDpi()
```


Horizontal DPI.

Value: The horizontal dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getHResDisplayUnit() {#getHResDisplayUnit--}
```
public final int getHResDisplayUnit()
```


Display units for horizontal resolution. This only affects the user interface; the resolution is still stored in the PSD file as pixels/inch.

Value: The horizontal resolution display unit.

**Returns:**
int
### getHeightDisplayUnit() {#getHeightDisplayUnit--}
```
public final int getHeightDisplayUnit()
```


Gets or sets the height display unit.

Value: The height display unit.

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


Gets or sets the unique identifier for the resource.

Value: The unique identifier for the resource.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


Gets the minimal required PSD version.

Value: The minimal PSD version.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0).

Value: The resource name.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


Gets the resource signature. Should be always '8BIM'.

Value: The resource signature.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Gets the resource block size in bytes including its data.

Value: The resource block size.

**Returns:**
int
### getVDpi() {#getVDpi--}
```
public final FixedPointDecimal getVDpi()
```


Vertical DPI.

Value: The vertical dpi.

**Returns:**
[FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal)
### getVResDisplayUnit() {#getVResDisplayUnit--}
```
public final int getVResDisplayUnit()
```


Display units for vertical resolution.

Value: The vertical resolution display unit.

**Returns:**
int
### getWidthDisplayUnit() {#getWidthDisplayUnit--}
```
public final int getWidthDisplayUnit()
```


Gets or sets the width display unit.

Value: The width display unit.

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


Saves the resource block to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream to save the resource block to. |

### setHDpi(FixedPointDecimal value) {#setHDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setHDpi(FixedPointDecimal value)
```


Horizontal DPI.

Value: The horizontal dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setHResDisplayUnit(int value) {#setHResDisplayUnit-int-}
```
public final void setHResDisplayUnit(int value)
```


Display units for horizontal resolution. This only affects the user interface; the resolution is still stored in the PSD file as pixels/inch.

Value: The horizontal resolution display unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHeightDisplayUnit(int value) {#setHeightDisplayUnit-int-}
```
public final void setHeightDisplayUnit(int value)
```


Gets or sets the height display unit.

Value: The height display unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


Gets or sets the unique identifier for the resource.

Value: The unique identifier for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


Gets or sets the layer and mask information.

Value: The layer and mask information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0).

Value: The resource name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


Gets or sets the resource block state.

Value: The resource block state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVDpi(FixedPointDecimal value) {#setVDpi-com.aspose.psd.fileformats.psd.resources.FixedPointDecimal-}
```
public final void setVDpi(FixedPointDecimal value)
```


Vertical DPI.

Value: The vertical dpi.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) |  |

### setVResDisplayUnit(int value) {#setVResDisplayUnit-int-}
```
public final void setVResDisplayUnit(int value)
```


Display units for vertical resolution.

Value: The vertical resolution display unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWidthDisplayUnit(int value) {#setWidthDisplayUnit-int-}
```
public final void setWidthDisplayUnit(int value)
```


Gets or sets the width display unit.

Value: The width display unit.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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


Validates the resource values.

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

