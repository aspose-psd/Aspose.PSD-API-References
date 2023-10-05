---
title: VersionInfoResource
second_title: Aspose.PSD for Java API Reference
description: Version Info resource
type: docs
weight: 41
url: /java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

Version Info resource
## Constructors

| Constructor | Description |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | Initializes a new instance of the [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) class. |
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
| [getFileVersion()](#getFileVersion--) | Gets or sets the file version. |
| [getID()](#getID--) | Gets or sets the unique identifier for the resource. |
| [getMinimalVersion()](#getMinimalVersion--) | Gets the minimal required PSD version. |
| [getName()](#getName--) | Gets or sets the resource name. |
| [getReaderName()](#getReaderName--) | Gets or sets the name of the reader. |
| [getSignature()](#getSignature--) | Gets the resource signature. |
| [getSize()](#getSize--) | Gets the resource block size in bytes including its data. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [getWriterName()](#getWriterName--) | Gets or sets the name of the writer. |
| [hasRealMergedData()](#hasRealMergedData--) | Gets or sets a value indicating whether this instance has real merged data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | Saves the resource block to the specified stream. |
| [setFileVersion(long value)](#setFileVersion-long-) | Gets or sets the file version. |
| [setID(short value)](#setID-short-) | Gets or sets the unique identifier for the resource. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | Gets or sets the layer and mask information. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the resource name. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | Gets or sets the name of the reader. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | Gets or sets a value indicating whether this instance has real merged data. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | Gets or sets the resource block state. |
| [setVersion(long value)](#setVersion-long-) | Gets or sets the version. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | Gets or sets the name of the writer. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | Validates the resource values. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


Initializes a new instance of the [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) class.

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
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


Gets or sets the file version.

Value: The file version.

**Returns:**
long
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
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


Gets or sets the name of the reader.

Value: The name of the reader.

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
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Gets or sets the version.

Value: The version.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


Gets or sets the name of the writer.

Value: The name of the writer.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


Gets or sets a value indicating whether this instance has real merged data.

Value:  true  if this instance has real merged data; otherwise,  false .

**Returns:**
boolean
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

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


Gets or sets the file version.

Value: The file version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

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

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


Gets or sets the name of the reader.

Value: The name of the reader.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


Gets or sets a value indicating whether this instance has real merged data.

Value:  true  if this instance has real merged data; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


Gets or sets the version.

Value: The version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


Gets or sets the name of the writer.

Value: The name of the writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

