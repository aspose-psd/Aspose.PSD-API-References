---
title: "Rectangle 클래스"
type: docs
weight: 3810
url: /ko/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Rectangle 클래스의 새 인스턴스를 초기화합니다 |
| [Rectangle(location, size)](#Rectangle_location_size_2) | 지정된 위치와 크기로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 새 인스턴스를 초기화합니다 |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | 지정된 위치와 크기로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bottom | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) 및 [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) 속성 값의 합인 y좌표를 가져오거나 설정합니다 |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) 및 [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) 값이 0으로 설정된 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조 인스턴스를 가져옵니다 |
| height | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 높이를 가져오거나 설정합니다 |
| is_empty | bool | r | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 모든 숫자 속성이 0값인지 여부를 나타내는 값을 가져옵니다 |
| left | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 가장자리 x좌표를 가져오거나 설정합니다 |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 위 모서리 좌표를 가져오거나 설정합니다 |
| right | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) 및 [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) 속성 값의 합인 x좌표를 가져오거나 설정합니다 |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 크기를 가져오거나 설정합니다 |
| top | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 상단 가장자리 y좌표를 가져오거나 설정합니다 |
| width | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 너비를 가져오거나 설정합니다 |
| x | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 위 모서리 x좌표를 가져오거나 설정합니다 |
| y | int | r/w | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 위 모서리 y좌표를 가져오거나 설정합니다 |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 변환하며, [RectangleF] 값들을 올림하여 정수값으로 만듭니다 |
| [contains(point)](#contains_point_2) | 지정된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되는지 확인합니다 |
| [contains(rect)](#contains_rect_3) | <paramref name="rect" /> 로 표시된 직사각형 영역이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 완전히 포함되는지 확인합니다 |
| [contains(x, y)](#contains_x_y_4) | 지정된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되는지 확인합니다 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | 지정된 가장자리 위치로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 생성합니다 |
| [from_points(point1, point2)](#from_points_point1_point2_6) | 지정된 두 점으로부터 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. 생성된 [Rectangle]의 두 꼭짓점은 전달된 <paramref name="point1" />와 <paramref name="point2" />와 동일합니다. 일반적으로 이는 반대 꼭짓점이 됩니다. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | 지정된 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 확대된 복사본을 생성하여 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조는 변경되지 않습니다. |
| [inflate(size)](#inflate_size_8) | 지정된 양만큼 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 확장합니다. |
| [inflate(width, height)](#inflate_width_height_9) | 지정된 양만큼 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 확장합니다. |
| [intersect(a, b)](#intersect_a_b_10) | 두 개의 다른 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 교차점을 나타내는 세 번째 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 반환합니다. 교차점이 없으면 빈 [Rectangle](/psd/python-net/aspose.psd/rectangle/)이 반환됩니다. |
| [intersect(rect)](#intersect_rect_11) | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 자체와 지정된 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 교차점으로 교체합니다. |
| [intersects_with(rect)](#intersects_with_rect_12) | 이 직사각형이 <paramref name="rect" />와 교차하는지 여부를 결정합니다. |
| normalize() | 직사각형의 너비와 높이를 양수로 만들고, 왼쪽이 오른쪽보다 작으며 위쪽이 아래쪽보다 작도록 하여 직사각형을 정규화합니다. |
| [offset(pos)](#offset_pos_13) | 이 직사각형의 위치를 지정된 양만큼 조정합니다. |
| [offset(x, y)](#offset_x_y_14) | 이 직사각형의 위치를 지정된 양만큼 조정합니다. |
| [round(value)](#round_value_15) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 값을 가장 가까운 정수로 반올림하여 [Rectangle](/psd/python-net/aspose.psd/rectangle/)으로 변환합니다. |
| [truncate(value)](#truncate_value_16) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 값을 잘라내어 [Rectangle](/psd/python-net/aspose.psd/rectangle/)으로 변환합니다. |
| [union(a, b)](#union_a_b_17) | 두 개의 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 합집합을 포함하는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 가져옵니다. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Rectangle 클래스의 새 인스턴스를 초기화합니다

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

지정된 위치와 크기로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | 직사각형 영역의 왼쪽 위 모서리를 나타내는 [Point](/psd/python-net/aspose.psd/point/)입니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | 직사각형 영역의 너비와 높이를 나타내는 [Size](/psd/python-net/aspose.psd/size/)입니다. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

지정된 위치와 크기로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 직사각형 왼쪽 위 모서리의 x 좌표입니다. |
| y | int | 직사각형 왼쪽 위 모서리의 y 좌표입니다. |
| width | int | 직사각형의 너비입니다. |
| 높이 | int | 직사각형의 높이입니다. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조를 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조로 변환하며, [RectangleF] 값들을 올림하여 정수값으로 만듭니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 변환할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 반환합니다. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

지정된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되는지 확인합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 테스트할 [Point](/psd/python-net/aspose.psd/point/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 <paramref name=\"point\" /> 로 표시된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

<paramref name="rect" /> 로 표시된 직사각형 영역이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 완전히 포함되는지 확인합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 테스트할 [Rectangle](/psd/python-net/aspose.psd/rectangle/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 <paramref name=\"rect\" /> 로 표시된 직사각형 영역이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 완전히 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

지정된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되는지 확인합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 <paramref name=\"x\" /> 및 <paramref name=\"y\" /> 로 정의된 점이 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조에 포함되어 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

지정된 가장자리 위치로 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 생성합니다

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| left | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 위 모서리의 x 좌표입니다. |
| top | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 왼쪽 위 모서리의 y 좌표입니다. |
| right | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 오른쪽 아래 모서리의 x 좌표입니다. |
| bottom | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 오른쪽 아래 모서리의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 메서드가 생성하는 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/)입니다. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

지정된 두 점으로부터 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 생성합니다. 생성된 [Rectangle]의 두 꼭짓점은 전달된 <paramref name="point1" />와 <paramref name="point2" />와 동일합니다. 일반적으로 이는 반대 꼭짓점이 됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 새 직사각형에 대한 첫 번째 [Point](/psd/python-net/aspose.psd/point/). |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 새 직사각형에 대한 두 번째 [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 새로 생성된 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

지정된 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 확대된 복사본을 생성하여 반환합니다. 복사본은 지정된 양만큼 확대됩니다. 원본 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조는 변경되지 않습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 시작할 [Rectangle](/psd/python-net/aspose.psd/rectangle/)입니다. 이 사각형은 수정되지 않습니다. |
| x | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 수평으로 확장할 양입니다. |
| y | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 수직으로 확장할 양입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 확장된 [Rectangle](/psd/python-net/aspose.psd/rectangle/)입니다. |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

지정된 양만큼 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 확장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | 이 직사각형을 확장할 양. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

지정된 양만큼 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 확장합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 수평으로 확장할 양입니다. |
| height | int | 이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 수직으로 확장할 양입니다. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

두 개의 다른 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 교차점을 나타내는 세 번째 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 반환합니다. 교차점이 없으면 빈 [Rectangle](/psd/python-net/aspose.psd/rectangle/)이 반환됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 첫 번째 교차할 직사각형. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 두 번째 교차할 직사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | <paramref name=\"a\" />와 <paramref name=\"b\" />의 교차점을 나타내는 [Rectangle](/psd/python-net/aspose.psd/rectangle/)입니다. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

이 [Rectangle](/psd/python-net/aspose.psd/rectangle/)을 자체와 지정된 [Rectangle](/psd/python-net/aspose.psd/rectangle/)의 교차점으로 교체합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 교차에 사용할 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

이 직사각형이 <paramref name="rect" />와 교차하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 테스트할 직사각형. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 이 메서드는 교차가 있으면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

이 직사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | 위치를 오프셋할 양. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

이 직사각형의 위치를 지정된 양만큼 조정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 수평 오프셋. |
| y | int | 수직 오프셋. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 값을 가장 가까운 정수로 반올림하여 [Rectangle](/psd/python-net/aspose.psd/rectangle/)으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 변환할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 값을 잘라내어 [Rectangle](/psd/python-net/aspose.psd/rectangle/)으로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 변환할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 새로운 [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

두 개의 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조의 합집합을 포함하는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 첫 번째 사각형을 합치기 위해. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 두 번째 사각형을 합치기 위해. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 두 개의 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조를 합친 영역을 경계하는 [Rectangle](/psd/python-net/aspose.psd/rectangle/) 구조. |


