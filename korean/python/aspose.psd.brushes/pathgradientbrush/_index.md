---
title: "PathGradientBrush 클래스"
type: docs
weight: 50
url: /ko/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | 지정된 경로를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | 지정된 점들을 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | 지정된 점들을 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | 지정된 점들과 랩 모드를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | 지정된 점들과 랩 모드를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 [Blend](/psd/python-net/aspose.psd/blend/) 를 가져오거나 설정합니다. |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 경로 그라디언트의 중심에 있는 색상을 가져오거나 설정합니다. |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the center point of the path gradient. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the focus point for the gradient falloff. |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | Gets the graphics path this brush was build upon. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | 다중 색 선형 그라디언트를 정의하는 [ColorBlend](/psd/python-net/aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| is_transform_changed | bool | r | 변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나<br/> 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 하위 호환성을 위해 도입되었습니다. |
| opacity | float | r/w | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | Gets the path points this brush was build upon. |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 이 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/)가 채우는 경로의 점에 해당하는 색상 배열을 가져오거나 설정합니다. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | 중심 색상과 하나의 주변 색상으로 선형 감소하는 그라디언트를 생성합니다. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | 중심 색상과 각 주변 색상으로 선형 감소하는 그라디언트를 생성합니다. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | 경로의 중심에서 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | 경로의 중심에서 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

지정된 경로를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/)가 채우는 영역을 정의하는 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)입니다. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

지정된 점들을 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

지정된 점들을 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

지정된 점들과 랩 모드를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 이 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/)로 그린 채우기가 어떻게 타일링되는지를 지정하는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/)입니다. |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

지정된 점들과 랩 모드를 사용하여 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | An array of [PointF](/psd/python-net/aspose.psd/pointf/) structures that represents the points that make up the vertices of the path. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | 이 [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/)로 그린 채우기가 어떻게 타일링되는지를 지정하는 [WrapMode](/psd/python-net/aspose.psd/wrapmode/)입니다. |

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

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

중심 색상과 하나의 주변 색상으로 선형 감소하는 그라디언트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 경로의 중심에서 경로 경계까지의 방사선 상에서 중심 색상이 가장 높은 강도를 갖는 위치를 지정합니다. 값 1(기본값)은 경로 중심에 가장 높은 강도를 배치합니다. |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

중심 색상과 각 주변 색상으로 선형 감소하는 그라디언트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 경로의 중심에서 경로 경계까지의 방사선 상에서 중심 색상이 가장 높은 강도를 갖는 위치를 지정합니다. 값 1(기본값)은 경로 중심에 가장 높은 강도를 배치합니다. |
| scale | float | 0부터 1까지의 값으로 경계 색상과 혼합되는 중심 색상의 최대 강도를 지정합니다. 값 1은 가능한 가장 높은 중심 색상 강도를 발생시키며, 이는 기본값입니다. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

경로의 중심에서 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 경로의 중심에서 경로 경계까지의 방사선 상에서 중심 색상이 가장 높은 강도를 갖는 위치를 지정합니다. 값 1(기본값)은 경로 중심에 가장 높은 강도를 배치합니다. |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

경로의 중심에서 경로 경계까지 색상이 변하는 그라디언트 브러시를 생성합니다. 한 색상에서 다른 색상으로의 전환은 종 모양 곡선을 기반으로 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 경로의 중심에서 경로 경계까지의 방사선 상에서 중심 색상이 가장 높은 강도를 갖는 위치를 지정합니다. 값 1(기본값)은 경로 중심에 가장 높은 강도를 배치합니다. |
| scale | float | 0부터 1까지의 값으로 경계 색상과 혼합되는 중심 색상의 최대 강도를 지정합니다. 값 1은 가능한 가장 높은 중심 색상 강도를 발생시키며, 이는 기본값입니다. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


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

