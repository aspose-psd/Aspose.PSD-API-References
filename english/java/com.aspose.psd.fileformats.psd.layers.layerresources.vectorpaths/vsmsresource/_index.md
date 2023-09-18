---
title: VsmsResource
second_title: Aspose.PSD for Java API Reference
description: Class VsmsResource.
type: docs
weight: 29
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vsmsresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathDataResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdataresource)
```
public class VsmsResource extends VectorPathDataResource
```

Class VsmsResource. This resource contains information about vector layer mask
## Constructors

| Constructor | Description |
| --- | --- |
| [VsmsResource(byte[] data)](#VsmsResource-byte---) | Initializes a new instance of the [VsmsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vsmsresource) class. |
| [VsmsResource()](#VsmsResource--) | Initializes a new instance of the [VsmsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vsmsresource) class. |
## Fields

| Field | Description |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | The PSB header version |
| [PsbResourceSignature](#PsbResourceSignature) | The PSB-specific resource signature. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | The PSD header version |
| [ResourceSignature](#ResourceSignature) | The common resource signature. |
| [TypeToolKey](#TypeToolKey) | The type tool info key. |
## Methods

| Method | Description |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Checks the and set if resource is PSB specific. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getPaths()](#getPaths--) | Gets or sets the path records. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [hashCode()](#hashCode--) |  |
| [isChanged_internalized()](#isChanged-internalized--) | Determines whether this instance is changed. |
| [isDisabled()](#isDisabled--) | Gets or sets a value indicating whether this instance is disabled. |
| [isInverted()](#isInverted--) | Gets or sets a value indicating whether this instance is inverted. |
| [isNotLinked()](#isNotLinked--) | Gets or sets a value indicating whether this instance is not linked. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Gets or sets a value indicating whether this instance is disabled. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setInverted(boolean value)](#setInverted-boolean-) | Gets or sets a value indicating whether this instance is inverted. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Gets or sets a value indicating whether this instance is not linked. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Gets or sets the path records. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets the version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [updateDataToCurrent_internalized()](#updateDataToCurrent-internalized--) | Update cached original data to the current state |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VsmsResource(byte[] data) {#VsmsResource-byte---}
```
public VsmsResource(byte[] data)
```


Initializes a new instance of the [VsmsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vsmsresource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The resource data. |

### VsmsResource() {#VsmsResource--}
```
public VsmsResource()
```


Initializes a new instance of the [VsmsResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vsmsresource) class.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


The PSB header version

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


The PSB-specific resource signature.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


The PSD header version

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


The common resource signature.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


The type tool info key.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Checks the and set if resource is PSB specific. Some resources are not recognized for now, but we have full list of PSB specific resources which changes their behaviour on save. So we need to check this in UnknownResource at least

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The key. |

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
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Gets or sets the header.

Value: The header.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public int getKey()
```


Gets the layer resource key.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Gets the layer resource length in bytes.

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
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Gets the prefix length. Default value is 12 for 8BIM resources. and 16 for 8B64

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| psdVersion | int | The PSD version. |

**Returns:**
int - The Prefix Length.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Gets the psd version.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Gets the signature.

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
### isChanged_internalized() {#isChanged-internalized--}
```
public final boolean isChanged_internalized()
```


Determines whether this instance is changed.

**Returns:**
boolean -  true  if this instance is changed; otherwise,  false .
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
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Determines whether the resource is PSB specific.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | int | The resource key. |

**Returns:**
boolean -  true  if the resource is PSB specific; otherwise,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Gets a value indicating whether this instance is resource PSB specific.

Value:  true  if this instance is resource PSB specific; otherwise,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Saves the resource to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |
| psdVersion | int | The PSD version. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Saves the custom resource header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Saves the header signature, identifier and length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |
| signature | int | The signature. |
| isLengthLong | boolean | if set to  true  length is long. |

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

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Gets or sets the header.

Value: The header.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

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


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
### updateDataToCurrent_internalized() {#updateDataToCurrent-internalized--}
```
public final void updateDataToCurrent_internalized()
```


Update cached original data to the current state

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

