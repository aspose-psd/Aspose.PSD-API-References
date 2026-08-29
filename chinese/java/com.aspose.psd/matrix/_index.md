---
title: "Matrix"
second_title: "Aspose.PSD 的 Java API 参考"
description: "替换 GDI Matrix。"
type: docs
weight: 69
url: /zh/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

替代 GDI+ Matrix。

大多数算法取自 Sun 的 AffineTransform.java。内部使用的矩阵元素名称来自 Java。java 名称到 .net 名称的映射及说明：m00 M11 缩放 X m10 M12 剪切 Y m01 M21 剪切 X m11 M22 缩放 Y m02 M31 平移 X m12 M32 平移 Y
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix()](#Matrix--) | 将 Matrix 类的新实例初始化为单位矩阵。 |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | 将 Matrix 类的新实例初始化。 |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | 创建 Matrix 类的副本。 |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | 将 Aspose.Imaging.Matrix 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | 将 Aspose.Imaging.Matrix 类的新实例初始化为由指定矩形和点数组定义的几何变换。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | 此标志位表示此对象定义的变换会围绕某个轴进行镜像翻转，除了其他标志位指示的转换外，还会将通常的右手坐标系转换为左手坐标系。 |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | 此标志位表示此对象定义的变换会进行任意角度的旋转，除其他标志位指示的转换外。 |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | 一般的缩放会在 x 和 y 方向上以不同的比例放大向量的长度，而不改变垂直向量之间的角度。 |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | 此常量表示此对象定义的变换会对输入坐标进行任意转换。 |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | 单位变换是指输出坐标始终与输入坐标相同的变换。 |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | 此常量是用于任意旋转标志位的位掩码。 |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | 此常量是用于任意缩放标志位的位掩码。 |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | 此标志位表示此对象定义的变换会进行以 90 度的整数倍为单位的象限旋转，除其他标志位指示的转换外。 |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | 平移会在 x 和 y 方向上以固定量移动坐标，而不改变向量的长度或角度。 |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | 均匀缩放会在 x 和 y 方向上以相同的比例放大向量的长度，而不改变向量之间的角度。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的  System.Object  是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | 获取矩阵元素的副本。 |
| [getM11()](#getM11--) | 获取矩阵第一行第一列的元素。 |
| [getM12()](#getM12--) | 获取矩阵第一行第二列的元素。 |
| [getM21()](#getM21--) | 获取矩阵第二行第一列的元素。 |
| [getM22()](#getM22--) | 获取矩阵第二行第二列的元素。 |
| [getM31()](#getM31--) | 获取矩阵第三行第一列的元素。 |
| [getM32()](#getM32--) | 获取矩阵第三行第一列的元素。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | 确定两个矩阵是否相等。 |
| [isIdentity()](#isIdentity--) | 如果此 `AffineTransform` 是单位变换，则返回 `true`。 |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | 使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。 |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | 将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | 将此 Matrix 重置为单位矩阵的元素。 |
| [rotate(float angle)](#rotate-float-) | 在默认（Prepend）顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。 |
| [rotate(float angle, int order)](#rotate-float-int-) | 在指定的顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。 |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | 在默认（Prepend）顺序下，对此 Matrix 进行关于指定点的顺时针旋转。 |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | 在指定的顺序下，对此 Matrix 进行关于指定点的顺时针旋转。 |
| [scale(float sx, float sy)](#scale-float-float-) | 使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。 |
| [toString()](#toString--) | 返回 一个  System.String  表示此实例。 |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | 将此 Matrix 表示的几何变换应用于指定的点数组。 |
| [translate(float tx, float ty)](#translate-float-float-) | 使用（默认）Prepend 顺序，将指定的平移向量应用于此 Matrix。 |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 在指定的顺序下，将指定的平移向量应用于此 Matrix。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


将 Matrix 类的新实例初始化为单位矩阵。

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


将 Matrix 类的新实例初始化。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| m11 | float | m00 M11 缩放 X |
| m12 | float | m10 M12 剪切 Y |
| m21 | float | m01 M21 剪切 X |
| m22 | float | m11 M22 缩放 Y |
| m31 | float | m02 M31 平移 X |
| m32 | float | m12 M32 平移 Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


创建 Matrix 类的副本。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | 用于协同的基础矩阵 |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


将 Aspose.Imaging.Matrix 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 表示要转换的矩形的 Aspose.Imaging.RectangleF 结构。 |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | 一个包含三个 Aspose.Imaging.PointF 结构的数组，表示要将矩形的左上角、右上角和左下角转换到的平行四边形的点。平行四边形的右下角由前面三个角暗示。 |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


将 Aspose.Imaging.Matrix 类的新实例初始化为由指定矩形和点数组定义的几何变换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 表示要转换的矩形的 Aspose.Imaging.Rectangle 结构。 |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | 一个包含三个 Aspose.Imaging.Point 结构的数组，表示要将矩形的左上角、右上角和左下角转换到的平行四边形的点。平行四边形的右下角由前面三个角暗示。 |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


此标志位指示此对象定义的变换在某个轴上执行镜像翻转，除了其他标志位指示的转换外，还将通常的右手坐标系转换为左手坐标系。右手坐标系是指正 X 轴逆时针旋转以覆盖正 Y 轴，类似于右手拇指指向观察者时手指的卷曲方向。左手坐标系是指正 X 轴顺时针旋转以覆盖正 Y 轴，类似于左手拇指指向观察者时手指的卷曲方向。没有数学方法能够确定原始翻转或镜像变换的角度，因为在适当的调整旋转下，所有翻转角度都是相同的。注意：TypeFlip 是在 GENERAL\\_TRANSFORM 已公开流通后添加的，标志位已无法在不引入外部代码二进制不兼容的情况下方便地重新编号。

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


此标志位指示此对象定义的变换在执行其他标志位指示的转换之外，以任意角度进行旋转。旋转会以相同的量改变向量的角度，而不论向量的原始方向，也不改变向量的长度。此标志位与 the

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


通用缩放在 x 和 y 方向上以不同的量乘以向量的长度，而不改变垂直向量之间的角度。此标志位与 TypeUniformScale 标志互斥。

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


此常量指示此对象定义的变换对输入坐标执行任意转换。如果此变换可以由上述任意常量分类，则其类型将是常量 TypeIdentity，或是针对该变换执行的各种坐标转换的相应标志位的组合。

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


恒等变换是指输出坐标始终与输入坐标相同的变换。如果此变换不是恒等变换，则其类型将是常量 GENERAL\\_TRANSFORM，或是针对该变换执行的各种坐标转换的相应标志位的组合。

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


此常量是用于任意旋转标志位的位掩码。

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


此常量是用于任意缩放标志位的位掩码。

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


此标志位指示此对象定义的变换在执行其他标志位指示的转换之外，以 90 度的整数倍进行象限旋转。旋转会以相同的量改变向量的角度，而不论向量的原始方向，也不改变向量的长度。此标志位与 TypeGeneralRotation 标志互斥。

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


平移会在 x 和 y 方向上以固定量移动坐标，而不改变向量的长度或角度。

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


统一缩放在 x 和 y 方向上以相同的量乘以向量的长度，而不改变向量之间的角度。此标志位与 TypeGeneralScale 标志互斥。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的  System.Object  是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 System.Object。 |

**Returns:**
布尔 - 如果指定的 System.Object 等于此实例，则为 true；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


获取矩阵元素的副本。

**Returns:**
float[] - 矩阵元素的副本。
### getM11() {#getM11--}
```
public float getM11()
```


获取矩阵第一行第一列的元素。表示沿 X 轴的缩放。

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


获取矩阵第一行第二列的元素。表示沿 Y 轴的剪切。

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


获取矩阵第二行第一列的元素。表示沿 X 轴的剪切。

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


获取矩阵第二行第二列的元素。表示沿 Y 轴的缩放。

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


获取矩阵第三行第一列的元素。表示沿 X 轴的平移。

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


获取矩阵第三行第一列的元素。表示沿 Y 轴的平移。

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


确定两个矩阵是否相等。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | 要比较的第一个矩阵。 |
| b | [Matrix](../../com.aspose.psd/matrix) | 要比较的第二个矩阵。 |

**Returns:**
布尔 - 如果矩阵相等则为 True。
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


如果此 `AffineTransform` 是单位变换，则返回 `true`。

**Returns:**
布尔 - 如果此 `AffineTransform` 是单位变换则为 `true`；否则为 `false`。
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


使用（默认）Prepend 顺序，将此 Matrix 与 matrix 参数中指定的矩阵相乘。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | 用于相乘的矩阵。 |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


将此 Matrix 与 matrix 参数中指定的矩阵相乘，并使用 order 参数中指定的顺序。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx。 tx。 tx。 |
| 顺序 | int | 顺序。 顺序。 顺序。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


将此 Matrix 重置为单位矩阵的元素。

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


在默认（Prepend）顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


在指定的顺序下，对此 Matrix 进行顺时针旋转，旋转角度由 angle 参数指定，围绕原点（零 x 和 y 坐标）进行。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 旋转角度。 |
| 顺序 | int | 矩阵顺序。 |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


在默认（Prepend）顺序下，对此 Matrix 进行关于指定点的顺时针旋转。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 角度。 |
| point | [PointF](../../com.aspose.psd/pointf) | 该点。 |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


在指定的顺序下，对此 Matrix 进行关于指定点的顺时针旋转。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| angle | float | 角度。 |
| point | [PointF](../../com.aspose.psd/pointf) | 该点。 |
| 顺序 | int | 顺序。 |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


使用（默认）Prepend 顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sx | float | sx。 sx。 sx。 |
| sy | float | sy。 sy。 sy。 |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


使用指定的顺序，将指定的缩放向量（scaleX 和 scaleY）应用于此 Matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scaleX | float | X 方向比例。 |
| scaleY | float | Y 方向比例。 |
| 顺序 | int | 顺序。 |

### toString() {#toString--}
```
public String toString()
```


返回 一个  System.String  表示此实例。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


将此 Matrix 表示的几何变换应用于指定的点数组。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 点。 |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


使用（默认）Prepend 顺序，将指定的平移向量应用于此 Matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| tx | float | tx。 tx。 tx。 |
| ty | float | ty。 ty。 ty。 |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


在指定的顺序下，将指定的平移向量应用于此 Matrix。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| offsetX | float | 偏移 X。 |
| offsetY | float | 偏移 Y。 |
| 顺序 | int | 顺序。 |

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

