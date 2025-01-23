---
title: Point Class
type: docs
weight: 3530
url: /python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Point()](#Point__1) | Initializes a new instance of the Point class |
| [Point(dw)](#Point_dw_2) | Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure using coordinates specified by an integer value. |
| [Point(size)](#Point_size_3) | Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure from the [Size](/psd/python-net/aspose.psd/size/) structure. |
| [Point(x, y)](#Point_x_y_4) | Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure with the specified coordinates. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Gets a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure that has [Point.x](/psd/python-net/aspose.psd/point/) and [Point.y](/psd/python-net/aspose.psd/point/) values set to zero. |
| is_empty | bool | r | Gets a value indicating whether this [Point](/psd/python-net/aspose.psd/point/) is empty. |
| x | int | r/w | Gets or sets the x-coordinate of this [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Gets or sets the y-coordinate of this [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Adds the specified [Size](/psd/python-net/aspose.psd/size/) to the specified [Point](/psd/python-net/aspose.psd/point/). |
| [ceiling(point)](#ceiling_point_2) | Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) by rounding the values of the [PointF](/psd/python-net/aspose.psd/pointf/) to the next higher integer values. |
| [offset(dx, dy)](#offset_dx_dy_3) | Translates this [Point](/psd/python-net/aspose.psd/point/) by the specified amount. |
| [offset(point)](#offset_point_4) | Translates this [Point](/psd/python-net/aspose.psd/point/) by the specified [Point](/psd/python-net/aspose.psd/point/). |
| [round(point)](#round_point_5) | Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) object by rounding the [Point](/psd/python-net/aspose.psd/point/) values to the nearest integer. |
| [subtract(point, size)](#subtract_point_size_6) | Returns the result of subtracting specified [Size](/psd/python-net/aspose.psd/size/) from the specified [Point](/psd/python-net/aspose.psd/point/). |
| [truncate(point)](#truncate_point_7) | Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) by truncating the values of the [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initializes a new instance of the Point class

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure using coordinates specified by an integer value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dw | int | A 32-bit integer that specifies the coordinates for the new point. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure from the [Size](/psd/python-net/aspose.psd/size/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Contains the new point coordinates. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initializes a new instance of the [Point](/psd/python-net/aspose.psd/point/) structure with the specified coordinates.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal position of the point. |
| y | int | The vertical position of the point. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Adds the specified [Size](/psd/python-net/aspose.psd/size/) to the specified [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) to add to. |
| size | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) to add to the <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) that is the result of the addition operation. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) by rounding the values of the [PointF](/psd/python-net/aspose.psd/pointf/) to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) this method converts to. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Translates this [Point](/psd/python-net/aspose.psd/point/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | int | The amount to offset the x-coordinate. |
| dy | int | The amount to offset the y-coordinate. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Translates this [Point](/psd/python-net/aspose.psd/point/) by the specified [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) used to offset this [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) object by rounding the [Point](/psd/python-net/aspose.psd/point/) values to the nearest integer.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) this method converts to. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Returns the result of subtracting specified [Size](/psd/python-net/aspose.psd/size/) from the specified [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) to be subtracted from. |
| size | [Size](/psd/python-net/aspose.psd/size) | The [Size](/psd/python-net/aspose.psd/size/) to subtract from the <paramref name="point" />. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) that is the result of the subtraction operation. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Converts the specified [PointF](/psd/python-net/aspose.psd/pointf/) to a [Point](/psd/python-net/aspose.psd/point/) by truncating the values of the [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to convert. |

**Returns**

| Type | Description |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) this method converts to. |


