---
title: "Pen"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义用于绘制线条、曲线和图形的对象。"
type: docs
weight: 77
url: /zh/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

定义用于绘制直线、曲线和图形的对象。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | 使用指定的颜色初始化 Pen 类的新实例。 |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | 使用指定的 Color 和 Pen.Width 属性初始化 Pen 类的新实例。 |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | 使用指定的 Brush 初始化 Pen 类的新实例。 |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | 使用指定的 Brush 和 Pen.Width 初始化 Pen 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取此 Pen 的对齐方式。 |
| [getBrush()](#getBrush--) | 获取决定此 Pen 属性的 Brush。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 获取此  Pen 的颜色 . |
| [getCompoundArray()](#getCompoundArray--) | 获取指定复合笔的值数组 . |
| [getCustomEndCap()](#getCustomEndCap--) | 获取在使用此  Pen 绘制的线条末端使用的自定义端帽 . |
| [getCustomStartCap()](#getCustomStartCap--) | 获取在使用此  Pen 绘制的线条起始端使用的自定义端帽 . |
| [getDashCap()](#getDashCap--) | 获取使用此  Pen 绘制的虚线中破折号末端使用的帽子样式 . |
| [getDashOffset()](#getDashOffset--) | 获取从线条起点到破折号模式起始的距离 . |
| [getDashPattern()](#getDashPattern--) | 获取自定义破折号和空格的数组 . |
| [getDashStyle()](#getDashStyle--) | 获取使用此  Pen 绘制的虚线的样式 . |
| [getEndCap()](#getEndCap--) | 获取使用此  Pen 绘制的线条末端使用的帽子样式 . |
| [getLineJoin()](#getLineJoin--) | 获取使用此  Pen 绘制的两条连续线条端点的连接样式 . |
| [getMiterLimit()](#getMiterLimit--) | 获取斜接角处连接厚度的限制 . |
| [getOpacity()](#getOpacity--) | 获取对象的不透明度。 |
| [getPenType()](#getPenType--) | 获取使用此  Pen 绘制的线条的样式 . |
| [getStartCap()](#getStartCap--) | 获取使用此  Pen 绘制的线条起始端使用的帽子样式 . |
| [getTransform()](#getTransform--) | 获取此  Pen 的几何变换的副本 . |
| [getWidth()](#getWidth--) | 获取此  Pen 的宽度，单位为用于绘图的 Graphics 对象的单位 . |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | 将此  Pen 的变换矩阵乘以指定的  Matrix . |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | 将此  Pen 的变换矩阵按指定顺序乘以指定的  Matrix . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | 将此  Pen 的几何变换矩阵重置为单位矩阵 . |
| [rotateTransform(float angle)](#rotateTransform-float-) | 按指定角度旋转局部几何变换 . |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | 按指定顺序按指定角度旋转局部几何变换 . |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 按指定因子缩放局部几何变换 . |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按指定顺序按指定因子缩放局部几何变换 . |
| [setAlignment(int value)](#setAlignment-int-) | 设置此  Pen 的对齐方式 . |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | 设置决定此  Pen 属性的  Brush . |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 设置此  Pen 的颜色 . |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 设置一个值数组，用于指定复合笔。 |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | 设置一个自定义帽子，用于此  Pen  绘制的线条末端。 |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | 设置一个自定义帽子，用于此  Pen  绘制的线条起始端。 |
| [setDashCap(int value)](#setDashCap-int-) | 设置用于此  Pen  绘制的虚线中破折号末端的帽子样式。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 设置从线条起点到破折号模式起始点的距离。 |
| [setDashPattern(float[] value)](#setDashPattern-float---) | 设置自定义破折号和空格的数组。 |
| [setDashStyle(int value)](#setDashStyle-int-) | 设置此  Pen  绘制的虚线所使用的样式。 |
| [setEndCap(int value)](#setEndCap-int-) | 设置此  Pen  绘制的线条末端使用的帽子样式。 |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | 设置决定此  Pen  绘制的线条结束时使用的帽子样式的值。 |
| [setLineJoin(int value)](#setLineJoin-int-) | 设置此  Pen  绘制的两条连续线条端点的连接样式。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 设置斜接角处连接厚度的限制。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置对象的不透明度。 |
| [setStartCap(int value)](#setStartCap-int-) | 设置此  Pen  的几何变换的副本。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | 设置此  Pen  的宽度，单位为用于绘图的 Graphics 对象的单位。 |
| [setWidth(float value)](#setWidth-float-) | 按指定的尺寸平移本地几何变换。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | 按指定的顺序使用指定的尺寸平移本地几何变换。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 一个  Color  结构，指示此  Pen  的颜色。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


使用指定的颜色初始化 Pen 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 一个指示此  Pen  宽度的值。 |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


使用指定的 Color 和 Pen.Width 属性初始化 Pen 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 一个指示此  Pen  宽度的值。 |
| 宽度 | float | 一个  Brush ，决定此  Pen  的填充属性。 |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


使用指定的 Brush 初始化 Pen 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 一个  Brush ，决定此  Pen  的特性。 |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


使用指定的 Brush 和 Pen.Width 初始化 Pen 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | 新  Pen  的宽度。 |
| 宽度 | float | int - 一个  PenAlignment ，表示此  Pen  的对齐方式。 |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取此 Pen 的对齐方式。

**Returns:**
获取一个值数组，用于指定复合笔。复合笔绘制由平行线和间隔组成的复合线。
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


获取决定此 Pen 属性的 Brush。

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


获取此  Pen 的颜色 .

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


float[] - 一个实数数组，用于指定复合数组。数组中的元素必须递增，且不小于 0，且不大于 1。

**Returns:**
int - 一个  DashCap  值，表示此  Pen  绘制的虚线中破折号起始和结束时使用的帽子样式。
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


获取在使用此  Pen 绘制的线条末端使用的自定义端帽 .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


获取在使用此  Pen 绘制的线条起始端使用的自定义端帽 .

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


获取使用此  Pen 绘制的虚线中破折号末端使用的帽子样式 .

**Returns:**
int - 表示在使用此 Pen 绘制的虚线的破折号开头和结尾使用的帽形样式的 DashCap 值之一。
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


获取从线条起点到破折号模式起始的距离 .

**Returns:**
float - 从线段起点到破折号模式起始点的距离。
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


获取自定义破折号和空格的数组 .

**Returns:**
float[] - 一个实数数组，用于指定虚线中交替的破折号和空格的长度。
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


获取使用此  Pen 绘制的虚线的样式 .

**Returns:**
int - 表示使用此 Pen 绘制的虚线的样式的 DashStyle。
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


获取使用此  Pen 绘制的线条末端使用的帽子样式 .

**Returns:**
int - 表示使用此 Pen 绘制的线段末端的帽子样式的 LineCap 值之一。
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


获取使用此  Pen 绘制的两条连续线条端点的连接样式 .

**Returns:**
int - 表示使用此 Pen 绘制的两条连续线段端点的连接样式的 LineJoin。
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


获取斜接角处连接厚度的限制 .

**Returns:**
float - 斜接角处连接的厚度上限。
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取对象的不透明度。该值应在 0 到 1 之间。0 表示对象完全可见，1 表示对象完全不透明。

**Returns:**
float - 不透明度值。
### getPenType() {#getPenType--}
```
public int getPenType()
```


获取使用此  Pen 绘制的线条的样式 .

**Returns:**
int - 指定使用此 Pen 绘制的线条样式的 PenType 枚举。
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


获取使用此  Pen 绘制的线条起始端使用的帽子样式 .

**Returns:**
int - 表示使用此 Pen 绘制的线段起始端的帽子样式的 LineCap 值之一。
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取此  Pen 的几何变换的副本 .

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


获取此  Pen 的宽度，单位为用于绘图的 Graphics 对象的单位 .

**Returns:**
float - 此 Pen 的宽度。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将此  Pen 的变换矩阵乘以指定的  Matrix .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以变换矩阵的 Matrix 对象。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


将此  Pen 的变换矩阵按指定顺序乘以指定的  Matrix .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 用于乘以变换矩阵的 Matrix。 |
| 顺序 | int | 执行乘法操作的顺序。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


将此  Pen 的几何变换矩阵重置为单位矩阵 .

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


按指定角度旋转局部几何变换。此方法将在变换前置旋转矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


按指定顺序按指定角度旋转局部几何变换 .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| 顺序 | int | 指定是追加还是前置旋转矩阵的 MatrixOrder。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


按指定因子缩放局部几何变换。此方法将在变换前置缩放矩阵。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按指定顺序按指定因子缩放局部几何变换 .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | 在 x 轴方向上缩放变换的因子。 |
| sy | float | 在 y 轴方向上缩放变换的因子。 |
| 顺序 | int | 指定是追加还是前置缩放矩阵的 MatrixOrder。 |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


设置此  Pen 的对齐方式 .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 表示此 Pen 对齐方式的 PenAlignment。 |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


设置决定此  Pen 属性的  Brush .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | 确定此 Pen 属性的 Brush。 |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


设置此  Pen 的颜色 .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 表示此 Pen 颜色的 Color 结构。 |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


设置一个值数组，用于指定复合笔。复合笔绘制由平行线和间隔组成的复合线。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float[] | 一个实数数组，用于指定复合数组。数组中的元素必须递增，且不小于 0，且不大于 1。 |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


设置一个自定义帽子，用于此  Pen  绘制的线条末端。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | 表示使用此 Pen 绘制的线段末端的帽子的 CustomLineCap。 |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


设置一个自定义帽子，用于此  Pen  绘制的线条起始端。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | 表示使用此 Pen 绘制的线段起始端的帽子的 CustomLineCap。 |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


设置用于此  Pen  绘制的虚线中破折号末端的帽子样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | DashCap 的一个值，表示使用此 Pen 绘制的虚线中组成虚线的短划线的起始和结束的帽子样式。 |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


设置从线条起点到破折号模式起始点的距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 从线段起点到虚线模式起始点的距离。 |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


设置自定义破折号和空格的数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float[] | 一个实数数组，指定虚线中交替的短划线和空白的长度。 |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


设置此  Pen  绘制的虚线所使用的样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | DashStyle，表示使用此 Pen 绘制的虚线的样式。 |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


设置此  Pen  绘制的线条末端使用的帽子样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | LineCap 的一个值，表示使用此 Pen 绘制的线段末端的帽子样式。 |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


设置决定此  Pen  绘制的线条结束时使用的帽子样式的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| startCap | int | LineCap，表示使用此 Pen 绘制的线段起始端要使用的帽子样式。 |
| endCap | int | LineCap，表示使用此 Pen 绘制的线段末端要使用的帽子样式。 |
| dashCap | int | LineCap，表示使用此 Pen 绘制的虚线的起始或结束端要使用的帽子样式。 |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


设置此  Pen  绘制的两条连续线条端点的连接样式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | LineJoin，表示使用此 Pen 绘制的两条连续线段端点的连接样式。 |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


设置斜接角处连接厚度的限制。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 斜接角处连接的厚度限制。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置对象的不透明度。该值应在 0 到 1 之间。值为 0 表示对象完全可见，值为 1 表示对象完全不透明。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 不透明度值。 |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


设置此  Pen  的几何变换的副本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | LineCap 的一个值，表示使用此 Pen 绘制的线段起始端的帽子样式。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


设置此  Pen  的宽度，单位为用于绘图的 Graphics 对象的单位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Matrix 的副本，表示此 Pen 的几何变换。 |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


按指定的尺寸平移本地几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 此 Pen 的宽度。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


按指定的尺寸平移本地几何变换。此方法将在变换前添加平移。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


一个  Color  结构，指示此  Pen  的颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| dx | float | x 方向平移的值。 |
| dy | float | y 方向平移的值。 |
| 顺序 | int | 应用平移的顺序（预置或追加）。 |

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

