---
title: Size Class
type: docs
weight: 4020
url: /python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Size()](#Size__1) | Initializes a new instance of the Size class |
| [Size(point)](#Size_point_2) | Initializes a new instance of the [Size](/psd/python-net/aspose.psd/size/) structure from the specified [Point](/psd/python-net/aspose.psd/point/). |
| [Size(width, height)](#Size_width_height_3) | Initializes a new instance of the [Size](/psd/python-net/aspose.psd/size/) structure from the specified dimensions. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Gets a new instance of the [Size](/psd/python-net/aspose.psd/size/) structure that has [Size.width](/psd/python-net/aspose.psd/size/) and [Size.height](/psd/python-net/aspose.psd/size/) values set to zero. |
| height | int | r/w | Gets or sets the vertical component of this [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Gets a value indicating whether this [Size](/psd/python-net/aspose.psd/size/) has width and height of 0. |
| width | int | r/w | Gets or sets the horizontal component of this [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Adds the width and height of one [Size](/psd/python-net/aspose.psd/size/) structure to the width and height of another [Size](/psd/python-net/aspose.psd/size/) structure. |
| [ceiling(size)](#ceiling_size_2) | Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by rounding the values of the [Size](/psd/python-net/aspose.psd/size/) structure to the next higher integer values. |
| [round(size)](#round_size_3) | Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by rounding the values of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the nearest integer values. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtracts the width and height of one [Size](/psd/python-net/aspose.psd/size/) structure from the width and height of another [Size](/psd/python-net/aspose.psd/size/) structure. |
| [truncate(size)](#truncate_size_5) | Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by truncating the values of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the next lower integer values. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initializes a new instance of the Size class

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initializes a new instance of the [Size](/psd/python-net/aspose.psd/size/) structure from the specified [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) from which to initialize this [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initializes a new instance of the [Size](/psd/python-net/aspose.psd/size/) structure from the specified dimensions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width component of the new [Size](/psd/python-net/aspose.psd/size/). |
| height | int | The height component of the new [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Adds the width and height of one [Size](/psd/python-net/aspose.psd/size/) structure to the width and height of another [Size](/psd/python-net/aspose.psd/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | The first [Size](/psd/python-net/aspose.psd/size/) to add. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | The second [Size](/psd/python-net/aspose.psd/size/) to add. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | A [Size](/psd/python-net/aspose.psd/size/) structure that is the result of the addition operation. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by rounding the values of the [Size](/psd/python-net/aspose.psd/size/) structure to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) structure this method converts to. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by rounding the values of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the nearest integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) structure this method converts to. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtracts the width and height of one [Size](/psd/python-net/aspose.psd/size/) structure from the width and height of another [Size](/psd/python-net/aspose.psd/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) structure on the left side of the subtraction operator. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) structure on the right side of the subtraction operator. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) that is a result of the subtraction operation. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Converts the specified [SizeF](/psd/python-net/aspose.psd/sizef/) structure to a [Size](/psd/python-net/aspose.psd/size/) structure by truncating the values of the [SizeF](/psd/python-net/aspose.psd/sizef/) structure to the next lower integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The [SizeF](/psd/python-net/aspose.psd/sizef/) structure to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) structure this method converts to. |


