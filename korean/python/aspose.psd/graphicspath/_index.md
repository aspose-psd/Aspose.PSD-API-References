---
title: "GraphicsPath 클래스"
type: docs
weight: 1570
url: /ko/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | 새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다. |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | 새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다. |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | 새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다. |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | 새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져오거나 설정합니다. |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | 경로 도형을 가져옵니다. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 모양 내부가 채워지는 방식을 결정하는 [FillMode](/psd/python-net/aspose.psd/fillmode/) 열거형을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | 새 도형을 추가합니다. |
| [add_figures(figures)](#add_figures_figures_2) | 새 도형들을 추가합니다. |
| [add_path(adding_path)](#add_path_adding_path_3) | 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을(를) 이 경로에 추가합니다. |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을(를) 이 경로에 추가합니다. |
| [deep_clone()](#deep_clone__5) | 이 그래픽 경로를 깊게 복제합니다. |
| flatten() | 이 경로의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [flatten(matrix)](#flatten_matrix_6) | 지정된 변환을 적용한 다음 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 각 곡선을 연결된 선분 시퀀스로 변환합니다. |
| [get_bounds(matrix)](#get_bounds_matrix_8) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | 객체의 경계를 가져옵니다. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | 지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다. |
| [is_visible(point)](#is_visible_point_18) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(point)](#is_visible_point_19) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(x, y)](#is_visible_x_y_22) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(x, y)](#is_visible_x_y_23) | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)의 보이는 클립 영역에서 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)의 보이는 클립 영역에서 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다. |
| [remove_figure(figure)](#remove_figure_figure_26) | 도형을 제거합니다. |
| [remove_figures(figures)](#remove_figures_figures_27) | 도형들을 제거합니다. |
| reset() | 그래픽 경로를 비우고 [FillMode](/psd/python-net/aspose.psd/fillmode/)을 [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/)로 설정합니다. |
| reverse() | 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 각 모양에서 도형, 형태 및 점의 순서를 반대로 합니다. |
| [transform(transform)](#transform_transform_28) | 지정된 변환을 도형에 적용합니다. |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | 사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다. |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | 사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다. |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | 사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다. |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | 사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다. |
| [widen(pen)](#widen_pen_33) | 경로에 추가 외곽선을 추가합니다. |
| [widen(pen, matrix)](#widen_pen_matrix_34) | 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 추가 외곽선을 추가합니다. |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | 지정된 펜으로 이 경로를 그릴 때 채워지는 영역을 둘러싸는 곡선으로 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을 교체합니다. |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다.

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 초기화할 도형들. |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 초기화할 도형들. |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 채우기 모드. |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

새로운 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 채우기 모드. |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

새 도형을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 추가할 도형. |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

새 도형들을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 추가할 도형들. |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을(를) 이 경로에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 추가할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을(를) 이 경로에 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 추가할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| 연결 | bool | 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형의 일부인지 여부를 지정하는 부울 값입니다. true 값은 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형의 일부임을 지정합니다. false 값은 추가된 경로의 첫 번째 도형이 이 경로의 마지막 도형과 별개임을 지정합니다. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

이 그래픽 경로를 깊게 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 그래픽 경로의 깊은 복제본입니다. |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

지정된 변환을 적용한 다음 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 평탄화하기 전에 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)를 변환할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 각 곡선을 연결된 선분 시퀀스로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 평탄화하기 전에 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)를 변환할 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| 평탄도 | float | 곡선과 평탄화된 근사치 사이의 허용 가능한 최대 오차를 지정합니다. 기본값은 0.25입니다. 평탄도 값을 낮추면 근사치의 선분 수가 증가합니다. |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

객체의 경계를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경계 이전에 적용할 행렬이 계산됩니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 예상 객체의 경계입니다. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

객체의 경계를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경계 이전에 적용할 행렬이 계산됩니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 객체에 사용할 펜입니다. 이는 객체의 경계 크기에 영향을 줄 수 있습니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 예상 객체의 경계입니다. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 위치를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그렸을 때 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 테스트할 위치를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그렸을 때 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 위치를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | 테스트할 위치를 지정하는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그렸을 때 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그렸을 때 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

지정된 [Pen](/psd/python-net/aspose.psd/pen/)과 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래)에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 테스트할 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 지정된 [Pen](/psd/python-net/aspose.psd/pen/)으로 그린 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 외곽선(아래) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 테스트할 점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | 테스트할 점을 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)의 보이는 클립 영역에서 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)의 보이는 클립 영역에서 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 내부에 포함되는지 여부를 나타냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 가시성을 테스트할 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 점이 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 안에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

도형을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 제거할 도형입니다. |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

도형들을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 제거할 도형들입니다. |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

지정된 변환을 도형에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 적용할 변환입니다. |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF] 배열 구조체로, <paramref name=\"srcRect\" /> 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면 평행사변형의 오른쪽 아래 모서리는 첫 세 점으로 암시됩니다. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 평행사변형 <paramref name=\"destPoints\" /> 로 정의된 사각형으로 변환되는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 나타냅니다. |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF] 배열 구조체로, <paramref name=\"srcRect\" /> 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면 평행사변형의 오른쪽 아래 모서리는 첫 세 점으로 암시됩니다. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 평행사변형 <paramref name=\"destPoints\" /> 로 정의된 사각형으로 변환되는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 나타냅니다. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF] 배열 구조체로, <paramref name=\"srcRect\" /> 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면 평행사변형의 오른쪽 아래 모서리는 첫 세 점으로 암시됩니다. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 평행사변형 <paramref name=\"destPoints\" /> 로 정의된 사각형으로 변환되는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 나타냅니다. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | [WarpMode](/psd/python-net/aspose.psd/warpmode/) 열거형으로, 이 왜곡 작업이 원근법 모드인지 또는 이중선형 모드인지를 지정합니다. |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

사각형과 평행사변형으로 정의된 워프 변환을 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | [PointF] 배열 구조체로, <paramref name=\"srcRect\" /> 로 정의된 사각형이 변환되는 평행사변형을 정의합니다. 배열은 세 개 또는 네 개의 요소를 포함할 수 있습니다. 배열에 세 개의 요소가 있으면 평행사변형의 오른쪽 아래 모서리는 첫 세 점으로 암시됩니다. |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 평행사변형 <paramref name=\"destPoints\" /> 로 정의된 사각형으로 변환되는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 나타냅니다. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경로에 적용할 기하학적 변환을 지정하는 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | [WarpMode](/psd/python-net/aspose.psd/warpmode/) 열거형으로, 이 왜곡 작업이 원근법 모드인지 또는 이중선형 모드인지를 지정합니다. |
| flatness | float | 0에서 1 사이의 값으로, 결과 경로의 평탄함 정도를 지정합니다. 자세한 내용은 [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) 메서드를 참조하십시오. |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

경로에 추가 외곽선을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 경로의 원래 외곽선 사이의 너비를 지정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)에 추가 외곽선을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 경로의 원래 외곽선 사이의 너비를 지정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 넓히기 전에 경로에 적용할 변환을 지정하는 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

지정된 펜으로 이 경로를 그릴 때 채워지는 영역을 둘러싸는 곡선으로 이 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)을 교체합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 이 메서드가 생성하는 새 외곽선과 경로의 원래 외곽선 사이의 너비를 지정하는 [Pen](/psd/python-net/aspose.psd/pen/)입니다. |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 넓히기 전에 경로에 적용할 변환을 지정하는 [Matrix](/psd/python-net/aspose.psd/matrix/)입니다. |
| 평탄도 | float | 곡선의 평탄도를 지정하는 값입니다. |

