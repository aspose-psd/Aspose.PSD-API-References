---
title: "Size 类"
type: docs
weight: 4080
url: /zh/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | 初始化 Size 类的新实例 |
| [Size(point)](#Size_point_2) | 使用指定的 [Point](/psd/python-net/aspose.psd/point/) 初始化 [Size](/psd/python-net/aspose.psd/size/) 结构的新实例。 |
| [Size(width, height)](#Size_width_height_3) | 使用指定的尺寸初始化 [Size](/psd/python-net/aspose.psd/size/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | 获取一个新的 [Size](/psd/python-net/aspose.psd/size/) 结构实例，其 [Size.width](/psd/python-net/aspose.psd/size/) 和 [Size.height](/psd/python-net/aspose.psd/size/) 值设为零。 |
| height | int | r/w | 获取或设置此 [Size](/psd/python-net/aspose.psd/size/) 的垂直分量。 |
| is_empty | bool | r | 获取一个值，指示此 [Size](/psd/python-net/aspose.psd/size/) 的宽度和高度是否为 0。 |
| width | int | r/w | 获取或设置此 [Size](/psd/python-net/aspose.psd/size/) 的水平分量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 将一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度加到另一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度上。 |
| [ceiling(size)](#ceiling_size_2) | 通过将 [Size](/psd/python-net/aspose.psd/size/) 结构的值向上取整到下一个更高的整数，将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构。 |
| [round(size)](#round_size_3) | 将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构，通过将 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的值四舍五入到最近的整数值。 |
| [subtract(size1, size2)](#subtract_size1_size2_4) | 从另一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度中减去一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度。 |
| [truncate(size)](#truncate_size_5) | 将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构，通过将 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的值截断为下一个更低的整数值。 |


### Constructor: Size() {#Size__1}


```
 Size() 
```

初始化 Size 类的新实例

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

使用指定的 [Point](/psd/python-net/aspose.psd/point/) 初始化 [Size](/psd/python-net/aspose.psd/size/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 用于初始化此 [Size](/psd/python-net/aspose.psd/size/) 的 [Point](/psd/python-net/aspose.psd/point/)。 |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

使用指定的尺寸初始化 [Size](/psd/python-net/aspose.psd/size/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 新 [Size](/psd/python-net/aspose.psd/size/) 的宽度分量。 |
| height | int | 新 [Size](/psd/python-net/aspose.psd/size/) 的高度分量。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

将一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度加到另一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度上。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 要相加的第一个 [Size](/psd/python-net/aspose.psd/size/)。 |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 要相加的第二个 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 一个 [Size](/psd/python-net/aspose.psd/size/) 结构，为加法操作的结果。 |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

通过将 [Size](/psd/python-net/aspose.psd/size/) 结构的值向上取整到下一个更高的整数，将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 要转换的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 此方法转换为的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构，通过将 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的值四舍五入到最近的整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 要转换的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 此方法转换为的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

从另一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度中减去一个 [Size](/psd/python-net/aspose.psd/size/) 结构的宽度和高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | 减法运算符左侧的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |
| size2 | [Size](/psd/python-net/aspose.psd/size) | 减法运算符右侧的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 减法操作的结果 [Size](/psd/python-net/aspose.psd/size/)。 |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

将指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构转换为 [Size](/psd/python-net/aspose.psd/size/) 结构，通过将 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的值截断为下一个更低的整数值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 要转换的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 此方法转换为的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |


