---
title: "SizeF 类"
type: docs
weight: 4090
url: /zh/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | 初始化 SizeF 类的新实例 |
| [SizeF(point)](#SizeF_point_2) | 从指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。 |
| [SizeF(size)](#SizeF_size_3) | 从指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。 |
| [SizeF(width, height)](#SizeF_width_height_4) | 从指定的尺寸初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | 获取一个新的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构实例，其 [SizeF.width](/psd/python-net/aspose.psd/sizef/) 和 [SizeF.height](/psd/python-net/aspose.psd/sizef/) 值均为零。 |
| height | float | r/w | 获取或设置此 [SizeF](/psd/python-net/aspose.psd/sizef/) 的垂直分量。 |
| is_empty | bool | r | 获取一个值，指示此 [SizeF](/psd/python-net/aspose.psd/sizef/) 的宽度和高度是否为零。 |
| width | float | r/w | 获取或设置此 [SizeF](/psd/python-net/aspose.psd/sizef/) 的水平分量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | 将一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度加到另一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度上。 |
| [subtract(size1, size2)](#subtract_size1_size2_2) | 从另一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度中减去一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度。 |
| [to_point_f()](#to_point_f__3) | 将 [SizeF](/psd/python-net/aspose.psd/sizef/) 转换为 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| [to_size()](#to_size__4) | 将 [SizeF](/psd/python-net/aspose.psd/sizef/) 转换为具有截断尺寸值的 [Size](/psd/python-net/aspose.psd/size/) 结构。 |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

初始化 SizeF 类的新实例

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

从指定的 [PointF](/psd/python-net/aspose.psd/pointf/) 初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 用于初始化此 [SizeF](/psd/python-net/aspose.psd/sizef/) 的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

从指定的 [SizeF](/psd/python-net/aspose.psd/sizef/) 初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 用于创建新 [SizeF](/psd/python-net/aspose.psd/sizef/) 的 [SizeF](/psd/python-net/aspose.psd/sizef/)。 |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

从指定的尺寸初始化 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | float | 新 [SizeF](/psd/python-net/aspose.psd/sizef/) 的宽度分量。 |
| height | float | 新 [SizeF](/psd/python-net/aspose.psd/sizef/) 的高度分量。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

将一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度加到另一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度上。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 第一个要添加的 [SizeF](/psd/python-net/aspose.psd/sizef/)。 |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 第二个要添加的 [SizeF](/psd/python-net/aspose.psd/sizef/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构，是加法运算的结果。 |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

从另一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度中减去一个 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构的宽度和高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 减法运算符左侧的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构。 |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 减法运算符右侧的 [SizeF](/psd/python-net/aspose.psd/sizef/) 结构。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 减法运算的结果 [SizeF](/psd/python-net/aspose.psd/sizef/)。 |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

将 [SizeF](/psd/python-net/aspose.psd/sizef/) 转换为 [PointF](/psd/python-net/aspose.psd/pointf/)。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 返回一个 [PointF](/psd/python-net/aspose.psd/pointf/) 结构。 |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

将 [SizeF](/psd/python-net/aspose.psd/sizef/) 转换为具有截断尺寸值的 [Size](/psd/python-net/aspose.psd/size/) 结构。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | 返回一个 [Size](/psd/python-net/aspose.psd/size/) 结构。 |


