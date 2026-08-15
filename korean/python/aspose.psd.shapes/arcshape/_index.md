---
title: "ArcShape 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | 새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | 새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | 새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져옵니다. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 도형의 중심을 가져옵니다. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 끝 도형 점을 가져옵니다. |
| has_segments | bool | r | 도형에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| is_closed | bool | r/w | 정렬된 도형이 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. 닫힌 정렬 도형을 처리할 때 시작점과 끝점은 의미가 없습니다. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 아래 사각형 점을 가져옵니다. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 위 사각형 점을 가져옵니다. |
| rectangle_height | double | r | 사각형 높이를 가져옵니다. |
| rectangle_width | double | r | 사각형 너비를 가져옵니다. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 아래 사각형 점을 가져옵니다. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 위 사각형 점을 가져옵니다. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 도형 세그먼트를 가져옵니다. |
| start_angle | float | r/w | 시작 각도를 가져오거나 설정합니다. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 시작 도형 점을 가져옵니다. |
| sweep_angle | float | r/w | 스윕 각도를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 객체의 경계를 가져옵니다. |
| reverse() | 이 도형의 포인트 순서를 반전시킵니다. |
| [transform(transform)](#transform_transform_3) | 지정된 변환을 도형에 적용합니다. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 사각형. |
| start_angle | float | 시작 각도. |
| sweep_angle | float | 스윕 각도. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

새로운 [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 사각형. |
| start_angle | float | 시작 각도. |
| sweep_angle | float | 스윕 각도. |
| is_closed | bool | 만약 <c>true</c> 로 설정하면 호가 닫힙니다. 닫힌 호는 실제로 타원으로 변형됩니다. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

지정된 변환을 도형에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 적용할 변환입니다. |

