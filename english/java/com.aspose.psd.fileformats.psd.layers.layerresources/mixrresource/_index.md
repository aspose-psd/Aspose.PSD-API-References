---
title: MixrResource
second_title: Aspose.PSD for Java API Reference
description: Class MixrResource.
type: docs
weight: 53
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public final class MixrResource extends AdjustmentLayerResource
```

Class MixrResource. Resource of Channel Mixer Adjustment Layer
## Constructors

| Constructor | Description |
| --- | --- |
| [MixrResource()](#MixrResource--) | Initializes a new instance of the [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) class. |
| [MixrResource(byte[] data)](#MixrResource-byte---) | Initializes a new instance of the [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) class. |
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
| [getChannelInfo(int channelIndex)](#getChannelInfo-int-) | Gets the channel information raw data |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Gets or sets the data. |
| [getHeader_internalized()](#getHeader-internalized--) | Gets or sets the header. |
| [getKey()](#getKey--) | Gets the layer resource key. |
| [getLength()](#getLength--) | Gets the layer resource length in bytes. |
| [getMonochrome()](#getMonochrome--) | Gets or sets a value indicating whether this [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) is monochrome. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Gets the prefix length. |
| [getPsdVersion()](#getPsdVersion--) | Gets the psd version. |
| [getSignature()](#getSignature--) | Gets the signature. |
| [getVersion()](#getVersion--) | Gets or sets the version. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Determines whether the resource is PSB specific. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Gets a value indicating whether this instance is resource PSB specific. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Saves the resource to the specified stream container. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Saves the custom resource header. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Saves the header signature, identifier and length. |
| [setChannelInfo(int channelIndex, byte[] value)](#setChannelInfo-int-byte---) | Sets the channel information. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Gets or sets the header. |
| [setMonochrome(boolean value)](#setMonochrome-boolean-) | Gets or sets a value indicating whether this [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) is monochrome. |
| [setVersion(short value)](#setVersion-short-) | Gets or sets the version. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MixrResource() {#MixrResource--}
```
public MixrResource()
```


Initializes a new instance of the [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) class. PSD format specification contains following description: 2 Version ( = 1) 2 Monochrome 20 RGB or CMYK color plus constant for the mixer settings. 4 \* 2 bytes of color with 2 bytes of constant.

### MixrResource(byte[] data) {#MixrResource-byte---}
```
public MixrResource(byte[] data)
```


Initializes a new instance of the [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) class. PSD format specification contains following description: 2 Version ( = 1) 2 Monochrome 20 RGB or CMYK color plus constant for the mixer settings. 4 \* 2 bytes of color with 2 bytes of constant.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The data of the resource. |

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
### getChannelInfo(int channelIndex) {#getChannelInfo-int-}
```
public final byte[] getChannelInfo(int channelIndex)
```


Gets the channel information raw data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |

**Returns:**
byte[] - Raw byte array of channel info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public final byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
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
### getMonochrome() {#getMonochrome--}
```
public final boolean getMonochrome()
```


Gets or sets a value indicating whether this [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) is monochrome.

Value:  true  if monochrome; otherwise,  false .

**Returns:**
boolean
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
public final short getVersion()
```


Gets or sets the version.

Value: The version. Default value is 1

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setChannelInfo(int channelIndex, byte[] value) {#setChannelInfo-int-byte---}
```
public final void setChannelInfo(int channelIndex, byte[] value)
```


Sets the channel information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| channelIndex | int | Index of the channel. |
| value | byte[] | The value. |

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

### setMonochrome(boolean value) {#setMonochrome-boolean-}
```
public final void setMonochrome(boolean value)
```


Gets or sets a value indicating whether this [MixrResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/mixrresource) is monochrome.

Value:  true  if monochrome; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Gets or sets the version.

Value: The version. Default value is 1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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

