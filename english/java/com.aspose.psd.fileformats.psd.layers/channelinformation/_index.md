---
title: ChannelInformation
second_title: Aspose.PSD for Java API Reference
description: The channel information.
type: docs
weight: 12
url: /java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

The channel information.
## Constructors

| Constructor | Description |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Clones the specified channel information. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelID()](#getChannelID--) | Gets or sets the channel ID. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Gets or sets the compression method. |
| [getData_internalized()](#getData-internalized--) | Gets or sets the channel data. |
| [getLength()](#getLength--) | Gets the channel length in bytes. |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Gets the uncompressed data. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Saves the channel data. |
| [setChannelID(short value)](#setChannelID-short-) | Gets or sets the channel ID. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Sets the compressed data. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Gets or sets the compression method. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| width | int |  |
| height | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Clones the specified channel information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | The information. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - The cloned layer mask.
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
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Gets or sets the channel ID.

Value: The channel ID.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Gets or sets the compression method.

Value: The compression method.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Gets or sets the channel data.

Value: The channel data.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final int getLength()
```


Gets the channel length in bytes.

Value: The length.

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Gets the uncompressed data.

**Returns:**
byte[] - 
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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Saves the channel data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to save to. |
| is32BitColor | boolean | true if the color is in 32-bit mode |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Gets or sets the channel ID.

Value: The channel ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Sets the compressed data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressedData | byte[] | The compressed data. |
| channelWidth | int | Width of the channel. |
| channelHeight | int | Height of the channel. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Gets or sets the compression method.

Value: The compression method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

