---
title: "PointF 类"
type: docs
weight: 3550
url: /zh/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PointF()](#PointF__1) | 初始化 PointF 类的新实例 |
| [PointF(x, y)](#PointF_x_y_2) | 使用指定坐标，初始化 [PointF](/psd/python-net/aspose.psd/pointf/) 结构的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | 获取一个新的 [PointF](/psd/python-net/aspose.psd/pointf/) 结构实例，其 [PointF.x](/psd/python-net/aspose.psd/pointf/) 和 [PointF.y](/psd/python-net/aspose.psd/pointf/) 的值均为零。 |
| is_empty | bool | r | 获取一个值，指示此 [PointF](/psd/python-net/aspose.psd/pointf/) 是否为空。 |
| x | float | r/w | 获取或设置此 [PointF](/psd/python-net/aspose.psd/pointf/) 的 x 坐标。 |
| y | float | r/w | 获取或设置此 [PointF](/psd/python-net/aspose.psd/pointf/) 的 y 坐标。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 按指定的 [Size](/psd/python-net/aspose.psd/size/) 平移给定的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| [add(point, size)](#add_point_size_2) | 按指定的 [Size](/psd/python-net/aspose.psd/size/) 平移给定的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| [subtract(point, size)](#subtract_point_size_3) | 按指定尺寸的相反方向平移 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| [subtract(point, size)](#subtract_point_size_4) | 按指定尺寸的相反方向平移 [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

初始化 PointF 类的新实例

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

使用指定坐标，初始化 [PointF](/psd/python-net/aspose.psd/pointf/) 结构的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | float | 点的水平位置。 |
| y | float | 点的垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

按指定的 [Size](/psd/python-net/aspose.psd/size/) 平移给定的 [PointF](/psd/python-net/aspose.psd/pointf/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 指定要加到 <paramref name=\"point\" /> 坐标的数字的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 已翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

按指定的 [Size](/psd/python-net/aspose.psd/size/) 平移给定的 [PointF](/psd/python-net/aspose.psd/pointf/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 指定要加到 <paramref name=\"point\" /> 坐标的数字的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 已翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/psd/python-net/aspose.psd/pointf/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 指定要从 <paramref name=\"point\" /> 坐标中减去的数字的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 已翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

按指定尺寸的相反方向平移 [PointF](/psd/python-net/aspose.psd/pointf/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 要翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 指定要从 <paramref name=\"point\" /> 坐标中减去的数字的 [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 已翻译的 [PointF](/psd/python-net/aspose.psd/pointf/)。 |


