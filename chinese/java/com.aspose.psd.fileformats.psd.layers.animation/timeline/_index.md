---
title: "时间轴"
second_title: "Aspose.PSD 的 Java API 参考"
description: "时间线选项模型。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Inheritance:**
java.lang.Object
```
public final class Timeline
```

时间线选项模型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Timeline()](#Timeline--) | 初始化 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [applyTo_internalized(PsdImage psdImage)](#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-) | 将当前时间线值应用于输入的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAFSt()](#getAFSt--) | 获取或设置 AFSt 值。 |
| [getActiveFrameIndex()](#getActiveFrameIndex--) | 获取或设置活动帧索引。 |
| [getClass()](#getClass--) |  |
| [getFrame(int frameId)](#getFrame-int-) | 按 ID 获取帧。 |
| [getFrames()](#getFrames--) | 获取帧列表。 |
| [getFramesList()](#getFramesList--) | 获取帧列表。 |
| [getFsID()](#getFsID--) | 获取或设置 FsID 值。 |
| [getLoopesCount()](#getLoopesCount--) | 获取或设置循环计数。 |
| [getPsdImage()](#getPsdImage--) | 获取或设置此 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(System.IO.Stream outputStream, ImageOptionsBase options)](#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将 PsdImage 和 Timeline 数据保存到指定流中，使用指定格式。 |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | 根据保存选项，将 PsdImage 和 Timeline 数据保存到指定文件位置，使用指定格式。 |
| [setAFSt(int value)](#setAFSt-int-) | 获取或设置 AFSt 值。 |
| [setActiveFrameIndex_internalized(int value)](#setActiveFrameIndex-internalized-int-) | 获取或设置活动帧索引。 |
| [setFrames(Frame[] value)](#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---) | 获取帧列表。 |
| [setFsID(int value)](#setFsID-int-) | 获取或设置 FsID 值。 |
| [setLoopesCount(int value)](#setLoopesCount-int-) | 获取或设置循环计数。 |
| [setPsdImage(PsdImage value)](#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-) | 获取或设置此 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [switchActiveFrame(int targetActiveFrameIndex)](#switchActiveFrame-int-) | 将活动帧切换到目标帧。 |
| [toString()](#toString--) |  |
| [updateFrameFromPsdImage_internalized(int frameIndex)](#updateFrameFromPsdImage-internalized-int-) | 将当前时间线值应用于输入的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timeline() {#Timeline--}
```
public Timeline()
```


初始化 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 类的新实例。

### applyTo_internalized(PsdImage psdImage) {#applyTo-internalized-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void applyTo_internalized(PsdImage psdImage)
```


将当前时间线值应用于输入的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| psdImage | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | psd 图像。 |

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
### getAFSt() {#getAFSt--}
```
public int getAFSt()
```


获取或设置 AFSt 值。

**Returns:**
int
### getActiveFrameIndex() {#getActiveFrameIndex--}
```
public int getActiveFrameIndex()
```


获取或设置活动帧索引。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrame(int frameId) {#getFrame-int-}
```
public Frame getFrame(int frameId)
```


按 ID 获取帧。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| frameId | int | 帧 ID。 |

**Returns:**
[Frame](../../com.aspose.psd.fileformats.psd.layers.animation/frame) - Returns the frame item or NULL if not exists.
### getFrames() {#getFrames--}
```
public Frame[] getFrames()
```


获取帧列表。

**Returns:**
com.aspose.psd.fileformats.psd.layers.animation.Frame[]
### getFramesList() {#getFramesList--}
```
public System.Collections.Generic.List<Frame> getFramesList()
```


获取帧列表。

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.animation.Frame>
### getFsID() {#getFsID--}
```
public int getFsID()
```


获取或设置 FsID 值。

**Returns:**
int
### getLoopesCount() {#getLoopesCount--}
```
public int getLoopesCount()
```


获取或设置循环计数。

**Returns:**
int
### getPsdImage() {#getPsdImage--}
```
public PsdImage getPsdImage()
```


获取或设置此 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
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




### save(System.IO.Stream outputStream, ImageOptionsBase options) {#save-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-}
```
public void save(System.IO.Stream outputStream, ImageOptionsBase options)
```


根据保存选项，将 PsdImage 和 Timeline 数据保存到指定流中，使用指定格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| outputStream | com.aspose.ms.System.IO.Stream | 输出流。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


根据保存选项，将 PsdImage 和 Timeline 数据保存到指定文件位置，使用指定格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 选项。 |

### setAFSt(int value) {#setAFSt-int-}
```
public void setAFSt(int value)
```


获取或设置 AFSt 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setActiveFrameIndex_internalized(int value) {#setActiveFrameIndex-internalized-int-}
```
public void setActiveFrameIndex_internalized(int value)
```


获取或设置活动帧索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFrames(Frame[] value) {#setFrames-com.aspose.psd.fileformats.psd.layers.animation.Frame---}
```
public void setFrames(Frame[] value)
```


获取帧列表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Frame\[\]](../../com.aspose.psd.fileformats.psd.layers.animation/frame) |  |

### setFsID(int value) {#setFsID-int-}
```
public void setFsID(int value)
```


获取或设置 FsID 值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLoopesCount(int value) {#setLoopesCount-int-}
```
public void setLoopesCount(int value)
```


获取或设置循环计数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPsdImage(PsdImage value) {#setPsdImage-com.aspose.psd.fileformats.psd.PsdImage-}
```
public void setPsdImage(PsdImage value)
```


获取或设置此 [Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline) 的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) |  |

### switchActiveFrame(int targetActiveFrameIndex) {#switchActiveFrame-int-}
```
public void switchActiveFrame(int targetActiveFrameIndex)
```


将活动帧切换到目标帧。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| targetActiveFrameIndex | int | 目标帧索引。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFrameFromPsdImage_internalized(int frameIndex) {#updateFrameFromPsdImage-internalized-int-}
```
public void updateFrameFromPsdImage_internalized(int frameIndex)
```


将当前时间线值应用于输入的 PsdImage ([.getPsdImage](../../null/\#getPsdImage)/[.setPsdImage(PsdImage)](../../null/\#setPsdImage-PsdImage-))。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| frameIndex | int | 用于更新图层状态的帧索引。 |

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

