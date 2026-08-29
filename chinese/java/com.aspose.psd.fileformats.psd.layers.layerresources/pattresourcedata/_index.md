---
title: "PattResourceData"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于存储资源的模式数据的类。"
type: docs
weight: 67
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

用于存储 [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) 资源的模式数据的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | 初始化 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | 返回从模式的通道获取的压缩方法代码。 |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | 创建默认的模式数据。 |
| [getHeight()](#getHeight--) | 获取高度。 |
| [getImageMode()](#getImageMode--) | 获取图像模式。 |
| [getLength()](#getLength--) | 获取模式的长度。 |
| [getName()](#getName--) | 获取或设置名称。 |
| [getPatternData()](#getPatternData--) | 获取图案数据。 |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | 内存数组列表。 |
| [getPatternId()](#getPatternId--) | 获取或设置图案标识符。 |
| [getVersion()](#getVersion--) | 获取版本。 |
| [getWidth()](#getWidth--) | 获取宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | 保存模式数据。 |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | 获取高度。 |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | 获取图像模式。 |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | 获取或设置索引颜色表。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置名称。 |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | 设置模式像素缓冲区和目标尺寸，更新宽度（[.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)）/高度（[.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)），并使用默认压缩模式 (0) 存储用于保存的数据。 |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | 内存数组列表。 |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | 获取或设置图案标识符。 |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | 设置模式像素缓冲区和目标尺寸，更新宽度（[.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)）/高度（[.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)），并使用指定的压缩模式存储用于保存的数据。 |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | 获取版本。 |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | 获取宽度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


初始化 [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) 类的新实例。

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


返回从模式的通道获取的压缩方法代码。

**Returns:**
byte - 压缩代码：0 — 原始/未压缩；>= 1 — zip。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


创建默认的模式数据。

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


获取高度。

Value: 高度。

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


获取图像模式。

值：图像模式。

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


获取模式的长度。

值：模式的长度。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取或设置名称。

值：名称。

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


获取图案数据。

值：图案数据。

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


内存数组列表。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


获取或设置图案标识符。

值：图案标识符。

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


获取版本。

值：版本。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


获取宽度。

Value: 宽度。

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


保存模式数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 要保存到的流容器。 |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


获取高度。

Value: 高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


获取图像模式。

值：图像模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


获取或设置索引颜色表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置名称。

值：名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


设置模式像素缓冲区和目标尺寸，更新宽度（[.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)）/高度（[.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)），并使用默认压缩模式 (0) 存储用于保存的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 像素 | int[] | 32 位像素，采用 0xAARRGGBB 格式。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 模式的像素边界。 |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


内存数组列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


获取或设置图案标识符。

值：图案标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


设置模式像素缓冲区和目标尺寸，更新宽度（[.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)）/高度（[.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)），并使用指定的压缩模式存储用于保存的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 像素 | int[] | 32 位像素，采用 0xAARRGGBB 格式。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | 模式的像素边界。 |
| compressionMode | byte | 用于在保存 PSD 文件时定义图案数据压缩的压缩模式。 |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


获取版本。

值：版本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


获取宽度。

Value: 宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

