---
title: "ThumbnailResource"
second_title: "Aspose.PSD 的 Java API 参考"
description: "缩略图资源块。"
type: docs
weight: 36
url: /zh/java/com.aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public class ThumbnailResource extends ResourceBlock
```

缩略图资源块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ThumbnailResource()](#ThumbnailResource--) | 初始化 [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady 的资源签名。 |
| [ResouceBlockSignature](#ResouceBlockSignature) | 常规 Photoshop 资源签名。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | 获取或设置位像素。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 获取资源数据大小（字节）。 |
| [getFormat()](#getFormat--) | 获取或设置缩略图数据格式。 |
| [getHeight()](#getHeight--) | 获取或设置缩略图的高度（像素）。 |
| [getID()](#getID--) | 获取或设置资源的唯一标识符。 |
| [getJpegOptions()](#getJpegOptions--) | 获取或设置 JPEG 选项。 |
| [getMinimalVersion()](#getMinimalVersion--) | 获取所需的最低 PSD 版本。 |
| [getName()](#getName--) | 获取或设置资源名称。 |
| [getPlanesCount()](#getPlanesCount--) | 获取或设置平面计数。 |
| [getSignature()](#getSignature--) | 获取资源签名。 |
| [getSize()](#getSize--) | 获取资源块的大小（字节），包括其数据。 |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | 获取或设置压缩后的大小。 |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | 获取或设置 32 位 ARGB 缩略图数据。 |
| [getThumbnailData()](#getThumbnailData--) | 获取或设置缩略图数据。 |
| [getTotalSize()](#getTotalSize--) | 获取总数据大小。 |
| [getWidth()](#getWidth--) | 获取或设置缩略图的宽度（像素）。 |
| [getWidthBytes()](#getWidthBytes--) | 获取行宽（字节）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 将资源块保存到指定的流中。 |
| [setBitsPixel(short value)](#setBitsPixel-short-) | 获取或设置位像素。 |
| [setFormat(int value)](#setFormat-int-) | 获取或设置缩略图数据格式。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置缩略图的高度（像素）。 |
| [setID(short value)](#setID-short-) | 获取或设置资源的唯一标识符。 |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | 获取或设置 JPEG 选项。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 获取或设置图层和蒙版信息。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置资源名称。 |
| [setPlanesCount(short value)](#setPlanesCount-short-) | 获取或设置平面计数。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 获取或设置资源块状态。 |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | 获取或设置 32 位 ARGB 缩略图数据。 |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | 获取或设置缩略图数据。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置缩略图的宽度（像素）。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 验证资源值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ThumbnailResource() {#ThumbnailResource--}
```
public ThumbnailResource()
```


初始化 [ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource) 类的新实例。

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady 的资源签名。

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


常规 Photoshop 资源签名。

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


获取或设置位像素。

值：缩略图位像素。

**Returns:**
short
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


获取资源数据大小（字节）。

值：资源数据大小。

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


获取或设置缩略图数据格式。

值：缩略图数据格式。

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取或设置缩略图的高度（像素）。

值：缩略图高度。

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


获取或设置资源的唯一标识符。

值：资源的唯一标识符。

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


获取或设置 JPEG 选项。仅在缩略图资源保存为 JPEG 文件格式时适用。当定义为 RAW 格式时此选项无效。

值：JPEG 选项。

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


获取所需的最低 PSD 版本。

值：最小的 psd 版本。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。

值：资源名称。

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


获取或设置平面计数。

值：缩略图平面计数。

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


获取资源签名。应始终为 '8BIM'。

值：资源签名。

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


获取资源块的大小（字节），包括其数据。

值：资源块大小。

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


获取或设置压缩后的大小。用于一致性检查。

值：压缩后的大小。

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


获取或设置 32 位 ARGB 缩略图数据。

值：32 位 ARGB 缩略图数据。

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


获取或设置缩略图数据。

值：缩略图数据。

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


获取总数据大小。

Value: 总数据大小。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取或设置缩略图的宽度（像素）。

Value: 缩略图宽度。

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


获取行宽（字节）。

Value: 行宽（字节）。

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


将资源块保存到指定的流中。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于保存资源块的流。 |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


获取或设置位像素。

值：缩略图位像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


获取或设置缩略图数据格式。

值：缩略图数据格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


获取或设置缩略图的高度（像素）。

值：缩略图高度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


获取或设置资源的唯一标识符。

值：资源的唯一标识符。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


获取或设置 JPEG 选项。仅在缩略图资源保存为 JPEG 文件格式时适用。当定义为 RAW 格式时此选项无效。

值：JPEG 选项。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


获取或设置图层和蒙版信息。

值：图层和蒙版信息。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。

值：资源名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


获取或设置平面计数。

值：缩略图平面计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 签名 | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


获取或设置资源块状态。

值：资源块状态。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


获取或设置 32 位 ARGB 缩略图数据。

值：32 位 ARGB 缩略图数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


获取或设置缩略图数据。

值：缩略图数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


获取或设置缩略图的宽度（像素）。

Value: 缩略图宽度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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


验证资源值。

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

