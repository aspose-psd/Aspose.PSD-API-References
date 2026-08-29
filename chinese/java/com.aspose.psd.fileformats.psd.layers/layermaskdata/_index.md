---
title: "LayerMaskData"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义了基类 LayerMaskData，包含 PSD 文件中图层蒙版数据的信息。"
type: docs
weight: 21
url: /zh/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

定义了基类 LayerMaskData，包含 PSD 文件中图层蒙版数据的信息。它可以帮助以编程方式修改 Adobe\\ufffd Photoshop\\ufffd 文件并自动化 PSD 格式编辑。如果图层仅有光栅蒙版，ImageData 包含光栅蒙版的数据字节。如果图层仅有矢量蒙版，ImageData 包含矢量蒙版栅格化（缓存）的数据字节。如果图层同时拥有光栅蒙版和矢量蒙版，ImageData 包含光栅蒙版和栅格化矢量蒙版的组合。ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) 的字节长度应等于 MaskRectangle ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) 属性中的宽度 * 高度。请注意，仅删除/添加/更新 LayerMaskData 并不足以正确保存，因为通道未更新；尽管可能提供正确的渲染。应使用 [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) 方法来完成此操作。
## Methods

| Method | 描述 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 克隆图层蒙版。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | 获取或设置底部图层蒙版位置。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 获取图层蒙版数据的大小。 |
| [getDefaultColor()](#getDefaultColor--) | 获取或设置默认颜色。 |
| [getFlags()](#getFlags--) | 获取或设置图层蒙版标志。 |
| [getHeight_internalized()](#getHeight-internalized--) | 获取蒙版高度。 |
| [getImageData()](#getImageData--) | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [getLeft()](#getLeft--) | 获取或设置左侧图层蒙版位置。 |
| [getMaskRectangle()](#getMaskRectangle--) | 获取或设置 PSD 文件中图层蒙版的蒙版矩形。 |
| [getRight()](#getRight--) | 获取或设置右侧图层蒙版位置。 |
| [getTop()](#getTop--) | 获取或设置顶部图层蒙版位置。 |
| [getWidth_internalized()](#getWidth-internalized--) | 获取蒙版宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 将 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) 保存到指定的 StreamContainer。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底部图层蒙版位置。 |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | 获取或设置默认颜色。 |
| [setFlags(byte value)](#setFlags-byte-) | 获取或设置图层蒙版标志。 |
| [setImageData(byte[] value)](#setImageData-byte---) | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置左侧图层蒙版位置。 |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | 获取或设置 PSD 文件中图层蒙版的蒙版矩形。 |
| [setRight(int value)](#setRight-int-) | 获取或设置右侧图层蒙版位置。 |
| [setTop(int value)](#setTop-int-) | 获取或设置顶部图层蒙版位置。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


克隆此实例。

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


克隆图层蒙版。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | 蒙版。 |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


获取或设置底部图层蒙版位置。

值：底部图层蒙版位置。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


获取图层蒙版数据的大小。

Value: 图层蒙版掩码数据的大小。

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


获取或设置默认颜色。

Value: 默认颜色。

**Returns:**
byte
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


获取或设置图层蒙版标志。

Value: 图层蒙版标志。

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


获取蒙版高度。

Value: 高度。

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。

Value: 图像数据。

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


获取或设置左侧图层蒙版位置。

Value: 左侧图层蒙版位置。

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


获取或设置 PSD 文件中图层蒙版的 mask Rectangle。它接受 left、right、top 和 bottom 属性并创建 Rectangle。

Value: 蒙版矩形。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRight() {#getRight--}
```
public final int getRight()
```


获取或设置右侧图层蒙版位置。

Value: 右侧图层蒙版位置。

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


获取或设置顶部图层蒙版位置。

Value: 顶部图层蒙版位置。

**Returns:**
int
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


获取蒙版宽度。

Value: 宽度。

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public abstract void save_internalized(StreamContainer streamContainer)
```


将 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) 保存到指定的 StreamContainer。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于保存数据的流容器。 |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


获取或设置底部图层蒙版位置。

值：底部图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


获取或设置默认颜色。

Value: 默认颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


获取或设置图层蒙版标志。

Value: 图层蒙版标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。

Value: 图像数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


获取或设置左侧图层蒙版位置。

Value: 左侧图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


获取或设置 PSD 文件中图层蒙版的 mask Rectangle。它接受 left、right、top 和 bottom 属性并创建 Rectangle。

Value: 蒙版矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


获取或设置右侧图层蒙版位置。

Value: 右侧图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


获取或设置顶部图层蒙版位置。

Value: 顶部图层蒙版位置。

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

