---
title: "Point 클래스"
type: docs
weight: 3530
url: /ko/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Point()](#Point__1) | Point 클래스의 새 인스턴스를 초기화합니다. |
| [Point(dw)](#Point_dw_2) | 정수 값으로 지정된 좌표를 사용하여 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다. |
| [Point(size)](#Point_size_3) | [Size](/psd/python-net/aspose.psd/size/) 구조체에서 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다. |
| [Point(x, y)](#Point_x_y_4) | 지정된 좌표로 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | [Point.x](/psd/python-net/aspose.psd/point/) 및 [Point.y](/psd/python-net/aspose.psd/point/) 값이 0으로 설정된 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 가져옵니다. |
| is_empty | bool | r | 이 [Point](/psd/python-net/aspose.psd/point/)가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| x | int | r/w | 이 [Point](/psd/python-net/aspose.psd/point/)의 x 좌표를 가져오거나 설정합니다. |
| y | int | r/w | 이 [Point](/psd/python-net/aspose.psd/point/)의 y 좌표를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 지정된 [Size](/psd/python-net/aspose.psd/size/)을 지정된 [Point](/psd/python-net/aspose.psd/point/)에 더합니다. |
| [ceiling(point)](#ceiling_point_2) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/)의 값을 다음 높은 정수값으로 반올림하여 [Point](/psd/python-net/aspose.psd/point/)로 변환합니다. |
| [offset(dx, dy)](#offset_dx_dy_3) | 지정된 양만큼 이 [Point](/psd/python-net/aspose.psd/point/)를 평행 이동합니다. |
| [offset(point)](#offset_point_4) | 지정된 [Point](/psd/python-net/aspose.psd/point/)만큼 이 [Point](/psd/python-net/aspose.psd/point/)를 평행 이동합니다. |
| [round(point)](#round_point_5) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/)를 [Point](/psd/python-net/aspose.psd/point/) 객체로 변환하고, [Point](/psd/python-net/aspose.psd/point/) 값을 가장 가까운 정수로 반올림합니다. |
| [subtract(point, size)](#subtract_point_size_6) | 지정된 [Size](/psd/python-net/aspose.psd/size/)를 지정된 [Point](/psd/python-net/aspose.psd/point/)에서 빼는 결과를 반환합니다. |
| [truncate(point)](#truncate_point_7) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/)를 [Point](/psd/python-net/aspose.psd/point/)로 변환하고, [Point](/psd/python-net/aspose.psd/point/) 값을 절단합니다. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Point 클래스의 새 인스턴스를 초기화합니다.

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

정수 값으로 지정된 좌표를 사용하여 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dw | int | 새 점의 좌표를 지정하는 32비트 정수입니다. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

[Size](/psd/python-net/aspose.psd/size/) 구조체에서 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | 새 점 좌표를 포함합니다. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

지정된 좌표로 [Point](/psd/python-net/aspose.psd/point/) 구조체의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 점의 수평 위치. |
| y | int | 점의 수직 위치. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

지정된 [Size](/psd/python-net/aspose.psd/size/)을 지정된 [Point](/psd/python-net/aspose.psd/point/)에 더합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 추가할 [Point](/psd/python-net/aspose.psd/point/)입니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | 추가할 [Size](/psd/python-net/aspose.psd/size/)은 <paramref name=\"point\" />에 적용됩니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 덧셈 연산의 결과인 [Point](/psd/python-net/aspose.psd/point/)입니다. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/)의 값을 다음 높은 정수값으로 반올림하여 [Point](/psd/python-net/aspose.psd/point/)로 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 변환할 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 이 메서드가 변환하는 [Point](/psd/python-net/aspose.psd/point/)입니다. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

지정된 양만큼 이 [Point](/psd/python-net/aspose.psd/point/)를 평행 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | int | x 좌표를 오프셋할 양입니다. |
| dy | int | y 좌표를 오프셋할 양입니다. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

지정된 [Point](/psd/python-net/aspose.psd/point/)만큼 이 [Point](/psd/python-net/aspose.psd/point/)를 평행 이동합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 이 [Point](/psd/python-net/aspose.psd/point/)를 오프셋하는 데 사용되는 [Point](/psd/python-net/aspose.psd/point/)입니다. |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/)를 [Point](/psd/python-net/aspose.psd/point/) 객체로 변환하고, [Point](/psd/python-net/aspose.psd/point/) 값을 가장 가까운 정수로 반올림합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 변환할 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 이 메서드가 변환하는 [Point](/psd/python-net/aspose.psd/point/)입니다. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

지정된 [Size](/psd/python-net/aspose.psd/size/)를 지정된 [Point](/psd/python-net/aspose.psd/point/)에서 빼는 결과를 반환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 빼는 대상인 [Point](/psd/python-net/aspose.psd/point/)입니다. |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name=\"point\" />에서 빼는 [Size](/psd/python-net/aspose.psd/size/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 뺄셈 연산의 결과인 [Point](/psd/python-net/aspose.psd/point/)입니다. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/)를 [Point](/psd/python-net/aspose.psd/point/)로 변환하고, [Point](/psd/python-net/aspose.psd/point/) 값을 절단합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 변환할 [PointF](/psd/python-net/aspose.psd/pointf/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 이 메서드가 변환하는 [Point](/psd/python-net/aspose.psd/point/)입니다. |


