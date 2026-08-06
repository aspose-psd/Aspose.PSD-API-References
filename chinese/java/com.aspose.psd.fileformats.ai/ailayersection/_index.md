---
title: "AiLayerSection"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Ai 格式图层段"
type: docs
weight: 15
url: /zh/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai 格式图层段
## Methods

| Method | 描述 |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | 添加光栅图像。 |
| [close()](#close--) | 实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。 |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | 释放当前实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | 获取或设置蓝色分量。 |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | 获取或设置颜色的索引。 |
| [getColorNumber()](#getColorNumber--) | 获取或设置颜色编号。 |
| [getData()](#getData--) | 获取字符串数据。 |
| [getDimValue()](#getDimValue--) | 获取或设置暗淡值（百分比）。 |
| [getDisposed()](#getDisposed--) | 获取指示此实例是否已释放的值。 |
| [getGreen()](#getGreen--) | 获取或设置绿色分量。 |
| [getName()](#getName--) | 获取或设置图层名称。 |
| [getRasterImages()](#getRasterImages--) | 获取光栅图像。 |
| [getRed()](#getRed--) | 获取或设置红色分量。 |
| [getStream_internalized()](#getStream-internalized--) | 获取内部流 |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | 获取或设置一个值，指示此实例是否具有多层蒙版。 |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | 获取或设置一个值，指示此图层是否已暗淡。 |
| [isLocked()](#isLocked--) | 获取或设置一个值，指示此图层是否已锁定。 |
| [isPreview()](#isPreview--) | 获取或设置一个值，指示此图层是否为预览。 |
| [isPrinted()](#isPrinted--) | 获取或设置一个值，指示此图层是否已打印。 |
| [isShown()](#isShown--) | 获取或设置一个值，指示此图层是否可见。 |
| [isTemplate()](#isTemplate--) | 获取或设置一个值，指示此图层是否为模板图层。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | 获取或设置蓝色分量。 |
| [setColorIndex(int value)](#setColorIndex-int-) | 获取或设置颜色的索引。 |
| [setColorNumber(int value)](#setColorNumber-int-) | 获取或设置颜色编号。 |
| [setDimValue(int value)](#setDimValue-int-) | 获取或设置暗淡值（百分比）。 |
| [setGreen(int value)](#setGreen-int-) | 获取或设置绿色分量。 |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | 获取或设置一个值，指示此图层是否已暗淡。 |
| [setLocked(boolean value)](#setLocked-boolean-) | 获取或设置一个值，指示此图层是否已锁定。 |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | 获取或设置一个值，指示此实例是否具有多层蒙版。 |
| [setName(String value)](#setName-java.lang.String-) | 获取或设置图层名称。 |
| [setPreview(boolean value)](#setPreview-boolean-) | 获取或设置一个值，指示此图层是否为预览。 |
| [setPrinted(boolean value)](#setPrinted-boolean-) | 获取或设置一个值，指示此图层是否已打印。 |
| [setRed(int value)](#setRed-int-) | 获取或设置红色分量。 |
| [setShown(boolean value)](#setShown-boolean-) | 获取或设置一个值，指示此图层是否可见。 |
| [setTemplate(boolean value)](#setTemplate-boolean-) | 获取或设置一个值，指示此图层是否为模板图层。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


添加光栅图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | 光栅图像。 |

### close() {#close--}
```
public void close()
```


实现 Closable 接口，并自 JDK 1.7 起可在 try-with-resources 语句中使用。此方法仅调用 dispose 方法。

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |
| 属性 | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


释放当前实例。

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


获取或设置蓝色分量。

值：蓝色分量。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


获取或设置颜色的索引。此参数的取值范围为 \u20131 到 26。每个整数代表一种颜色，可分配给图层用于用户识别目的。

值：颜色的索引。

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


获取或设置颜色编号。-1 表示来自红色、绿色、蓝色属性的自定义颜色值。指定图层\u2019的颜色设置。

值：颜色编号。

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


获取字符串数据。

**Returns:**
java.lang.String - 部分的字符串数据
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


获取或设置暗淡值（百分比）。将图层中包含的链接图像和位图图像的强度降低到指定的百分比。

值：暗淡值（百分比）。

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


获取指示此实例是否已释放的值。

**Returns:**
boolean -  true  如果已释放；否则，  false 。
### getGreen() {#getGreen--}
```
public final int getGreen()
```


获取或设置绿色分量。

值：绿色分量。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取或设置图层名称。指定该项目在“图层”面板中显示的名称。

值：图层名称。

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


获取光栅图像。

值：光栅图像。

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


获取或设置红色分量。

值：红色分量。

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


获取内部流

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


获取或设置一个值，指示此实例是否具有多层蒙版。

值： true 如果此实例具有多层蒙版；否则， false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


获取或设置一个值，指示此图层是否已调暗。降低图层中链接图像和位图图像的强度。

值： true 如果此图层已调暗；否则， false。

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取或设置一个值，指示此图层是否已锁定。防止对该项目的更改。

值： true 如果此图层已锁定；否则， false。

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


获取或设置一个值，指示此图层是否为预览。以彩色而非轮廓显示图层中包含的艺术作品。

值： true 如果此图层为预览；否则， false。

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


获取或设置一个值，指示此图层是否已打印。如果为 true，则使图层中包含的艺术作品可打印。

值： true 如果此图层已打印；否则， false。

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


获取或设置一个值，指示此图层是否已显示。如果为 true，则在画板上显示图层中包含的所有艺术作品。

值： true 如果此图层已显示；否则， false。

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


获取或设置一个值，指示此图层是否为模板图层。

值： true 如果此图层是模板；否则， false。

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


获取或设置蓝色分量。

值：蓝色分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


获取或设置颜色的索引。此参数的取值范围为 \u20131 到 26。每个整数代表一种颜色，可分配给图层用于用户识别目的。

值：颜色的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


获取或设置颜色编号。-1 表示来自红色、绿色、蓝色属性的自定义颜色值。指定图层\u2019的颜色设置。

值：颜色编号。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


获取或设置暗淡值（百分比）。将图层中包含的链接图像和位图图像的强度降低到指定的百分比。

值：暗淡值（百分比）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


获取或设置绿色分量。

值：绿色分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


获取或设置一个值，指示此图层是否已调暗。降低图层中链接图像和位图图像的强度。

值： true 如果此图层已调暗；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


获取或设置一个值，指示此图层是否已锁定。防止对该项目的更改。

值： true 如果此图层已锁定；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


获取或设置一个值，指示此实例是否具有多层蒙版。

值： true 如果此实例具有多层蒙版；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置图层名称。指定该项目在“图层”面板中显示的名称。

值：图层名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


获取或设置一个值，指示此图层是否为预览。以彩色而非轮廓显示图层中包含的艺术作品。

值： true 如果此图层为预览；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


获取或设置一个值，指示此图层是否已打印。如果为 true，则使图层中包含的艺术作品可打印。

值： true 如果此图层已打印；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


获取或设置红色分量。

值：红色分量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


获取或设置一个值，指示此图层是否已显示。如果为 true，则在画板上显示图层中包含的所有艺术作品。

值： true 如果此图层已显示；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


获取或设置一个值，指示此图层是否为模板图层。

值： true 如果此图层是模板；否则， false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

