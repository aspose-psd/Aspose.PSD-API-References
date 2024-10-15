---
title: RectangleF Class
type: docs
weight: 3820
url: /python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initializes a new instance of the RectangleF class |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initializes a new instance of the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the specified location and size. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initializes a new instance of the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the specified location and size. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | float | r/w | Gets or sets the y-coordinate that is the sum of [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) and [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Gets a new instance of the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that has [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) and [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) values set to zero. |
| height | float | r/w | Gets or sets the height of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| is_empty | bool | r | Gets a value indicating whether the [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) or [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) property of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) has a value of zero. |
| left | float | r/w | Gets or sets the x-coordinate of the left edge of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Gets or sets the coordinates of the upper-left corner of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| right | float | r/w | Gets or sets the x-coordinate that is the sum of [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) and [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Gets or sets the size of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Gets or sets the y-coordinate of the top edge of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| width | float | r/w | Gets or sets the width of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| x | float | r/w | Gets or sets the x-coordinate of the upper-left corner of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| y | float | r/w | Gets or sets the y-coordinate of the upper-left corner of this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains(point)](#contains_point_1) | Determines if the specified point is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [contains(rect)](#contains_rect_2) | Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [contains(x, y)](#contains_x_y_3) | Determines if the specified point is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Creates a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with upper-left corner and lower-right corner at the specified locations. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Creates a new [Rectangle](/psd/python-net/aspose.psd/rectangle/) from two points specified. Two verticles of the created [Rectangle](/psd/python-net/aspose.psd/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Creates and returns an inflated copy of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified. |
| [inflate(size)](#inflate_size_7) | Inflates this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) by the specified amount. |
| [inflate(x, y)](#inflate_x_y_8) | Inflates this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure by the specified amount. |
| [intersect(a, b)](#intersect_a_b_9) | Returns a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/psd/python-net/aspose.psd/rectanglef/) is returned. |
| [intersect(rect)](#intersect_rect_10) | Replaces this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the intersection of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. |
| [intersects_with(rect)](#intersects_with_rect_11) | Determines if this rectangle intersects with <paramref name="rect" />. |
| normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [offset(pos)](#offset_pos_12) | Adjusts the location of this rectangle by the specified amount. |
| [offset(x, y)](#offset_x_y_13) | Adjusts the location of this rectangle by the specified amount. |
| [union(a, b)](#union_a_b_14) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initializes a new instance of the RectangleF class

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initializes a new instance of the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | A [PointF](/psd/python-net/aspose.psd/pointf/) that represents the upper-left corner of the rectangular region. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | A [SizeF](/psd/python-net/aspose.psd/sizef/) that represents the width and height of the rectangular region. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initializes a new instance of the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the upper-left corner of the rectangle. |
| y | float | The y-coordinate of the upper-left corner of the rectangle. |
| width | float | The width of the rectangle. |
| height | float | The height of the rectangle. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Determines if the specified point is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | The [PointF](/psd/python-net/aspose.psd/pointf/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by the <paramref name="point" /> parameter is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure; otherwise false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by <paramref name="rect" /> is entirely contained within the rectangular region represented by this [RectangleF](/psd/python-net/aspose.psd/rectanglef/); otherwise false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Determines if the specified point is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point defined by <paramref name="x" /> and <paramref name="y" /> is contained within this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure; otherwise false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Creates a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with upper-left corner and lower-right corner at the specified locations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left | float | The x-coordinate of the upper-left corner of the rectangular region. |
| top | float | The y-coordinate of the upper-left corner of the rectangular region. |
| right | float | The x-coordinate of the lower-right corner of the rectangular region. |
| bottom | float | The y-coordinate of the lower-right corner of the rectangular region. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The new [RectangleF](/psd/python-net/aspose.psd/rectanglef/) that this method creates. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Creates a new [Rectangle](/psd/python-net/aspose.psd/rectangle/) from two points specified. Two verticles of the created [Rectangle](/psd/python-net/aspose.psd/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | The first [Point](/psd/python-net/aspose.psd/point/) for the new rectangle. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | The second [Point](/psd/python-net/aspose.psd/point/) for the new rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A newly created [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Creates and returns an inflated copy of the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to be copied. This rectangle is not modified. |
| x | float | The amount to inflate the copy of the rectangle horizontally. |
| y | float | The amount to inflate the copy of the rectangle vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The inflated [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Inflates this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | The amount to inflate this rectangle. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Inflates this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The amount to inflate this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure horizontally. |
| y | float | The amount to inflate this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure vertically. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Returns a [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that represents the intersection of two rectangles. If there is no intersection, and empty [RectangleF](/psd/python-net/aspose.psd/rectanglef/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A first rectangle to intersect. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A third [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure the size of which represents the overlapped area of the two specified rectangles. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Replaces this [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure with the intersection of itself and the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rectangle to intersect. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Determines if this rectangle intersects with <paramref name="rect" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if there is any intersection. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | The amount to offset the location. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The amount to offset the location horizontally. |
| y | float | The amount to offset the location vertically. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Creates the smallest possible third rectangle that can contain both of two rectangles that form a union.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A first rectangle to union. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A second rectangle to union. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | A third [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure that contains both of the two rectangles that form the union. |


