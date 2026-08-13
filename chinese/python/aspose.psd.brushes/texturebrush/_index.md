---
title: "TextureBrush 类"
type: docs
weight: 90
url: /zh/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | 使用指定的图像初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | 使用指定的图像和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | 使用指定的图像和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | 使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | 使用指定的图像和包装模式初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | 使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| image | [Image](/psd/python-net/aspose.psd/image) | r | 获取与此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象关联的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | 获取与此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 关联的 [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/)。 |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 获取与此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 关联的 [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |
| is_transform_changed | bool | r | 获取一个值，指示变换是否以某种方式被更改。例如，设置变换矩阵或<br/> 调用任何修改变换矩阵的方法。此属性为向后兼容 GDI+ 引入。 |
| opacity | float | 读/写 | 获取或设置画笔不透明度。该值应在 0 到 1 之间。0 表示画笔完全可见，1 表示画笔完全不透明。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 获取或设置一个复制的 [Matrix](/psd/python-net/aspose.psd/matrix/) ，它定义此 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) 的局部几何变换。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | 获取或设置一个指示此 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) 包装模式的 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 枚举。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 创建当前 [Brush](/psd/python-net/aspose.psd/brush/) 的深度克隆副本。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | 将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘，方法是将指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 前置。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | 将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 按指定顺序相乘。 |
| reset_transform() | 将 [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) 属性重置为单位矩阵。 |
| [rotate_transform(angle)](#rotate_transform_angle_4) | 按指定的量旋转局部几何变换。此方法将在变换前置旋转。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | 按指定的量并按照指定顺序旋转局部几何变换。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | 按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | 按指定的比例并按照指定顺序缩放局部几何变换。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 按指定的尺寸平移局部几何变换。此方法将在变换前置平移。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 按指定的尺寸并按照指定顺序平移局部几何变换。 |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

使用指定的图像初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

使用指定的图像和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 一个 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象，包含此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象使用的图像的附加信息。 |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

使用指定的图像、边界矩形和图像属性初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 一个 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 对象，包含此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象使用的图像的附加信息。 |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

使用指定的图像和包装模式初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 一个 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 枚举，指定此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的平铺方式。 |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 一个 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 枚举，指定此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的平铺方式。 |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

使用指定的图像、包装模式和边界矩形初始化 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | 此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象用于填充内部的 [Image](/psd/python-net/aspose.psd/image/) 对象。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 一个 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 枚举，指定此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的平铺方式。 |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 表示此 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 对象的边界矩形的 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 结构。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

创建当前 [Brush](/psd/python-net/aspose.psd/brush/) 的深度克隆副本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | 一个新的 [Brush](/psd/python-net/aspose.psd/brush/)，它是此 [Brush](/psd/python-net/aspose.psd/brush/) 实例的深度克隆。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 相乘，方法是将指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 前置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

将表示此 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 的局部几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/) 与指定的 [Matrix](/psd/python-net/aspose.psd/matrix/) 按指定顺序相乘。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 用于乘以几何变换的 [Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定两个矩阵相乘顺序的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

按指定的量旋转局部几何变换。此方法将在变换前置旋转。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

按指定的量并按照指定顺序旋转局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 角度 | float | 旋转角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置旋转矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

按指定的比例缩放局部几何变换。此方法将在变换前置缩放矩阵。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

按指定的比例并按照指定顺序缩放局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| sx | float | 在 x 轴方向上缩放变换的量。 |
| sy | float | 在 y 轴方向上缩放变换的量。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 指定是追加还是前置缩放矩阵的 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

按指定的尺寸平移局部几何变换。此方法将在变换前置平移。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

按指定的尺寸并按照指定顺序平移局部几何变换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| dx | float | x 方向的平移值。 |
| dy | float | y 方向的平移值。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 应用平移的顺序（前置或后置）。 |

