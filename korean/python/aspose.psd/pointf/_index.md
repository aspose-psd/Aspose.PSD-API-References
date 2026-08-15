---
title: "PointF 클래스"
type: docs
weight: 3550
url: /ko/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PointF()](#PointF__1) | 새로운 PointF 클래스 인스턴스를 초기화합니다. |
| [PointF(x, y)](#PointF_x_y_2) | 지정된 좌표를 사용하여 새로운 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | 새로운 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 인스턴스를 가져오며, 이 구조체는 [PointF.x](/psd/python-net/aspose.psd/pointf/) 및 [PointF.y](/psd/python-net/aspose.psd/pointf/) 값이 0으로 설정됩니다. |
| is_empty | bool | r | 이 [PointF](/psd/python-net/aspose.psd/pointf/)가 비어 있는지 여부를 나타내는 값을 가져옵니다. |
| x | float | r/w | 이 [PointF](/psd/python-net/aspose.psd/pointf/)의 x 좌표를 가져오거나 설정합니다. |
| y | float | r/w | 이 [PointF](/psd/python-net/aspose.psd/pointf/)의 y 좌표를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 주어진 [PointF](/psd/python-net/aspose.psd/pointf/)를 지정된 [Size](/psd/python-net/aspose.psd/size/)만큼 변환합니다. |
| [add(point, size)](#add_point_size_2) | 주어진 [PointF](/psd/python-net/aspose.psd/pointf/)를 지정된 [Size](/psd/python-net/aspose.psd/size/)만큼 변환합니다. |
| [subtract(point, size)](#subtract_point_size_3) | 지정된 크기의 음수만큼 [PointF](/psd/python-net/aspose.psd/pointf/)를 변환합니다. |
| [subtract(point, size)](#subtract_point_size_4) | 지정된 크기의 음수만큼 [PointF](/psd/python-net/aspose.psd/pointf/)를 변환합니다. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

새로운 PointF 클래스 인스턴스를 초기화합니다.

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

지정된 좌표를 사용하여 새로운 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 점의 수평 위치. |
| y | float | 점의 수직 위치. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

주어진 [PointF](/psd/python-net/aspose.psd/pointf/)를 지정된 [Size](/psd/python-net/aspose.psd/size/)만큼 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 번역할 [PointF](/psd/python-net/aspose.psd/pointf/) |
| size | [Size](/psd/python-net/aspose.psd/size) | 좌표에 <paramref name="point" />를 추가하기 위한 숫자를 지정하는 [Size](/psd/python-net/aspose.psd/size/) |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 번역된 [PointF](/psd/python-net/aspose.psd/pointf/) |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

주어진 [PointF](/psd/python-net/aspose.psd/pointf/)를 지정된 [Size](/psd/python-net/aspose.psd/size/)만큼 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 번역할 [PointF](/psd/python-net/aspose.psd/pointf/) |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 좌표에 <paramref name="point" />를 추가하기 위한 숫자를 지정하는 [Size](/psd/python-net/aspose.psd/size/) |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 번역된 [PointF](/psd/python-net/aspose.psd/pointf/) |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

지정된 크기의 음수만큼 [PointF](/psd/python-net/aspose.psd/pointf/)를 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 번역할 [PointF](/psd/python-net/aspose.psd/pointf/) |
| size | [Size](/psd/python-net/aspose.psd/size) | 좌표에서 <paramref name="point" />를 빼기 위한 숫자를 지정하는 [Size](/psd/python-net/aspose.psd/size/) |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 번역된 [PointF](/psd/python-net/aspose.psd/pointf/) |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

지정된 크기의 음수만큼 [PointF](/psd/python-net/aspose.psd/pointf/)를 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 번역할 [PointF](/psd/python-net/aspose.psd/pointf/) |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 좌표에서 <paramref name="point" />를 빼기 위한 숫자를 지정하는 [Size](/psd/python-net/aspose.psd/size/) |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 번역된 [PointF](/psd/python-net/aspose.psd/pointf/) |


