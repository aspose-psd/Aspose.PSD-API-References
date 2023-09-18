---
title: AnimatedDataSectionResource
second_title: Aspose.PSD for Java API Reference
description: The Animated Data Section Plug-In resource.
type: docs
weight: 10
url: /java/com.aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class AnimatedDataSectionResource extends ResourceBlock
```

The Animated Data Section Plug-In resource.
## Fields

| Field | Description |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | The resource signature of ImageReady. |
| [ResouceBlockSignature](#ResouceBlockSignature) | The regular Photoshop resource signature. |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized()](#create-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnimatedDataSection()](#getAnimatedDataSection--) | Gets or sets the animated data section structure. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Gets the resource data size in bytes. |
| [getID()](#getID--) | Gets or sets the unique identifier for the resource. |
| [getKeyName()](#getKeyName--) | The resource key name. |
| [getMinimalVersion()](#getMinimalVersion--) | Gets the minimal required PSD version. |
| [getName()](#getName--) | Gets or sets the resource name. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)](#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-) | Gets or sets the animated data section structure. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setKeyName_internalized(String value)](#setKeyName-internalized-java.lang.String-) | The resource key name. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setRoll_internalized(RollStructure value)](#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-) | Gets or sets the roll structure. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setUnknownLeftBytes_internalized(byte[] value)](#setUnknownLeftBytes-internalized-byte---) | The unknown bytes from original resource. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### create_internalized() {#create-internalized--}
```
public static AnimatedDataSectionResource create_internalized()
```




**Returns:**
[AnimatedDataSectionResource](../../com.aspose.psd.fileformats.psd.resources/animateddatasectionresource)
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
### getAnimatedDataSection() {#getAnimatedDataSection--}
```
public final AnimatedDataSectionStructure getAnimatedDataSection()
```


Gets or sets the animated data section structure.

**Returns:**
[AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure)
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
### getKeyName() {#getKeyName--}
```
public final String getKeyName()
```


The resource key name.

**Returns:**
java.lang.String
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

### setAnimatedDataSection_internalized(AnimatedDataSectionStructure value) {#setAnimatedDataSection-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.AnimatedDataSectionStructure-}
```
public final void setAnimatedDataSection_internalized(AnimatedDataSectionStructure value)
```


Gets or sets the animated data section structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AnimatedDataSectionStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure) |  |

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

### setKeyName_internalized(String value) {#setKeyName-internalized-java.lang.String-}
```
public final void setKeyName_internalized(String value)
```


The resource key name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setRoll_internalized(RollStructure value) {#setRoll-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure-}
```
public final void setRoll_internalized(RollStructure value)
```


Gets or sets the roll structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.layers.layerresources.RollStructure |  |

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

### setUnknownLeftBytes_internalized(byte[] value) {#setUnknownLeftBytes-internalized-byte---}
```
public final void setUnknownLeftBytes_internalized(byte[] value)
```


The unknown bytes from original resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

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

