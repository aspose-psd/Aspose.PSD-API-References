---
title: "Figure 클래스"
type: docs
weight: 1220
url: /ko/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Figure()](#Figure__1) | Figure 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져오거나 설정합니다. |
| is_closed | bool | r/w | 이 도형이 닫혀 있는지 여부를 나타내는 값을 가져오거나 설정합니다. 닫힌 도형은 첫 번째와 마지막 도형의 모양이 연속적인 경우에만 차이를 만듭니다.<br/>            첫 번째 모양의 첫 번째 점은 마지막 모양의 마지막 점에서 직선으로 연결됩니다.<br/>             |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 전체 도형 세그먼트를 가져옵니다. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | 도형 모양을 가져옵니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | 그림에 도형을 추가합니다. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | 그림에 여러 도형을 추가합니다. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | 객체의 경계를 가져옵니다. |
| [remove_shape(shape)](#remove_shape_shape_5) | 그림에서 도형을 제거합니다. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | 그림에서 여러 도형을 제거합니다. |
| reverse() | 이 그림의 도형 순서와 도형 포인트 순서를 반전시킵니다. |
| [transform(transform)](#transform_transform_7) | 지정된 변환을 도형에 적용합니다. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Figure 클래스의 새 인스턴스를 초기화합니다.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

그림에 도형을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 추가할 도형. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

그림에 여러 도형을 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 추가할 도형들. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

그림에서 도형을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 제거할 도형. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

그림에서 여러 도형을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 제거할 도형 범위. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

지정된 변환을 도형에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 적용할 변환입니다. |

