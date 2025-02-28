---
title: ChannelInformation
second_title: Aspose.PSD for Java API Reference
description: The channel information.
type: docs
weight: 13
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
## Fields

| Field | Description |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | The user (raster) mask channel Id. |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | The short (raster or vector) mask channel Id. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | The alpha channel Id |
## Methods

| Method | Description |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | It compresses channel data |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Clones the specified channel information. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Gets the channel bit depth. |
| [getChannelID()](#getChannelID--) | Gets or sets the channel ID. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Gets or sets the compression method. |
| [getData_internalized()](#getData-internalized--) | Gets or sets the channel data. |
| [getLength()](#getLength--) | Gets the channel length in bytes. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Gets the version of PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Gets the uncompressed data. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Gets channel is ShortMask or not |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Saves the channel data. |
| [setChannelID(short value)](#setChannelID-short-) | Gets or sets the channel ID. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Sets the compressed data. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Gets or sets the compression method. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Sets the compressed data. |
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

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


The user (raster) mask channel Id. (if a layer has both vector and raster mask).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


The short (raster or vector) mask channel Id. (if a layer has only one vector or raster mask but not both).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


The alpha channel Id

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


It compresses channel data

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawData | byte[] | The raw data for compress |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of layer |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of layer mask |

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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Gets the channel bit depth.

**Returns:**
int
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
public final long getLength()
```


Gets the channel length in bytes.

Value: The length.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Gets the version of PSD

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
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Gets channel is ShortMask or not

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

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Sets the compressed data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawData | byte[] | The raw data. |
| imageSize | [Size](../../com.aspose.psd/size) | The size of image |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | The bounds of current channelData. If image is big it will be divide on process and currentBounds != imageBounds |

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

