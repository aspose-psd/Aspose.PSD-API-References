---
title: "Pen 클래스"
type: docs
weight: 3360
url: /ko/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | 지정된 [Pen.brush](/psd/python-net/aspose.psd/pen/)를 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(brush, width)](#Pen_brush_width_2) | 지정된 [Pen.brush](/psd/python-net/aspose.psd/pen/)와 [Pen.width](/psd/python-net/aspose.psd/pen/)를 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(color)](#Pen_color_3) | 지정된 색상으로 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다. |
| [Pen(color, width)](#Pen_color_width_4) | 지정된 [Pen.color](/psd/python-net/aspose.psd/pen/) 및 [Pen.width](/psd/python-net/aspose.psd/pen/) 속성을 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 정렬을 가져오거나 설정합니다. |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 속성을 결정하는 [Pen.brush](/psd/python-net/aspose.psd/pen/)를 가져오거나 설정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 색상을 가져오거나 설정합니다. |
| compound_array | float | r/w | 복합 펜을 지정하는 값 배열을 가져오거나 설정합니다. 복합 펜은 평행 라인과 간격으로 구성된 복합 라인을 그립니다. |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 라인의 끝에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 라인의 시작에 사용할 사용자 정의 캡을 가져오거나 설정합니다. |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 점선의 대시 끝에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| dash_offset | float | r/w | 선의 시작점부터 대시 패턴 시작까지의 거리를 가져오거나 설정합니다. |
| dash_pattern | float | r/w | 사용자 정의 대시와 공백 배열을 가져오거나 설정합니다. |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 대시선에 사용되는 스타일을 가져오거나 설정합니다. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선의 끝에서 사용되는 캡 스타일을 가져오거나 설정합니다. |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 두 연속 선의 끝에 대한 조인 스타일을 가져오거나 설정합니다. |
| miter_limit | float | r/w | 각진 모서리에서 조인의 두께 제한을 가져오거나 설정합니다. |
| opacity | float | r/w | 객체의 불투명도를 가져오거나 설정합니다. 값은 0과 1 사이여야 합니다. 0은 객체가 완전히 투명함을 의미하고, 1은 객체가 완전히 불투명함을 의미합니다. |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선의 스타일을 가져옵니다. |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선의 시작 부분에 사용되는 캡 스타일을 가져오거나 설정합니다. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | 이 [Pen](/psd/python-net/aspose.psd/pen/)에 대한 기하 변환 복사본을 가져오거나 설정합니다. |
| width | float | r/w | 그리기에 사용되는 Graphics 객체 단위로 이 [Pen](/psd/python-net/aspose.psd/pen/)의 너비를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 변환 행렬에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 곱합니다. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 변환 행렬에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 지정된 순서대로 곱합니다. |
| reset_transform() | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 기하 변환 행렬을 단위 행렬로 재설정합니다. |
| [rotate_transform(angle)](#rotate_transform_angle_3) | 지정된 각도만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | 지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전합니다. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | 지정된 배율만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | 지정된 순서대로 지정된 배율만큼 로컬 기하 변환을 스케일링합니다. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

지정된 [Pen.brush](/psd/python-net/aspose.psd/pen/)를 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 채우기 속성을 결정하는 [Pen.brush](/psd/python-net/aspose.psd/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

지정된 [Pen.brush](/psd/python-net/aspose.psd/pen/)와 [Pen.width](/psd/python-net/aspose.psd/pen/)를 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 특성을 결정하는 [Pen.brush](/psd/python-net/aspose.psd/pen/). |
| width | float | 새로운 [Pen](/psd/python-net/aspose.psd/pen/)의 너비. |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

지정된 색상으로 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 색상을 나타내는 [Pen.color](/psd/python-net/aspose.psd/pen/) 구조. |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

지정된 [Pen.color](/psd/python-net/aspose.psd/pen/) 및 [Pen.width](/psd/python-net/aspose.psd/pen/) 속성을 사용하여 [Pen](/psd/python-net/aspose.psd/pen/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 색상을 나타내는 [Pen.color](/psd/python-net/aspose.psd/pen/) 구조. |
| width | float | 이 [Pen](/psd/python-net/aspose.psd/pen/)의 너비를 나타내는 값. |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

이 [Pen](/psd/python-net/aspose.psd/pen/)의 변환 행렬에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) 객체를 사용하여 변환 행렬을 곱합니다. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

이 [Pen](/psd/python-net/aspose.psd/pen/)의 변환 행렬에 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 지정된 순서대로 곱합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 변환 행렬을 곱하는 [Matrix](/psd/python-net/aspose.psd/matrix/). |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 곱셈 연산을 수행하는 순서. |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

지정된 각도만큼 로컬 기하 변환을 회전합니다. 이 메서드는 회전을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

지정된 순서대로 지정된 각도만큼 로컬 기하 변환을 회전합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 각도 | float | 회전 각도입니다. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 회전 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

지정된 배율만큼 로컬 기하 변환을 스케일링합니다. 이 메서드는 스케일링 행렬을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링하는 계수. |
| sy | float | y축 방향으로 변환을 스케일링하는 계수. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

지정된 순서대로 지정된 배율만큼 로컬 기하 변환을 스케일링합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| sx | float | x축 방향으로 변환을 스케일링하는 계수. |
| sy | float | y축 방향으로 변환을 스케일링하는 계수. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 스케일링 행렬을 추가할지 앞에 삽입할지를 지정하는 [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/)입니다. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선을 끝낼 때 사용되는 캡 스타일을 결정하는 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선의 시작 부분에 사용할 캡 스타일을 나타내는 [LineCap](/psd/python-net/aspose.psd/linecap/). |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 선의 끝 부분에 사용할 캡 스타일을 나타내는 [LineCap](/psd/python-net/aspose.psd/linecap/). |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | 이 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 점선의 시작 또는 끝에 사용할 캡 스타일을 나타내는 [LineCap](/psd/python-net/aspose.psd/linecap/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

지정된 치수만큼 로컬 기하 변환을 평행 이동합니다. 이 메서드는 평행 이동을 변환 앞에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

지정된 순서대로 지정된 치수만큼 로컬 기하 변환을 평행 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | x축에서 평행 이동 값입니다. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | The order (prepend or append) in which to apply the translation. |

