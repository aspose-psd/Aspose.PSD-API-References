---
title: WorkingPathResource
second_title: Aspose.PSD for Java API Reference
description: Working path resource.
type: docs
weight: 43
url: /java/com.aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class WorkingPathResource extends ResourceBlock implements IVectorPathData
```

Working path resource.
## Constructors

| Constructor | Description |
| --- | --- |
| [WorkingPathResource(byte[] dataBytes)](#WorkingPathResource-byte---) | Initializes a new instance of the [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource) class. |
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
| [getPaths()](#getPaths--) | Gets or sets the path records. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Gets or sets a value indicating whether this instance is disabled. |
| [isInverted()](#isInverted--) | Gets or sets a value indicating whether this instance is inverted. |
| [isNotLinked()](#isNotLinked--) | Gets or sets a value indicating whether this instance is not linked. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Gets or sets a value indicating whether this instance is disabled. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setInverted(boolean value)](#setInverted-boolean-) | Gets or sets a value indicating whether this instance is inverted. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Gets or sets a value indicating whether this instance is not linked. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Gets or sets the path records. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WorkingPathResource(byte[] dataBytes) {#WorkingPathResource-byte---}
```
public WorkingPathResource(byte[] dataBytes)
```


Initializes a new instance of the [WorkingPathResource](../../com.aspose.psd.fileformats.psd.resources/workingpathresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataBytes | byte[] | The data of the vector path. |

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
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Gets or sets the path records.

Value: The paths.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets or sets the version.

Value: The version.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Gets or sets a value indicating whether this instance is disabled.

Value:  true  if this instance is disabled; otherwise,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Gets or sets a value indicating whether this instance is inverted.

Value:  true  if this instance is inverted; otherwise,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Gets or sets a value indicating whether this instance is not linked.

Value:  true  if this instance is not linked; otherwise,  false .

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


Saves the resource block to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream to save the resource block to. |

### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Gets or sets a value indicating whether this instance is disabled.

Value:  true  if this instance is disabled; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Gets or sets a value indicating whether this instance is inverted.

Value:  true  if this instance is inverted; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Gets or sets a value indicating whether this instance is not linked.

Value:  true  if this instance is not linked; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Gets or sets the path records.

Value: The paths.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

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

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Gets or sets the version.

Value: The version.

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

