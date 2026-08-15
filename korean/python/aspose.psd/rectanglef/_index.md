---
title: "RectangleF 클래스"
type: docs
weight: 3830
url: /ko/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | RectangleF 클래스의 새 인스턴스를 초기화합니다. |
| [RectangleF(location, size)](#RectangleF_location_size_2) | 지정된 위치와 크기로 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 새 인스턴스를 초기화합니다. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | 지정된 위치와 크기로 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bottom | float | r/w | 이 [RectangleF] 구조의 [RectangleF.y]와 [RectangleF.height]의 합인 y좌표를 가져오거나 설정합니다. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | x, y, width 및 height 값이 0으로 설정된 새로운 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 인스턴스를 가져옵니다. |
| height | float | r/w | 이 [RectangleF] 구조의 높이를 가져오거나 설정합니다. |
| is_empty | bool | r | 이 [RectangleF] 구조의 [RectangleF.width] 또는 [RectangleF.height] 속성이 0인지 여부를 나타내는 값을 가져옵니다. |
| left | float | r/w | 이 [RectangleF] 구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | 이 [RectangleF] 구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다. |
| right | float | r/w | 이 [RectangleF] 구조의 [RectangleF.x]와 [RectangleF.width]의 합인 x좌표를 가져오거나 설정합니다. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | 이 [RectangleF] 구조의 크기를 가져오거나 설정합니다. |
| top | float | r/w | 이 [RectangleF] 구조의 상단 가장자리 y좌표를 가져오거나 설정합니다. |
| width | float | r/w | 이 [RectangleF] 구조의 너비를 가져오거나 설정합니다. |
| x | float | r/w | 이 [RectangleF] 구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다. |
| y | float | r/w | 이 [RectangleF] 구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [contains(point)](#contains_point_1) | 지정된 점이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 내에 포함되는지 여부를 판단합니다. |
| [contains(rect)](#contains_rect_2) | 이 <paramref name="rect" /> 로 표시된 직사각형 영역이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 완전히 포함되는지 결정합니다. |
| [contains(x, y)](#contains_x_y_3) | 지정된 점이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 내에 포함되는지 여부를 판단합니다. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | 지정된 위치에 왼쪽 위 모서리와 오른쪽 아래 모서리를 갖는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 생성합니다. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | 지정된 두 점으로부터 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. 생성된 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 두 꼭짓점은 전달된 <paramref name="point1" /> 및 <paramref name="point2" />와 동일합니다. 일반적으로 이는 서로 반대되는 꼭짓점이 됩니다. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 직사각형은 수정되지 않은 채로 남습니다. |
| [inflate(size)](#inflate_size_7) | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 지정된 양만큼 확대합니다. |
| [inflate(x, y)](#inflate_x_y_8) | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 지정된 양만큼 확대합니다. |
| [intersect(a, b)](#intersect_a_b_9) | 두 직사각형의 교차점을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 반환합니다. 교차점이 없으면 빈 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)이 반환됩니다. |
| [intersect(rect)](#intersect_rect_10) | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교차점으로 교체합니다. |
| [intersects_with(rect)](#intersects_with_rect_11) | 이 직사각형이 <paramref name="rect" />와 교차하는지 여부를 결정합니다. |
| normalize() | 직사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위쪽이 아래쪽보다 작도록 하여 직사각형을 정규화합니다. |
| [offset(pos)](#offset_pos_12) | 이 직사각형의 위치를 지정된 양만큼 조정합니다. |
| [offset(x, y)](#offset_x_y_13) | 이 직사각형의 위치를 지정된 양만큼 조정합니다. |
| [union(a, b)](#union_a_b_14) | 두 직사각형의 합집합을 포함할 수 있는 가장 작은 세 번째 직사각형을 생성합니다. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

RectangleF 클래스의 새 인스턴스를 초기화합니다.

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

지정된 위치와 크기로 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | 직사각형 영역의 왼쪽 위 모서리를 나타내는 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 직사각형 영역의 너비와 높이를 나타내는 [SizeF](/psd/python-net/aspose.psd/sizef/)입니다. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

지정된 위치와 크기로 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 직사각형 왼쪽 위 모서리의 x 좌표입니다. |
| y | float | 직사각형 왼쪽 위 모서리의 y 좌표입니다. |
| width | float | 직사각형의 너비입니다. |
| 높이 | float | 직사각형의 높이입니다. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

지정된 점이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 내에 포함되는지 여부를 판단합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 <paramref name="point" /> 매개변수로 표시된 점이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

이 <paramref name="rect" /> 로 표시된 직사각형 영역이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에 완전히 포함되는지 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 테스트할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 <paramref name="rect" /> 로 표시된 직사각형 영역이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 로 표시된 직사각형 영역에 완전히 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

지정된 점이 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 내에 포함되는지 여부를 판단합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | This method returns true if the point defined by <paramref name=\"x\" /> and <paramref name=\"y\" /> is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure; otherwise false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

지정된 위치에 왼쪽 위 모서리와 오른쪽 아래 모서리를 갖는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| left | float | 직사각형 영역의 왼쪽 위 모서리의 x 좌표. |
| top | float | 직사각형 영역의 왼쪽 위 모서리의 y 좌표. |
| right | float | 직사각형 영역의 오른쪽 아래 모서리의 x 좌표. |
| 하단 | float | 직사각형 영역의 오른쪽 아래 모서리의 y 좌표. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 메서드가 생성하는 새로운 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

지정된 두 점으로부터 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. 생성된 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 두 꼭짓점은 전달된 <paramref name="point1" /> 및 <paramref name="point2" />와 동일합니다. 일반적으로 이는 서로 반대되는 꼭짓점이 됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 새 직사각형에 대한 첫 번째 [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 새 직사각형에 대한 두 번째 [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 새로 생성된 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 확대된 복사본을 생성하고 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 직사각형은 수정되지 않은 채로 남습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 복사될 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). 이 직사각형은 수정되지 않습니다. |
| x | float | 직사각형 복사본을 가로 방향으로 확장할 양. |
| y | float | 직사각형 복사본을 세로 방향으로 확장할 양. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 확장된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)을 지정된 양만큼 확대합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 이 직사각형을 확장할 양. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 지정된 양만큼 확대합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 가로 방향으로 확장할 양. |
| y | float | 이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 세로 방향으로 확장할 양. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

두 직사각형의 교차점을 나타내는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 반환합니다. 교차점이 없으면 빈 [RectangleF](/psd/python-net/aspose.psd/rectanglef/)이 반환됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 첫 번째 교차할 직사각형. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 두 번째 교차할 직사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 두 지정된 직사각형의 겹친 영역을 나타내는 크기를 가진 세 번째 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

이 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교차점으로 교체합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 교차할 직사각형. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

이 직사각형이 <paramref name="rect" />와 교차하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 테스트할 직사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 교차가 하나라도 있으면 true를 반환합니다. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

이 직사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | 위치를 오프셋할 양. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

이 직사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 위치를 가로 방향으로 오프셋할 양. |
| y | float | 위치를 세로 방향으로 오프셋할 양. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

두 직사각형의 합집합을 포함할 수 있는 가장 작은 세 번째 직사각형을 생성합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 첫 번째 사각형을 합치기 위해. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 두 번째 사각형을 합치기 위해. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 두 개의 사각형이 합쳐져 형성된 합집합을 포함하는 세 번째 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |


