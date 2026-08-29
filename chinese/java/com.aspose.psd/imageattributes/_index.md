---
title: "ImageAttributes"
second_title: "Aspose.PSD 的 Java API 参考"
description: "一个 com.aspose.psd.ImageAttributes 对象包含有关在渲染过程中如何操作位图和元文件颜色的信息。"
type: docs
weight: 55
url: /zh/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

一个 com.aspose.psd.ImageAttributes 对象包含有关在渲染过程中如何操作位图和元文件颜色的信息。该 com.aspose.psd.ImageAttributes 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染期间，颜色可以被校正、加暗、增亮或移除。要应用这些操作，请初始化一个 com.aspose.psd.ImageAttributes 对象，并将该对象的路径（以及 [Image](../../com.aspose.psd/image) 的路径）传递给 drawImage 方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | 初始化 com.aspose.psd.ImageAttributes 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI 图像属性。 |
## Methods

| Method | 描述 |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | 清除此 com.aspose.psd.ImageAttributes 对象的画笔颜色重新映射表。 |
| [clearColorKey()](#clearColorKey--) | 清除默认类别的颜色键（透明度范围）。 |
| [clearColorKey(int type)](#clearColorKey-int-) | 清除指定类别的颜色键（透明度范围）。 |
| [clearColorMatrix()](#clearColorMatrix--) | 清除默认类别的颜色调整矩阵。 |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 清除指定类别的颜色调整矩阵。 |
| [clearGamma()](#clearGamma--) | 禁用默认类别的伽马校正。 |
| [clearGamma(int type)](#clearGamma-int-) | 禁用指定类别的伽马校正。 |
| [clearNoOp()](#clearNoOp--) | 清除默认类别的 NoOp 设置。 |
| [clearNoOp(int type)](#clearNoOp-int-) | 清除指定类别的 NoOp 设置。 |
| [clearOutputChannel()](#clearOutputChannel--) | 清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。 |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 清除指定类别的（青-品红-黄-黑）输出通道设置。 |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | 清除默认类别的输出通道颜色配置文件设置。 |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 清除指定类别的输出通道颜色配置文件设置。 |
| [clearRemapTable()](#clearRemapTable--) | 清除默认类别的颜色重新映射表。 |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 清除指定类别的颜色重新映射表。 |
| [clearThreshold()](#clearThreshold--) | 清除默认类别的阈值。 |
| [clearThreshold(int type)](#clearThreshold-int-) | 清除指定类别的阈值。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | 设置画笔类别的颜色重新映射表。 |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | 设置默认类别的颜色键。 |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | 设置指定类别的颜色键（透明度范围）。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | 为默认类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 为指定类别设置颜色调整矩阵和灰度调整矩阵。 |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | 为默认类别设置颜色调整矩阵。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | 为默认类别设置颜色调整矩阵。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 为指定类别设置颜色调整矩阵。 |
| [setGamma(float gamma)](#setGamma-float-) | 为默认类别设置伽马值。 |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 为指定类别设置伽马值。 |
| [setNoOp()](#setNoOp--) | 关闭默认类别的颜色调整。 |
| [setNoOp(int type)](#setNoOp-int-) | 关闭指定类别的颜色调整。 |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | 为默认类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 为指定类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | 为默认类别设置输出通道颜色配置文件。 |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 为指定类别设置输出通道颜色配置文件。 |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | 为默认类别设置颜色重新映射表。 |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | 为指定类别设置颜色重新映射表。 |
| [setThreshold(float threshold)](#setThreshold-float-) | 为默认类别设置阈值（透明度范围）。 |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 为指定类别设置阈值（透明度范围）。 |
| [setWrapMode(int mode)](#setWrapMode-int-) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式。 |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式和颜色。 |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式和颜色。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


初始化 com.aspose.psd.ImageAttributes 类的新实例。

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI 图像属性。

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


清除此 com.aspose.psd.ImageAttributes 对象的画笔颜色重新映射表。

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


清除默认类别的颜色键（透明度范围）。

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


清除指定类别的颜色键（透明度范围）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除颜色键的类别。 |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


清除默认类别的颜色调整矩阵。

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


清除指定类别的颜色调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除颜色调整矩阵的类别。 |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


禁用默认类别的伽马校正。

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


禁用指定类别的伽马校正。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要禁用伽马校正的类别。 |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


清除默认类别的 NoOp 设置。

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


清除指定类别的 NoOp 设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除 NoOp 设置的类别。 |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


清除指定类别的（青-品红-黄-黑）输出通道设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除输出通道设置的类别。 |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


清除默认类别的输出通道颜色配置文件设置。

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


清除指定类别的输出通道颜色配置文件设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除输出通道配置文件设置的类别。 |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


清除默认类别的颜色重新映射表。

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


清除指定类别的颜色重新映射表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除重新映射表的类别。 |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


清除默认类别的阈值。

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


清除指定类别的阈值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，指定要清除阈值的类别。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


设置画笔类别的颜色重新映射表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 对象的数组。 |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


设置默认类别的颜色键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 低颜色键值。 |
| colorHigh | [Color](../../com.aspose.psd/color) | 高颜色键值。 |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


设置指定类别的颜色键（透明度范围）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 低颜色键值。 |
| colorHigh | [Color](../../com.aspose.psd/color) | 高颜色键值。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置颜色键的类别。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 灰度调整矩阵。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


为默认类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 灰度调整矩阵。 |
| 标志 | int | Aspose.Imaging.ColorMatrixFlag 的一个元素，用于指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


为指定类别设置颜色调整矩阵和灰度调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 灰度调整矩阵。 |
| mode | int | Aspose.Imaging.ColorMatrixFlag 的一个元素，用于指定将受到颜色调整和灰度调整矩阵影响的图像和颜色类型。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置颜色调整和灰度调整矩阵的类别。 |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


为默认类别设置颜色调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


为默认类别设置颜色调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |
| 标志 | int | Aspose.Imaging.ColorMatrixFlag 的一个元素，用于指定将受到颜色调整矩阵影响的图像和颜色类型。 |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


为指定类别设置颜色调整矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | 颜色调整矩阵。 |
| mode | int | Aspose.Imaging.ColorMatrixFlag 的一个元素，用于指定将受到颜色调整矩阵影响的图像和颜色类型。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置颜色调整矩阵的类别。 |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


为默认类别设置伽马值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 伽马 | float | 伽马校正值。 |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


为指定类别设置伽马值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 伽马 | float | 伽马校正值。 |
| type | int | Aspose.Imaging.ColorAdjustType 枚举的一个元素，用于指定设置伽马值的类别。 |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


关闭默认类别的颜色调整。

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


关闭指定类别的颜色调整。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定关闭颜色校正的类别。 |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


为默认类别设置 CMYK（青-品红-黄-黑）输出通道。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标志 | int | Aspose.Imaging.ColorChannelFlag 的一个元素，用于指定输出通道。 |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


为指定类别设置 CMYK（青-品红-黄-黑）输出通道。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 标志 | int | Aspose.Imaging.ColorChannelFlag 的一个元素，用于指定输出通道。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置输出通道的类别。 |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


为默认类别设置输出通道颜色配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，则此参数可以是文件名。否则，此参数必须是完整的路径名。 |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


为指定类别设置输出通道颜色配置文件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | 颜色配置文件的路径名。如果颜色配置文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，则此参数可以是文件名。否则，此参数必须是完整的路径名。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置输出通道颜色配置文件的类别。 |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


为默认类别设置颜色重新映射表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | 类型为 com.aspose.psd.ColorMap 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


为指定类别设置颜色重新映射表。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | 类型为 com.aspose.psd.ColorMap 的颜色对数组。每个颜色对包含一个现有颜色（第一个值）和它将映射到的颜色（第二个值）。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置颜色重新映射表的类别。 |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


为默认类别设置阈值（透明度范围）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| threshold | float | 指定阈值的实数。 |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


为指定类别设置阈值（透明度范围）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| threshold | float | 从 0.0 到 1.0 的阈值，用作分界点，以对将映射到最大值或最小值的颜色进行排序。 |
| type | int | Aspose.Imaging.ColorAdjustType 的一个元素，用于指定设置颜色阈值的类别。 |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


设置用于决定如何在形状或形状边界上平铺纹理的包装模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


设置用于决定如何在形状或形状边界上平铺纹理的包装模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |
| color | [Color](../../com.aspose.psd/color) | com.aspose.psd.ImageAttributes 对象，用于指定渲染图像之外像素的颜色。如果模式参数设置为 WrapMode.Clamp 且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


设置用于决定如何在形状或形状边界上平铺纹理的包装模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode 的一个元素，用于指定图像的重复副本如何用于平铺区域。 |
| color | [Color](../../com.aspose.psd/color) | 一个颜色对象，用于指定渲染图像之外像素的颜色。如果模式参数设置为  WrapMode.Clamp  且传递给 DrawImage 的源矩形大于图像本身，则此颜色可见。 |
| 夹紧 | boolean | 此参数无效。将其设为 false。 |

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

