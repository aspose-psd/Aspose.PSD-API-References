---
title: "PathMulticolorGradientBrush Class"
type: docs
weight: 70
url: /ko/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathMulticolorGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PathMulticolorGradientBrush(path)](#PathMulticolorGradientBrush_path_1) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified path. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_2) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(points)](#PathMulticolorGradientBrush_points_3) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_4) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
| [PathMulticolorGradientBrush(points, wrap_mode)](#PathMulticolorGradientBrush_points_wrap_mode_5) | Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the center point of the path gradient. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the focus point for the gradient falloff. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Gets the graphics path this brush was build upon. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | 다중 색 선형 그라디언트를 정의하는 [ColorBlend](/psd/python-net/aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| is_transform_changed | bool | r | 변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나<br/> 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 하위 호환성을 위해 도입되었습니다. |
| opacity | float | r/w | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Gets the path points this brush was build upon. |
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


### Constructor: PathMulticolorGradientBrush(path) {#PathMulticolorGradientBrush_path_1}


```
 PathMulticolorGradientBrush(path) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified path.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | The [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) that defines the area filled by this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/). |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_2}


```
 PathMulticolorGradientBrush(points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(points) {#PathMulticolorGradientBrush_points_3}


```
 PathMulticolorGradientBrush(points) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_4}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) are tiled. |

### Constructor: PathMulticolorGradientBrush(points, wrap_mode) {#PathMulticolorGradientBrush_points_wrap_mode_5}


```
 PathMulticolorGradientBrush(points, wrap_mode) 
```

Initializes a new instance of the [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) class with the specified points and wrap mode.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | A [WrapMode](/psd/python-net/aspose.psd/wrapmode/) that specifies how fills drawn with this [PathMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/pathmulticolorgradientbrush/) are tiled. |

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

