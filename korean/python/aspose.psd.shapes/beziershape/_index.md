---
title: "BezierShape 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | 새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다. |
| [BezierShape(points)](#BezierShape_points_2) | 새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다. |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | 새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져옵니다. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 도형의 중심을 가져옵니다. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 끝 도형 점을 가져옵니다. |
| has_segments | bool | r | 도형에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| is_closed | bool | r/w | 도형이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | 곡선 점을 가져오거나 설정합니다. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 도형 세그먼트를 가져옵니다. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 시작 도형 점을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 객체의 경계를 가져옵니다. |
| reverse() | 이 도형의 포인트 순서를 반전시킵니다. |
| [transform(transform)](#transform_transform_3) | 지정된 변환을 도형에 적용합니다. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다.

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 포인트 배열. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

새로운 [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 포인트 배열. |
| is_closed | bool | 만약 <c>true</c> 로 설정하면 베지어 스플라인이 닫힙니다. |

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

