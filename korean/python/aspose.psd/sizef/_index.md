---
title: "SizeF 클래스"
type: docs
weight: 4090
url: /ko/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [SizeF()](#SizeF__1) | 새로운 SizeF 클래스 인스턴스를 초기화합니다 |
| [SizeF(point)](#SizeF_point_2) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/)에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다. |
| [SizeF(size)](#SizeF_size_3) | 지정된 [SizeF](/psd/python-net/aspose.psd/sizef/)에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다. |
| [SizeF(width, height)](#SizeF_width_height_4) | 지정된 차원에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | [SizeF.width](/psd/python-net/aspose.psd/sizef/)와 [SizeF.height](/psd/python-net/aspose.psd/sizef/) 값이 0으로 설정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 가져옵니다. |
| height | float | r/w | 이 [SizeF](/psd/python-net/aspose.psd/sizef/)의 수직 구성 요소를 가져오거나 설정합니다. |
| is_empty | bool | r | 이 [SizeF](/psd/python-net/aspose.psd/sizef/)의 너비와 높이가 0인지 여부를 나타내는 값을 가져옵니다. |
| width | float | r/w | 이 [SizeF](/psd/python-net/aspose.psd/sizef/)의 수평 구성 요소를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 한 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이를 다른 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이에 더합니다. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | 한 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이를 다른 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이에서 빼습니다. |
| [to_point_f()](#to_point_f__3) | [SizeF](/psd/python-net/aspose.psd/sizef/)를 [PointF](/psd/python-net/aspose.psd/pointf/)로 변환합니다. |
| [to_size()](#to_size__4) | [SizeF](/psd/python-net/aspose.psd/sizef/)를 잘린 크기 값으로 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환합니다. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

새로운 SizeF 클래스 인스턴스를 초기화합니다

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/)에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 이 [SizeF](/psd/python-net/aspose.psd/sizef/)를 초기화할 [PointF](/psd/python-net/aspose.psd/pointf/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

지정된 [SizeF](/psd/python-net/aspose.psd/sizef/)에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 새로운 [SizeF](/psd/python-net/aspose.psd/sizef/)를 만들기 위한 [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

지정된 차원에서 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | float | 새로운 [SizeF](/psd/python-net/aspose.psd/sizef/)의 너비 구성 요소. |
| height | float | 새로운 [SizeF](/psd/python-net/aspose.psd/sizef/)의 높이 구성 요소. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

한 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이를 다른 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이에 더합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 첫 번째 추가할 [SizeF](/psd/python-net/aspose.psd/sizef/). |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 두 번째 추가할 [SizeF](/psd/python-net/aspose.psd/sizef/). |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 덧셈 연산의 결과인 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조체. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

한 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이를 다른 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 너비와 높이에서 빼습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 뺄셈 연산자 왼쪽에 있는 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조체. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 뺄셈 연산자 오른쪽에 있는 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 뺄셈 연산의 결과인 [SizeF](/psd/python-net/aspose.psd/sizef/). |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/)를 [PointF](/psd/python-net/aspose.psd/pointf/)로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 구조체를 반환합니다. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/)를 잘린 크기 값으로 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) 구조체를 반환합니다. |


