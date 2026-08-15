---
title: "IntRange 클래스"
type: docs
weight: 2340
url: /ko/python-net/aspose.psd/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IntRange

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | [IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다. |
| [IntRange(start, count)](#IntRange_start_count_2) | [IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다. |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | [IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| 범위 | int | r/w | 범위를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | 지정된 인덱스에서 하나의 항목 배열을 반환합니다. |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | 시작 위치에서 시작하는 int 요소들의 개수 범위를 가져옵니다. |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 범위 | int | 범위입니다. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 시작 | int | 시작입니다. |
| count | int | 개수입니다. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

[IntRange](/psd/python-net/aspose.psd/intrange/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 시작 | int | 시작입니다. |
| count | int | 개수입니다. |
| 델타 | int | 델타입니다. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

지정된 인덱스에서 하나의 항목 배열을 반환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | int | 범위 인덱스입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | int 배열 |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

시작 위치에서 시작하는 int 요소들의 개수 범위를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 시작 | int | 시작입니다. |
| count | int | 개수입니다. |
| 델타 | int | 델타입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| iter[int] | 항목 배열 |


