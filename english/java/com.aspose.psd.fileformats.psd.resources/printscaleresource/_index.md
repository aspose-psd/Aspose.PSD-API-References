---
title: PrintScaleResource
second_title: Aspose.PSD for Java API Reference
description: Print Scale resource
type: docs
weight: 31
url: /java/com.aspose.psd.fileformats.psd.resources/printscaleresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class PrintScaleResource extends ResourceBlock
```

Print Scale resource
## Constructors

| Constructor | Description |
| --- | --- |
| [PrintScaleResource()](#PrintScaleResource--) | Initializes a new instance of the [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource) class. |
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
| [getID()](#getID--) | Gets or sets the unique identifier for the resource. |
| [getMinimalVersion()](#getMinimalVersion--) | Gets the minimal required PSD version. |
| [getName()](#getName--) | Gets or sets the resource name. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [getStyle()](#getStyle--) | Gets or sets the style. |
| [getXLocation()](#getXLocation--) | Gets or sets the x location. |
| [getYLocation()](#getYLocation--) | Gets or sets the y location. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setScale(float value)](#setScale-float-) | Gets or sets the scale. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setStyle(short value)](#setStyle-short-) | Gets or sets the style. |
| [setXLocation(float value)](#setXLocation-float-) | Gets or sets the x location. |
| [setYLocation(float value)](#setYLocation-float-) | Gets or sets the y location. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintScaleResource() {#PrintScaleResource--}
```
public PrintScaleResource()
```


Initializes a new instance of the [PrintScaleResource](../../com.aspose.psd.fileformats.psd.resources/printscaleresource) class.

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
### getScale() {#getScale--}
```
public final float getScale()
```


Gets or sets the scale.

Value: The scale.

**Returns:**
float
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
### getStyle() {#getStyle--}
```
public final short getStyle()
```


Gets or sets the style.

Value: The style.

**Returns:**
short
### getXLocation() {#getXLocation--}
```
public final float getXLocation()
```


Gets or sets the x location.

Value: The x location.

**Returns:**
float
### getYLocation() {#getYLocation--}
```
public final float getYLocation()
```


Gets or sets the y location.

Value: The y location.

**Returns:**
float
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

### setScale(float value) {#setScale-float-}
```
public final void setScale(float value)
```


Gets or sets the scale.

Value: The scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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

### setStyle(short value) {#setStyle-short-}
```
public final void setStyle(short value)
```


Gets or sets the style.

Value: The style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setXLocation(float value) {#setXLocation-float-}
```
public final void setXLocation(float value)
```


Gets or sets the x location.

Value: The x location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setYLocation(float value) {#setYLocation-float-}
```
public final void setYLocation(float value)
```


Gets or sets the y location.

Value: The y location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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

