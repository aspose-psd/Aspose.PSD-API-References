---
title: "ChannelInformation"
second_title: "Aspose.PSD 的 Java API 参考"
description: "通道信息。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

通道信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | 用户（光栅）遮罩通道 ID。 |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | 短（光栅或矢量）遮罩通道 ID。 |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Alpha 通道 ID |
## Methods

| Method | 描述 |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 它压缩通道数据 |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | 克隆指定的通道信息。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | 获取通道位深度。 |
| [getChannelID()](#getChannelID--) | 获取或设置通道 ID。 |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | 获取或设置压缩方法。 |
| [getData_internalized()](#getData-internalized--) | 获取或设置通道数据。 |
| [getLength()](#getLength--) | 获取通道的字节长度。 |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | 获取 PSD 的版本 |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | 获取未压缩的数据。 |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | 获取通道是否为 ShortMask |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | 保存通道数据。 |
| [setChannelID(short value)](#setChannelID-short-) | 获取或设置通道 ID。 |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | 设置压缩数据。 |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | 获取或设置压缩方法。 |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | 设置压缩数据。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


用户（光栅）遮罩通道 ID。（如果图层同时具有矢量和光栅遮罩）。

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


短（光栅或矢量）遮罩通道 ID。（如果图层仅有一个矢量或光栅遮罩，而不是两者）。

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Alpha 通道 ID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


它压缩通道数据

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawData | byte[] | 用于压缩的原始数据 |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 图层的边界 |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | 图层遮罩的边界 |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| 宽度 | int |  |
| 高度 | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


克隆指定的通道信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 信息。 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - 克隆的图层遮罩。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


获取通道位深度。

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


获取或设置通道 ID。

值：通道 ID。

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


获取或设置压缩方法。

值：压缩方法。

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


获取或设置通道数据。

值：通道数据。

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


获取通道的字节长度。

值：长度。

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


获取 PSD 的版本

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


获取未压缩的数据。

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


获取通道是否为 ShortMask

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


保存通道数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |
| is32BitColor | boolean | 如果颜色为 32 位模式则为 true |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


获取或设置通道 ID。

值：通道 ID。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


设置压缩数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| compressedData | byte[] | 压缩数据。 |
| channelWidth | int | 通道的宽度。 |
| channelHeight | int | 通道的高度。 |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


获取或设置压缩方法。

值：压缩方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


设置压缩数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawData | byte[] | 原始数据。 |
| imageSize | [Size](../../com.aspose.psd/size) | 图像的大小 |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | 当前 channelData 的边界。如果图像很大，它将在处理时被划分，且 currentBounds != imageBounds。 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

