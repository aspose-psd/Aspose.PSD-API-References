---
title: Rectangle
second_title: Aspose.PSD for Java API Reference
description: Stores a set of four integers that represent the location and size of a rectangle.
type: docs
weight: 88
url: /java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Stores a set of four integers that represent the location and size of a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initializes a new instance of the  com.aspose.psd.Rectangle  structure with the specified location and size. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Initializes a new instance of the  com.aspose.psd.Rectangle  structure with the specified location and size. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Converts the specified  com.aspose.psd.RectangleF  structure to a  com.aspose.psd.Rectangle  structure by rounding the  com.aspose.psd.RectangleF  values to the next higher integer values. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Determines if the specified point is contained within this  com.aspose.psd.Rectangle  structure. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Determines if the rectangular region represented by  rect  is entirely contained within this  com.aspose.psd.Rectangle  structure. |
| [contains(int x, int y)](#contains-int-int-) | Determines if the specified point is contained within this  com.aspose.psd.Rectangle  structure. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether  obj  is a  com.aspose.psd.Rectangle  structure with the same location and size of this  com.aspose.psd.Rectangle  structure. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Creates a  com.aspose.psd.Rectangle  structure with the specified edge locations. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Creates a new  Rectangle  from two points specified. |
| [getBottom()](#getBottom--) | Gets or sets the y-coordinate that is the sum of the  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  property values of this  com.aspose.psd.Rectangle  structure. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gets a new instance of the  com.aspose.psd.Rectangle  structure that has  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  and  com.aspose.psd.Rectangle.Height  values set to zero. |
| [getHeight()](#getHeight--) | Gets or sets the height of this  com.aspose.psd.Rectangle  structure. |
| [getLeft()](#getLeft--) | Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure. |
| [getLocation()](#getLocation--) | Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [getRight()](#getRight--) | Gets or sets the x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  property values of this  com.aspose.psd.Rectangle  structure. |
| [getSize()](#getSize--) | Gets or sets the size of this  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure. |
| [getWidth()](#getWidth--) | Gets the width of this  com.aspose.psd.Rectangle  structure. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [hashCode()](#hashCode--) | Returns the hash code for this  com.aspose.psd.Rectangle  structure. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Creates and returns an inflated copy of the specified  com.aspose.psd.Rectangle  structure. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Inflates this  com.aspose.psd.Rectangle  by the specified amount. |
| [inflate(int width, int height)](#inflate-int-int-) | Inflates this  com.aspose.psd.Rectangle  by the specified amount. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Replaces this  com.aspose.psd.Rectangle  with the intersection of itself and the specified  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Returns a third  com.aspose.psd.Rectangle  structure that represents the intersection of two other  com.aspose.psd.Rectangle  structures. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Determines if this rectangle intersects with  rect . |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether all numeric properties of this  com.aspose.psd.Rectangle  have values of zero. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Gets a value indicating whether this  Rectangle  is at least partially visible |
| [normalize()](#normalize--) | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Adjusts the location of this rectangle by the specified amount. |
| [offset(int x, int y)](#offset-int-int-) | Adjusts the location of this rectangle by the specified amount. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Tests whether two  com.aspose.psd.Rectangle  structures have equal location and size. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Tests whether two  com.aspose.psd.Rectangle  structures differ in location or size. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Converts the specified  com.aspose.psd.RectangleF  to a  com.aspose.psd.Rectangle  by rounding the  com.aspose.psd.RectangleF  values to the nearest integer values. |
| [setBottom(int value)](#setBottom-int-) | Gets or sets the y-coordinate that is the sum of the  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  property values of this  com.aspose.psd.Rectangle  structure. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets the height of this  com.aspose.psd.Rectangle  structure. |
| [setLeft(int value)](#setLeft-int-) | Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [setRight(int value)](#setRight-int-) | Gets or sets the x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  property values of this  com.aspose.psd.Rectangle  structure. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Gets or sets the size of this  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of this  com.aspose.psd.Rectangle  structure. |
| [setX(int value)](#setX-int-) | Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [setY(int value)](#setY-int-) | Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| [toString()](#toString--) | Converts the attributes of this  com.aspose.psd.Rectangle  to a human-readable string. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Converts the specified  com.aspose.psd.RectangleF  to a  com.aspose.psd.Rectangle  by truncating the  com.aspose.psd.RectangleF  values. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Gets a  com.aspose.psd.Rectangle  structure that contains the union of two  com.aspose.psd.Rectangle  structures. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initializes a new instance of the  com.aspose.psd.Rectangle  structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the upper-left corner of the rectangle. |
| y | int | The y-coordinate of the upper-left corner of the rectangle. |
| width | int | The width of the rectangle. |
| height | int | The height of the rectangle. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Initializes a new instance of the  com.aspose.psd.Rectangle  structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | A  com.aspose.psd.Point  that represents the upper-left corner of the rectangular region. |
| size | [Size](../../com.aspose.psd/size) | A  com.aspose.psd.Size  that represents the width and height of the rectangular region. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converts the specified  com.aspose.psd.RectangleF  structure to a  com.aspose.psd.Rectangle  structure by rounding the  com.aspose.psd.RectangleF  values to the next higher integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure to be converted. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Determines if the specified point is contained within this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  com.aspose.psd.Point  to test. |

**Returns:**
boolean - This method returns true if the point represented by  point  is contained within this  com.aspose.psd.Rectangle  structure; otherwise false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determines if the rectangular region represented by  rect  is entirely contained within this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  to test. |

**Returns:**
boolean - This method returns true if the rectangular region represented by  rect  is entirely contained within this  com.aspose.psd.Rectangle  structure; otherwise false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determines if the specified point is contained within this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the point to test. |
| y | int | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the point defined by  x  and  y  is contained within this  com.aspose.psd.Rectangle  structure; otherwise false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether  obj  is a  com.aspose.psd.Rectangle  structure with the same location and size of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to test. |

**Returns:**
boolean - This method returns true if  obj  is a  com.aspose.psd.Rectangle  structure and its  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , and  com.aspose.psd.Rectangle.Height  properties are equal to the corresponding properties of this  com.aspose.psd.Rectangle  structure; otherwise, false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Creates a  com.aspose.psd.Rectangle  structure with the specified edge locations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | int | The x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| top | int | The y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |
| right | int | The x-coordinate of the lower-right corner of this  com.aspose.psd.Rectangle  structure. |
| bottom | int | The y-coordinate of the lower-right corner of this  com.aspose.psd.Rectangle  structure. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Creates a new  Rectangle  from two points specified. Two verticales of the created  Rectangle  will be equal to the passed  point1  and  point2 . These would be typically the opposite vertices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | The first  Point  for the new rectangle. |
| point2 | [Point](../../com.aspose.psd/point) | The second  Point  for the new rectangle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Gets or sets the y-coordinate that is the sum of the  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  property values of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The y-coordinate that is the sum of  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  of this  com.aspose.psd.Rectangle .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gets a new instance of the  com.aspose.psd.Rectangle  structure that has  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  and  com.aspose.psd.Rectangle.Height  values set to zero.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets the height of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The height of this  com.aspose.psd.Rectangle  structure.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Gets or sets the x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  property values of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  of this  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Gets or sets the size of this  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets the width of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The width of this  com.aspose.psd.Rectangle  structure.
### getX() {#getX--}
```
public int getX()
```


Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getY() {#getY--}
```
public int getY()
```


Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - The y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this  com.aspose.psd.Rectangle  structure.

**Returns:**
int - An integer that represents the hash code for this rectangle.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Creates and returns an inflated copy of the specified  com.aspose.psd.Rectangle  structure. The copy is inflated by the specified amount. The original  com.aspose.psd.Rectangle  structure remains unmodified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  with which to start. This rectangle is not modified. |
| x | int | The amount to inflate this  com.aspose.psd.Rectangle  horizontally. |
| y | int | The amount to inflate this  com.aspose.psd.Rectangle  vertically. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Inflates this  com.aspose.psd.Rectangle  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | The amount to inflate this rectangle. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Inflates this  com.aspose.psd.Rectangle  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The amount to inflate this  com.aspose.psd.Rectangle  horizontally. |
| height | int | The amount to inflate this  com.aspose.psd.Rectangle  vertically. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Replaces this  com.aspose.psd.Rectangle  with the intersection of itself and the specified  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  with which to intersect. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Returns a third  com.aspose.psd.Rectangle  structure that represents the intersection of two other  com.aspose.psd.Rectangle  structures. If there is no intersection, an empty  com.aspose.psd.Rectangle  is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | A first rectangle to intersect. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | A second rectangle to intersect. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Determines if this rectangle intersects with  rect .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to test. |

**Returns:**
boolean - This method returns true if there is any intersection, otherwise false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether all numeric properties of this  com.aspose.psd.Rectangle  have values of zero.

**Returns:**
boolean - This property returns true if the  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , and  com.aspose.psd.Rectangle.Y  properties of this  com.aspose.psd.Rectangle  all have values of zero; otherwise, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Gets a value indicating whether this  Rectangle  is at least partially visible

**Returns:**
boolean -  true  if this  Rectangle  is at least partially visible; otherwise,  false .
### normalize() {#normalize--}
```
public void normalize()
```


Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Amount to offset the location. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The horizontal offset. |
| y | int | The vertical offset. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Tests whether two  com.aspose.psd.Rectangle  structures have equal location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure that is to the left of the equality operator. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure that is to the right of the equality operator. |

**Returns:**
boolean - This operator returns true if the two  com.aspose.psd.Rectangle  structures have equal  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , and  com.aspose.psd.Rectangle.Height  properties.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Tests whether two  com.aspose.psd.Rectangle  structures differ in location or size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure that is to the left of the inequality operator. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure that is to the right of the inequality operator. |

**Returns:**
boolean - This operator returns true if any of the  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  or  com.aspose.psd.Rectangle.Height  properties of the two  com.aspose.psd.Rectangle  structures are unequal; otherwise false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converts the specified  com.aspose.psd.RectangleF  to a  com.aspose.psd.Rectangle  by rounding the  com.aspose.psd.RectangleF  values to the nearest integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  to be converted. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Gets or sets the y-coordinate that is the sum of the  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  property values of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate that is the sum of  com.aspose.psd.Rectangle.Y  and  com.aspose.psd.Rectangle.Height  of this  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets the height of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of this  com.aspose.psd.Rectangle  structure. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate of the left edge of this  com.aspose.psd.Rectangle  structure. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | A  Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Gets or sets the x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  property values of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate that is the sum of  com.aspose.psd.Rectangle.X  and  com.aspose.psd.Rectangle.Width  of this  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Gets or sets the size of this  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate of the top edge of this  com.aspose.psd.Rectangle  structure. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Sets the width of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of this  com.aspose.psd.Rectangle  structure. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The x-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The y-coordinate of the upper-left corner of this  com.aspose.psd.Rectangle  structure. |

### toString() {#toString--}
```
public String toString()
```


Converts the attributes of this  com.aspose.psd.Rectangle  to a human-readable string.

**Returns:**
java.lang.String - A string that contains the position, width, and height of this  com.aspose.psd.Rectangle  structure.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converts the specified  com.aspose.psd.RectangleF  to a  com.aspose.psd.Rectangle  by truncating the  com.aspose.psd.RectangleF  values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  to be converted. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Gets a  com.aspose.psd.Rectangle  structure that contains the union of two  com.aspose.psd.Rectangle  structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | A first rectangle to union. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | A second rectangle to union. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

