---
title: "IntRange 类"
type: docs
weight: 2340
url: /zh/python-net/aspose.psd/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IntRange

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | 初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。 |
| [IntRange(start, count)](#IntRange_start_count_2) | 初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。 |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | 初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 范围 | int | 读/写 | 获取或设置范围。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | 从指定索引返回包含一个项的数组 |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | 获取从 start 开始的 int 元素的计数范围 |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 范围 | int | 范围。 |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

初始化一个新的 [IntRange](/psd/python-net/aspose.psd/intrange/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |
| 增量 | int | 增量。 |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

从指定索引返回包含一个项的数组

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 范围索引。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | int 数组 |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

获取从 start 开始的 int 元素的计数范围

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 起始 | int | 起始。 |
| 计数 | int | 计数。 |
| 增量 | int | 增量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| iter[int] | 项数组 |


