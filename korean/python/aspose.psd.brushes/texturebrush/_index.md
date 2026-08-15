---
title: "TextureBrush Class"
type: docs
weight: 90
url: /ko/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
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
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Gets the [Image](/psd/python-net/aspose.psd/image/) object associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Gets the [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets the [Rectangle](/psd/python-net/aspose.psd/rectangle/) associated with this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/). |
| is_transform_changed | bool | r | 변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나<br/> 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 하위 호환성을 위해 도입되었습니다. |
| opacity | float | r/w | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 이 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/)에 대한 로컬 기하 변환을 정의하는 복사본 [Matrix](/psd/python-net/aspose.psd/matrix/)을 가져오거나 설정합니다. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | 이 [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/)의 랩 모드를 나타내는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 열거형을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 현재 [Brush](/psd/python-net/aspose.psd/brush/)의 새로운 깊은 복제본을 생성합니다. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 앞에 붙여 곱합니다. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 지정된 순서대로 곱합니다. |
| reset_transform() | 다음 [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) 속성을 identity로 재설정합니다. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | 지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전시킵니다. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | 지정된 양큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | 지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 객체가 사용하는 이미지에 대한 추가 정보를 포함하는 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 객체입니다. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | 이 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 객체가 사용하는 이미지에 대한 추가 정보를 포함하는 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 객체입니다. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image and wrap mode.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 이 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 객체가 타일링되는 방식을 지정하는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 열거형입니다. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 이 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 객체가 타일링되는 방식을 지정하는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 열거형입니다. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | The [Image](/psd/python-net/aspose.psd/image/) object with which this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 이 [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) 객체가 타일링되는 방식을 지정하는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 열거형입니다. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) object. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

현재 [Brush](/psd/python-net/aspose.psd/brush/)의 새로운 깊은 복제본을 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | 이 [Brush](/psd/python-net/aspose.psd/brush/) 인스턴스의 깊은 복제본인 새로운 [Brush](/psd/python-net/aspose.psd/brush/)입니다. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

[LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 앞에 붙여 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 기하 변환에 곱할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

[LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/)의 로컬 기하 변환을 나타내는 [Matrix](/psd/python-net/aspose.psd/matrix/)에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 지정된 순서대로 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 기하 변환에 곱할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 두 행렬을 곱할 순서를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

지정된 양만큼 로컬 기하 변환을 회전시킵니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

지정된 순서대로 지정된 양만큼 로컬 기하 변환을 회전시킵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 회전 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

지정된 양큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링할 양입니다. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

지정된 순서대로 지정된 양만큼 로컬 기하 변환을 스케일링합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링할 양입니다. |
| sy | float | y축 방향으로 변환을 스케일링할 양입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 스케일링 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

