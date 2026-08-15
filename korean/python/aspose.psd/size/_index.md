---
title: "Size 클래스"
type: docs
weight: 4080
url: /ko/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Size()](#Size__1) | 새로운 Size 클래스 인스턴스를 초기화합니다. |
| [Size(point)](#Size_point_2) | 지정된 [Point](/psd/python-net/aspose.psd/point/)에서 새로운 [Size](/psd/python-net/aspose.psd/size/) 구조체 인스턴스를 초기화합니다. |
| [Size(width, height)](#Size_width_height_3) | 지정된 차원에서 새로운 [Size](/psd/python-net/aspose.psd/size/) 구조체 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | [Size.width](/psd/python-net/aspose.psd/size/)와 [Size.height](/psd/python-net/aspose.psd/size/) 값이 0으로 설정된 새로운 [Size](/psd/python-net/aspose.psd/size/) 구조체 인스턴스를 가져옵니다. |
| height | int | r/w | 이 [Size](/psd/python-net/aspose.psd/size/)의 수직 구성 요소를 가져오거나 설정합니다. |
| is_empty | bool | r | 이 [Size](/psd/python-net/aspose.psd/size/)의 width와 height가 0인지 여부를 나타내는 값을 가져옵니다. |
| width | int | r/w | 이 [Size](/psd/python-net/aspose.psd/size/)의 수평 구성 요소를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 한 [Size](/psd/python-net/aspose.psd/size/) 구조체의 width와 height를 다른 [Size](/psd/python-net/aspose.psd/size/) 구조체의 width와 height에 더합니다. |
| [ceiling(size)](#ceiling_size_2) | 지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조체를 [Size](/psd/python-net/aspose.psd/size/) 구조체로 변환합니다. 이때 [Size](/psd/python-net/aspose.psd/size/) 구조체의 값을 올림하여 다음 정수값으로 만듭니다. |
| [round(size)](#round_size_3) | 지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조를 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환하며, [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 값을 가장 가까운 정수값으로 반올림합니다. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | 한 [Size](/psd/python-net/aspose.psd/size/) 구조의 너비와 높이를 다른 [Size](/psd/python-net/aspose.psd/size/) 구조의 너비와 높이에서 빼습니다. |
| [truncate(size)](#truncate_size_5) | 지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조를 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환하며, [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 값을 다음 낮은 정수값으로 잘라냅니다. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

새로운 Size 클래스 인스턴스를 초기화합니다.

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

지정된 [Point](/psd/python-net/aspose.psd/point/)에서 새로운 [Size](/psd/python-net/aspose.psd/size/) 구조체 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 이 [Size](/psd/python-net/aspose.psd/size/)을 초기화할 [Point](/psd/python-net/aspose.psd/point/)입니다. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

지정된 차원에서 새로운 [Size](/psd/python-net/aspose.psd/size/) 구조체 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| width | int | 새로운 [Size](/psd/python-net/aspose.psd/size/)의 너비 구성 요소입니다. |
| height | int | 새로운 [Size](/psd/python-net/aspose.psd/size/)의 높이 구성 요소입니다. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

한 [Size](/psd/python-net/aspose.psd/size/) 구조체의 width와 height를 다른 [Size](/psd/python-net/aspose.psd/size/) 구조체의 width와 height에 더합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 첫 번째로 더할 [Size](/psd/python-net/aspose.psd/size/)입니다. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 두 번째로 더할 [Size](/psd/python-net/aspose.psd/size/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 덧셈 연산의 결과인 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조체를 [Size](/psd/python-net/aspose.psd/size/) 구조체로 변환합니다. 이때 [Size](/psd/python-net/aspose.psd/size/) 구조체의 값을 올림하여 다음 정수값으로 만듭니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 변환할 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 이 메서드가 변환하는 대상 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조를 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환하며, [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 값을 가장 가까운 정수값으로 반올림합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 변환할 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 이 메서드가 변환하는 대상 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

한 [Size](/psd/python-net/aspose.psd/size/) 구조의 너비와 높이를 다른 [Size](/psd/python-net/aspose.psd/size/) 구조의 너비와 높이에서 빼습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 뺄셈 연산자 왼쪽에 있는 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 뺄셈 연산자 오른쪽에 있는 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 뺄셈 연산의 결과인 [Size](/psd/python-net/aspose.psd/size/)입니다. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

지정된 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조를 [Size](/psd/python-net/aspose.psd/size/) 구조로 변환하며, [SizeF](/psd/python-net/aspose.psd/sizef/) 구조의 값을 다음 낮은 정수값으로 잘라냅니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 변환할 [SizeF](/psd/python-net/aspose.psd/sizef/) 구조입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 이 메서드가 변환하는 대상 [Size](/psd/python-net/aspose.psd/size/) 구조입니다. |


