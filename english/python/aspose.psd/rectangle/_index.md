---
title: Rectangle Class
type: docs
weight: 3740
url: /python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initializes a new instance of the Rectangle class |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initializes a new instance of the [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified location and size. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initializes a new instance of the [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified location and size. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Gets or sets the y-coordinate that is the sum of the [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) and [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) property values of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Gets a new instance of the [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that has [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) and [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) values set to zero. |
| height | int | r/w | Gets or sets the height of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| is_empty | bool | r | Gets a value indicating whether all numeric properties of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) have values of zero. |
| left | int | r/w | Gets or sets the x-coordinate of the left edge of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Gets or sets the coordinates of the upper-left corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| right | int | r/w | Gets or sets the x-coordinate that is the sum of [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) and [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) property values of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Gets or sets the size of this [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Gets or sets the y-coordinate of the top edge of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| width | int | r/w | Gets or sets the width of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| x | int | r/w | Gets or sets the x-coordinate of the upper-left corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| y | int | r/w | Gets or sets the y-coordinate of the upper-left corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure by rounding the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values to the next higher integer values. |
| [contains(point)](#contains_point_2) | Determines if the specified point is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| [contains(rect)](#contains_rect_3) | Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| [contains(x, y)](#contains_x_y_4) | Determines if the specified point is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Creates a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified edge locations. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Creates a new [Rectangle](/psd/python-net/aspose.psd/rectangle/) from two points specified. Two verticales of the created [Rectangle](/psd/python-net/aspose.psd/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Creates and returns an inflated copy of the specified [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure remains unmodified. |
| [inflate(size)](#inflate_size_8) | Inflates this [Rectangle](/psd/python-net/aspose.psd/rectangle/) by the specified amount. |
| [inflate(width, height)](#inflate_width_height_9) | Inflates this [Rectangle](/psd/python-net/aspose.psd/rectangle/) by the specified amount. |
| [intersect(a, b)](#intersect_a_b_10) | Returns a third [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the intersection of two other [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. If there is no intersection, an empty [Rectangle](/psd/python-net/aspose.psd/rectangle/) is returned. |
| [intersect(rect)](#intersect_rect_11) | Replaces this [Rectangle](/psd/python-net/aspose.psd/rectangle/) with the intersection of itself and the specified [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Determines if this rectangle intersects with <paramref name="rect" />. |
| normalize() | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [offset(pos)](#offset_pos_13) | Adjusts the location of this rectangle by the specified amount. |
| [offset(x, y)](#offset_x_y_14) | Adjusts the location of this rectangle by the specified amount. |
| [round(value)](#round_value_15) | Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) by rounding the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values to the nearest integer values. |
| [truncate(value)](#truncate_value_16) | Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) by truncating the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values. |
| [union(a, b)](#union_a_b_17) | Gets a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that contains the union of two [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initializes a new instance of the Rectangle class

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initializes a new instance of the [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | A [Point](/psd/python-net/aspose.psd/point/) that represents the upper-left corner of the rectangular region. |
| size | [Size](/psd/python-net/aspose.psd/size) | A [Size](/psd/python-net/aspose.psd/size/) that represents the width and height of the rectangular region. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initializes a new instance of the [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified location and size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the upper-left corner of the rectangle. |
| y | int | The y-coordinate of the upper-left corner of the rectangle. |
| width | int | The width of the rectangle. |
| height | int | The height of the rectangle. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure by rounding the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values to the next higher integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structure to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Returns a [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Determines if the specified point is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | The [Point](/psd/python-net/aspose.psd/point/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point represented by <paramref name="point" /> is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure; otherwise false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Determines if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [Rectangle](/psd/python-net/aspose.psd/rectangle/) to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the rectangular region represented by <paramref name="rect" /> is entirely contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure; otherwise false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Determines if the specified point is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if the point defined by <paramref name="x" /> and <paramref name="y" /> is contained within this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure; otherwise false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Creates a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure with the specified edge locations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left | int | The x-coordinate of the upper-left corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| top | int | The y-coordinate of the upper-left corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| right | int | The x-coordinate of the lower-right corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |
| bottom | int | The y-coordinate of the lower-right corner of this [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | The new [Rectangle](/psd/python-net/aspose.psd/rectangle/) that this method creates. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Creates a new [Rectangle](/psd/python-net/aspose.psd/rectangle/) from two points specified. Two verticales of the created [Rectangle](/psd/python-net/aspose.psd/rectangle/) will be equal to the passed <paramref name="point1" /> and <paramref name="point2" />. These would be typically the opposite vertices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | The first [Point](/psd/python-net/aspose.psd/point/) for the new rectangle. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | The second [Point](/psd/python-net/aspose.psd/point/) for the new rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | A newly created [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Creates and returns an inflated copy of the specified [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure. The copy is inflated by the specified amount. The original [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure remains unmodified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [Rectangle](/psd/python-net/aspose.psd/rectangle/) with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontally. |
| y | int | The amount to inflate this [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertically. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | The inflated [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Inflates this [Rectangle](/psd/python-net/aspose.psd/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | The amount to inflate this rectangle. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Inflates this [Rectangle](/psd/python-net/aspose.psd/rectangle/) by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The amount to inflate this [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontally. |
| height | int | The amount to inflate this [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertically. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Returns a third [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that represents the intersection of two other [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. If there is no intersection, an empty [Rectangle](/psd/python-net/aspose.psd/rectangle/) is returned.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A first rectangle to intersect. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A second rectangle to intersect. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [Rectangle](/psd/python-net/aspose.psd/rectangle/) that represents the intersection of <paramref name="a" /> and <paramref name="b" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Replaces this [Rectangle](/psd/python-net/aspose.psd/rectangle/) with the intersection of itself and the specified [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The [Rectangle](/psd/python-net/aspose.psd/rectangle/) with which to intersect. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Determines if this rectangle intersects with <paramref name="rect" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The rectangle to test. |

**Returns**

| Type | Description |
| :- | :- |
| bool | This method returns true if there is any intersection, otherwise false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Amount to offset the location. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Adjusts the location of this rectangle by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The horizontal offset. |
| y | int | The vertical offset. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) by rounding the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values to the nearest integer values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | A new [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Converts the specified [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to a [Rectangle](/psd/python-net/aspose.psd/rectangle/) by truncating the [RectangleF](/psd/python-net/aspose.psd/rectanglef/) values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | The [RectangleF](/psd/python-net/aspose.psd/rectanglef/) to be converted. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | A new [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Gets a [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that contains the union of two [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A first rectangle to union. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | A second rectangle to union. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | A [Rectangle](/psd/python-net/aspose.psd/rectangle/) structure that bounds the union of the two [Rectangle](/psd/python-net/aspose.psd/rectangle/) structures. |


