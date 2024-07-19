---
title: SizeF Class
type: docs
weight: 4020
url: /python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initializes a new instance of the SizeF class |
| [SizeF(point)](#SizeF_point_2) | Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified dimensions. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Gets a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure that has [SizeF.width](/psd/python-net/aspose.psd/sizef/) and [SizeF.height](/psd/python-net/aspose.psd/sizef/) values set to zero. |
| height | float | r/w | Gets or sets the vertical component of this [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Gets a value indicating whether this [SizeF](/psd/python-net/aspose.psd/sizef/) has zero width and height. |
| width | float | r/w | Gets or sets the horizontal component of this [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Adds the width and height of one [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the width and height of another [SizeF](/psd/python-net/aspose.psd/sizef/) structure. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Subtracts the width and height of one [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the width and height of another [SizeF](/psd/python-net/aspose.psd/sizef/) structure. |
| [to_point_f()](#to_point_f__3) | Converts a [SizeF](/psd/python-net/aspose.psd/sizef/) to a [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Converts a [SizeF](/psd/python-net/aspose.psd/sizef/) to a [Size](/psd/python-net/aspose.psd/size/) structure with truncated size values. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initializes a new instance of the SizeF class

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) from which to initialize this [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) from which to create the new [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initializes a new instance of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the specified dimensions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | float | The width component of the new [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | The height component of the new [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Adds the width and height of one [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the width and height of another [SizeF](/psd/python-net/aspose.psd/sizef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | The first [SizeF](/psd/python-net/aspose.psd/sizef/) to add. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | The second [SizeF](/psd/python-net/aspose.psd/sizef/) to add. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | A [SizeF](/psd/python-net/aspose.psd/sizef/) structure that is the result of the addition operation. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Subtracts the width and height of one [SizeF](/psd/python-net/aspose.psd/sizef/) structure from the width and height of another [SizeF](/psd/python-net/aspose.psd/sizef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) structure on the left side of the subtraction operator. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) structure on the right side of the subtraction operator. |

**Returns**

| Type | Description |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) that is a result of the subtraction operation. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Converts a [SizeF](/psd/python-net/aspose.psd/sizef/) to a [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Type | Description |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Returns a [PointF](/psd/python-net/aspose.psd/pointf/) structure. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Converts a [SizeF](/psd/python-net/aspose.psd/sizef/) to a [Size](/psd/python-net/aspose.psd/size/) structure with truncated size values.

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Returns a [Size](/psd/python-net/aspose.psd/size/) structure. |


