---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义 LayerMaskDataFull 类，该类包含在 PSD 文件图层中当图层同时具有图层蒙版和矢量蒙版时的蒙版数据信息。"
type: docs
weight: 22
url: /zh/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

定义 LayerMaskDataFull 类，该类包含 PSD 文件图层中掩码数据的信息，当图层同时具有图层掩码和矢量掩码时。否则，使用 [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort)。ImageData 包含光栅掩码和光栅化的矢量掩码的组合。ImageData 字节长度应等于 MaskRectangle.Width \* MaskRectangle.Height 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | 初始化 [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | 克隆此实例。 |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | 克隆图层蒙版。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取或设置背景颜色。 |
| [getBottom()](#getBottom--) | 获取或设置底部图层蒙版位置。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 获取图层蒙版数据的大小。 |
| [getDefaultColor()](#getDefaultColor--) | 获取或设置默认颜色。 |
| [getEnclosingBottom()](#getEnclosingBottom--) | 获取或设置 PSD 图像图层中封闭的底部光栅掩码位置。 |
| [getEnclosingLeft()](#getEnclosingLeft--) | 获取或设置 PSD 文件图层中封闭的左侧光栅掩码位置。 |
| [getEnclosingRight()](#getEnclosingRight--) | 获取或设置 PSD 文件图层中封闭的右侧光栅掩码位置。 |
| [getEnclosingTop()](#getEnclosingTop--) | 获取或设置 PSD 图像图层中封闭的光栅掩码顶部位置。 |
| [getFlags()](#getFlags--) | 获取或设置图层蒙版标志。 |
| [getHeight_internalized()](#getHeight-internalized--) | 获取蒙版高度。 |
| [getImageData()](#getImageData--) | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [getLeft()](#getLeft--) | 获取或设置左侧图层蒙版位置。 |
| [getMaskRectangle()](#getMaskRectangle--) | 获取或设置 PSD 文件中图层蒙版的蒙版矩形。 |
| [getRealFlags()](#getRealFlags--) | 获取或设置用于用户/光栅掩码的图层掩码标志。 |
| [getRight()](#getRight--) | 获取或设置右侧图层蒙版位置。 |
| [getTop()](#getTop--) | 获取或设置顶部图层蒙版位置。 |
| [getUserMaskData()](#getUserMaskData--) | 获取或设置 PSD 文件中图层的用户（光栅）掩码数据。 |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | 获取或设置 PSD 图像图层中的用户掩码（包围）矩形。 |
| [getWidth_internalized()](#getWidth-internalized--) | 获取蒙版宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 将 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) 保存到指定的 StreamContainer。 |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | 获取或设置背景颜色。 |
| [setBottom(int value)](#setBottom-int-) | 获取或设置底部图层蒙版位置。 |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | 获取或设置默认颜色。 |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | 获取或设置 PSD 图像图层中封闭的底部光栅掩码位置。 |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | 获取或设置 PSD 文件图层中封闭的左侧光栅掩码位置。 |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | 获取或设置 PSD 文件图层中封闭的右侧光栅掩码位置。 |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | 获取或设置 PSD 图像图层中封闭的光栅掩码顶部位置。 |
| [setFlags(byte value)](#setFlags-byte-) | 获取或设置图层蒙版标志。 |
| [setImageData(byte[] value)](#setImageData-byte---) | 获取或设置 PSD 文件中图层蒙版数据（如果存在矢量蒙版，则为组合/最终蒙版）。 |
| [setLeft(int value)](#setLeft-int-) | 获取或设置左侧图层蒙版位置。 |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | 获取或设置 PSD 文件中图层蒙版的蒙版矩形。 |
| [setRealFlags(byte value)](#setRealFlags-byte-) | 获取或设置用于用户/光栅掩码的图层掩码标志。 |
| [setRight(int value)](#setRight-int-) | 获取或设置右侧图层蒙版位置。 |
| [setTop(int value)](#setTop-int-) | 获取或设置顶部图层蒙版位置。 |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | 获取或设置 PSD 文件中图层的用户（光栅）掩码数据。 |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | 获取或设置 PSD 图像图层中的用户掩码（包围）矩形。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


初始化 [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) 类的新实例。

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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


获取或设置背景颜色。

值：背景颜色。

**Returns:**
byte
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
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


获取或设置 PSD 图像图层中封闭的底部光栅掩码位置。

值：底部图层蒙版位置。

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


获取或设置 PSD 文件图层中封闭的左侧光栅掩码位置。

Value: 左侧图层蒙版位置。

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


获取或设置 PSD 文件图层中封闭的右侧光栅掩码位置。

Value: 右侧图层蒙版位置。

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


获取或设置 PSD 图像图层中封闭的光栅掩码顶部位置。

Value: 顶部图层蒙版位置。

**Returns:**
int
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
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


获取或设置用于用户/光栅掩码的图层掩码标志。对于矢量掩码，使用 Flags 属性。

值：真实的图层掩码标志。

**Returns:**
byte
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
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


获取或设置 PSD 文件中图层的用户（光栅）掩码数据。（MaskData 属性中有一个光栅化的矢量掩码）。

值：PSD 图像中的图层图像数据。

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


获取或设置 PSD 图像图层中的用户掩码（包围）矩形。

值：用户掩码矩形。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
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
public void save_internalized(StreamContainer streamContainer)
```


将 [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) 保存到指定的 StreamContainer。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于保存数据的流容器。 |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


获取或设置背景颜色。

值：背景颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

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

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


获取或设置 PSD 图像图层中封闭的底部光栅掩码位置。

值：底部图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


获取或设置 PSD 文件图层中封闭的左侧光栅掩码位置。

Value: 左侧图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


获取或设置 PSD 文件图层中封闭的右侧光栅掩码位置。

Value: 右侧图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


获取或设置 PSD 图像图层中封闭的光栅掩码顶部位置。

Value: 顶部图层蒙版位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


获取或设置用于用户/光栅掩码的图层掩码标志。对于矢量掩码，使用 Flags 属性。

值：真实的图层掩码标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

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

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


获取或设置 PSD 文件中图层的用户（光栅）掩码数据。（MaskData 属性中有一个光栅化的矢量掩码）。

值：PSD 图像中的图层图像数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


获取或设置 PSD 图像图层中的用户掩码（包围）矩形。

值：用户掩码矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

