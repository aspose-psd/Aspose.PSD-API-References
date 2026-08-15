---
title: "LinearGradientBrush 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.brushes/lineargradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) with a linear gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [LinearGradientBrush()](#LinearGradientBrush__1) | 기본 매개변수로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.<br/>            시작 색상은 검정색이고, 끝 색상은 흰색이며, 각도는 45도이고 사각형은 (0,0)에 위치하며 크기는 (1,1)입니다. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_2) | 지정된 점과 색상을 사용하여 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(point1, point2, color1, color2)](#LinearGradientBrush_point1_point2_color1_color2_3) | 지정된 점과 색상을 사용하여 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_4) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(rect, color1, color2, angle)](#LinearGradientBrush_rect_color1_color2_angle_5) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
| [LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)](#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7) | 사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 각도 | float | r/w | 그라디언트 각도를 가져오거나 설정합니다. |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | 그라디언트에 대한 사용자 정의 감쇠를 정의하는 위치와 계수를 지정하는 [Blend](/psd/python-net/aspose.psd/blend/) 를 가져오거나 설정합니다. |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| end_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 끝 그라디언트 색상을 가져오거나 설정합니다. |
| gamma_correction | bool | r/w | 이 [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/)에 대해 감마 보정이 활성화되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | 다중 색 선형 그라디언트를 정의하는 [ColorBlend](/psd/python-net/aspose.psd/colorblend/)을 가져오거나 설정합니다. |
| is_angle_scalable | bool | r/w | 이 [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/)와 함께 변환 중에 [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/)이 변경되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| is_transform_changed | bool | r | 변환이 어떤 방식으로든 변경되었는지 여부를 나타내는 값을 가져옵니다. 예를 들어 변환 행렬을 설정하거나<br/> 변환 행렬을 변경하는 메서드를 호출하는 경우입니다. 이 속성은 GDI+와의 하위 호환성을 위해 도입되었습니다. |
| linear_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 그라디언트의 시작 및 끝 색상을 가져오거나 설정합니다. |
| opacity | float | r/w | 브러시 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 브러시가 완전히 투명함을 의미하고, 1은 브러시가 완전히 불투명함을 의미합니다. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | 그라디언트의 시작점과 끝점을 정의하는 사각형 영역을 가져오거나 설정합니다. |
| start_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 시작 그라디언트 색상을 가져오거나 설정합니다. |
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
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | 중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다. |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | 중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다. |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | 벨 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다. |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | 벨 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | 지정된 순서대로 지정된 차원만큼 로컬 기하 변환을 평행 이동합니다. |


### Constructor: LinearGradientBrush() {#LinearGradientBrush__1}


```
 LinearGradientBrush() 
```

기본 매개변수로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.<br/>            시작 색상은 검정색이고, 끝 색상은 흰색이며, 각도는 45도이고 사각형은 (0,0)에 위치하며 크기는 (1,1)입니다.

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_2}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

지정된 점과 색상을 사용하여 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 선형 그라디언트의 시작점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조체입니다. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 선형 그라디언트의 끝점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 선형 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 선형 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |

### Constructor: LinearGradientBrush(point1, point2, color1, color2) {#LinearGradientBrush_point1_point2_color1_color2_3}


```
 LinearGradientBrush(point1, point2, color1, color2) 
```

지정된 점과 색상을 사용하여 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 선형 그라디언트의 시작점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조체입니다. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 선형 그라디언트의 끝점을 나타내는 [Point](/psd/python-net/aspose.psd/point/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 선형 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 선형 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_4}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 선형 그라디언트의 경계를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도( x축을 기준으로 시계 방향으로 측정한 도 단위)입니다. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle) {#LinearGradientBrush_rect_color1_color2_angle_5}


```
 LinearGradientBrush(rect, color1, color2, angle) 
```

사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 선형 그라디언트의 경계를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도( x축을 기준으로 시계 방향으로 측정한 도 단위)입니다. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_6}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 선형 그라디언트의 경계를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도( x축을 기준으로 시계 방향으로 측정한 도 단위)입니다. |
| is_angle_scalable | bool | <c>true</c> 로 설정하면 이 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 로 변환할 때 각도가 변경됩니다. |

### Constructor: LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) {#LinearGradientBrush_rect_color1_color2_angle_is_angle_scalable_7}


```
 LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable) 
```

사각형, 시작 및 끝 색상, 그리고 방향 각도를 기반으로 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 선형 그라디언트의 경계를 지정하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체입니다. |
| color1 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 시작 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체입니다. |
| color2 | [Color](/psd/python-net/aspose.psd/color) | 그라디언트의 끝 색상을 나타내는 [Color](/psd/python-net/aspose.psd/color/) 구조체. |
| 각도 | float | 그라디언트 방향선의 각도( x축을 기준으로 시계 방향으로 측정한 도 단위)입니다. |
| is_angle_scalable | bool | <c>true</c> 로 설정하면 이 [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) 로 변환할 때 각도가 변경됩니다. |

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

중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 그라디언트의 중심을 지정합니다(그라디언트가 오직 끝 색상만으로 구성되는 지점). |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

중심 색상과 양쪽 끝으로 단일 색상으로 선형 감쇠되는 선형 그라디언트를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 그라디언트의 중심을 지정합니다(그라디언트가 오직 끝 색상만으로 구성되는 지점). |
| scale | float | 0부터 1까지의 값으로 시작 색상에서 <paramref name="focus" />(끝 색상)까지 색상이 얼마나 빠르게 감소하는지를 지정합니다. |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

벨 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 그라디언트의 중심을 지정합니다(시작 색상과 끝 색상이 동일하게 혼합되는 지점). |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

벨 모양 곡선을 기반으로 하는 그라디언트 감쇠를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 포커스 | float | 0부터 1까지의 값으로 그라디언트의 중심을 지정합니다(그라디언트가 오직 끝 색상만으로 구성되는 지점). |
| scale | float | 0부터 1까지의 값으로 <paramref name="focus" />에서 색상이 얼마나 빠르게 감소하는지를 지정합니다. |

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

