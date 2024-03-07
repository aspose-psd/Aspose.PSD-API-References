---
title: TextureBrush Class
type: docs
weight: 90
url: /python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and wrap mode. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Gets the [Image](/psd/python-net/aspose.psd/image/) object associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Gets the [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the [Rectangle](/psd/python-net/aspose.psd/rectangle/) associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Gets or sets a copy [Matrix](/psd/python-net/aspose.psd/matrix/) that defines a local geometric transform for this [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Gets or sets a [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Creates a new deep clone of the current [Brush](/psd/python-net/aspose.psd/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order. |
| reset_transform() | Resets the [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeration that specifies how this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object is tiled. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeration that specifies how this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) enumeration that specifies how this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/psd/python-net/aspose.psd/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | A new [Brush](/psd/python-net/aspose.psd/brush/) which is the deep clone of this [Brush](/psd/python-net/aspose.psd/brush/) instance. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) by prepending the specified [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/psd/python-net/aspose.psd/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) by the specified [Matrix](/psd/python-net/aspose.psd/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | The [Matrix](/psd/python-net/aspose.psd/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | A [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

