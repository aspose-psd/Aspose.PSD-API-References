---
title: "RectangleProjectedShape 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.psd.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleProjectedShape

**Inheritance:** Shape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져옵니다. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 도형의 중심을 가져옵니다. |
| has_segments | bool | r | 도형에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 아래 사각형 점을 가져옵니다. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 위 사각형 점을 가져옵니다. |
| rectangle_height | double | r | 사각형 높이를 가져옵니다. |
| rectangle_width | double | r | 사각형 너비를 가져옵니다. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 아래 사각형 점을 가져옵니다. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 위 사각형 점을 가져옵니다. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 도형 세그먼트를 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 객체의 경계를 가져옵니다. |
| [transform(transform)](#transform_transform_3) | 지정된 변환을 도형에 적용합니다. |


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

