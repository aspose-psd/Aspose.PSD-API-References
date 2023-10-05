---
title: VectorPathData
second_title: Aspose.PSD for Java API Reference
description: The class to work with a vector path.
type: docs
weight: 18
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

The class to work with a vector path.
## Constructors

| Constructor | Description |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Initializes a new instance of the [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) class. |
| [VectorPathData()](#VectorPathData--) | Initializes a new instance of the [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) class. |
## Fields

| Field | Description |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | The size of the general information like version and flags. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Gets as byte array. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Gets the vector path data length in the resource as bytes. |
| [getPaths()](#getPaths--) | Gets or sets the path records. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Gets or sets a value indicating whether this instance is disabled. |
| [isInverted()](#isInverted--) | Gets or sets a value indicating whether this instance is inverted. |
| [isNotLinked()](#isNotLinked--) | Gets or sets a value indicating whether this instance is not linked. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Gets or sets a value indicating whether this instance is disabled. |
| [setInverted(boolean value)](#setInverted-boolean-) | Gets or sets a value indicating whether this instance is inverted. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Gets or sets a value indicating whether this instance is not linked. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Gets or sets the path records. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Initializes a new instance of the [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The resource data. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Initializes a new instance of the [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) class.

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


The size of the general information like version and flags.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Gets as byte array.

**Returns:**
byte[] - The resource as byte array.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Gets the vector path data length in the resource as bytes.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Gets or sets the path records.

Value: The paths.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
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

