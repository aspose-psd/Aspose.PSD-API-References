---
title: PointF Class
type: docs
weight: 3480
url: /python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PointF()](#PointF__1) | Initializes a new instance of the PointF class |
| [PointF(x, y)](#PointF_x_y_2) | Initializes a new instance of the [PointF](/psd/python-net/aspose.psd/pointf/) structure with the specified coordinates. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | Gets a new instance of the [PointF](/psd/python-net/aspose.psd/pointf/) structure that has [PointF.x](/psd/python-net/aspose.psd/pointf/) and [PointF.y](/psd/python-net/aspose.psd/pointf/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [PointF](/psd/python-net/aspose.psd/pointf/) is empty. |
| x | float | r/w | Gets or sets the x-coordinate of this [PointF](/psd/python-net/aspose.psd/pointf/). |
| y | float | r/w | Gets or sets the y-coordinate of this [PointF](/psd/python-net/aspose.psd/pointf/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Translates a given [PointF](/psd/python-net/aspose.psd/pointf/) by the specified [Size](/psd/python-net/aspose.psd/size/). |
| [add(point, size)](#add_point_size_2) | Translates a given [PointF](/psd/python-net/aspose.psd/pointf/) by the specified [Size](/psd/python-net/aspose.psd/size/). |
| [subtract(point, size)](#subtract_point_size_3) | Translates a [PointF](/psd/python-net/aspose.psd/pointf/) by the negative of a specified size. |
| [subtract(point, size)](#subtract_point_size_4) | Translates a [PointF](/psd/python-net/aspose.psd/pointf/) by the negative of a specified size. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

Initializes a new instance of the PointF class

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

Initializes a new instance of the [PointF](/psd/python-net/aspose.psd/pointf/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The horizontal position of the point. |
| y | float | The vertical position of the point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Translates a given [PointF](/psd/python-net/aspose.psd/pointf/) by the specified [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to translate. |
| size | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | The translated [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Translates a given [PointF](/psd/python-net/aspose.psd/pointf/) by the specified [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to translate. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [Size](/psd/python-net/aspose.psd/size/) that specifies the numbers to add to the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | The translated [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

Translates a [PointF](/psd/python-net/aspose.psd/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to translate. |
| size | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | The translated [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

Translates a [PointF](/psd/python-net/aspose.psd/pointf/) by the negative of a specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to translate. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [Size](/psd/python-net/aspose.psd/size/) that specifies the numbers to subtract from the coordinates of <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | The translated [PointF](/psd/python-net/aspose.psd/pointf/). |


