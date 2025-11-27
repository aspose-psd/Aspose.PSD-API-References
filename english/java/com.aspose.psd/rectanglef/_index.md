---
title: RectangleF
second_title: Aspose.PSD for Java API Reference
description: Stores a set of four floating-point numbers that represent the location and size of a rectangle.
type: docs
weight: 89
url: /java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Stores a set of four floating-point numbers that represent the location and size of a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initializes a new instance of the  com.aspose.psd.RectangleF  structure with the specified location and size. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Initializes a new instance of the  com.aspose.psd.RectangleF  structure with the specified location and size. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Determines if the specified point is contained within this  com.aspose.psd.RectangleF  structure. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Determines if the rectangular region represented by  rect  is entirely contained within this  com.aspose.psd.RectangleF  structure. |
| [contains(float x, float y)](#contains-float-float-) | Determines if the specified point is contained within this  com.aspose.psd.RectangleF  structure. |
| [equals(Object obj)](#equals-java.lang.Object-) | Tests whether  obj  is a  com.aspose.psd.RectangleF  with the same location and size of this  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Creates a  com.aspose.psd.RectangleF  structure with upper-left corner and lower-right corner at the specified locations. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Creates a new  Rectangle  from two points specified. |
| [getBottom()](#getBottom--) | Gets or sets the y-coordinate that is the sum of  com.aspose.psd.RectangleF.Y  and  com.aspose.psd.RectangleF.Height  of this  com.aspose.psd.RectangleF  structure. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gets a new instance of the  com.aspose.psd.RectangleF  structure that has  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  and  com.aspose.psd.RectangleF.Height  values set to zero. |
| [getHeight()](#getHeight--) | Gets or sets the height of this  com.aspose.psd.RectangleF  structure. |
| [getLeft()](#getLeft--) | Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.RectangleF  structure. |
| [getLocation()](#getLocation--) | Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [getRight()](#getRight--) | Gets or sets the x-coordinate that is the sum of  com.aspose.psd.RectangleF.X  and  com.aspose.psd.RectangleF.Width  of this  com.aspose.psd.RectangleF  structure. |
| [getSize()](#getSize--) | Gets or sets the size of this  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.RectangleF  structure. |
| [getWidth()](#getWidth--) | Gets or sets the width of this  com.aspose.psd.RectangleF  structure. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [hashCode()](#hashCode--) | Gets the hash code for this  com.aspose.psd.RectangleF  structure. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Creates and returns an inflated copy of the specified  com.aspose.psd.RectangleF  structure. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Inflates this  com.aspose.psd.RectangleF  by the specified amount. |
| [inflate(float x, float y)](#inflate-float-float-) | Inflates this  com.aspose.psd.RectangleF  structure by the specified amount. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Replaces this  com.aspose.psd.RectangleF  structure with the intersection of itself and the specified  com.aspose.psd.RectangleF  structure. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Returns a  com.aspose.psd.RectangleF  structure that represents the intersection of two rectangles. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Determines if this rectangle intersects with  rect . |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether the  com.aspose.psd.RectangleF.Width  or  com.aspose.psd.RectangleF.Height  property of this  com.aspose.psd.RectangleF  has a value of zero. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [normalize()](#normalize--) | Normalizes the rectangle by making it's width and height positive, left less than right and top less than bottom. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Adjusts the location of this rectangle by the specified amount. |
| [offset(float x, float y)](#offset-float-float-) | Adjusts the location of this rectangle by the specified amount. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implements the operator /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Tests whether two  com.aspose.psd.RectangleF  structures have equal location and size. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Tests whether two  com.aspose.psd.RectangleF  structures differ in location or size. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implements the operator \*. |
| [setBottom(float value)](#setBottom-float-) | Gets or sets the y-coordinate that is the sum of  com.aspose.psd.RectangleF.Y  and  com.aspose.psd.RectangleF.Height  of this  com.aspose.psd.RectangleF  structure. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height of this  com.aspose.psd.RectangleF  structure. |
| [setLeft(float value)](#setLeft-float-) | Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.RectangleF  structure. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [setRight(float value)](#setRight-float-) | Gets or sets the x-coordinate that is the sum of  com.aspose.psd.RectangleF.X  and  com.aspose.psd.RectangleF.Width  of this  com.aspose.psd.RectangleF  structure. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Gets or sets the size of this  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.RectangleF  structure. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width of this  com.aspose.psd.RectangleF  structure. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure. |
| [toString()](#toString--) | Converts the attributes of this  com.aspose.psd.RectangleF  to a human-readable string. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Converts the specified  com.aspose.psd.Rectangle  structure to a  com.aspose.psd.RectangleF  structure. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Creates the smallest possible third rectangle that can contain both of two rectangles that form a union. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initializes a new instance of the  com.aspose.psd.RectangleF  structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the upper-left corner of the rectangle. |
| y | float | The y-coordinate of the upper-left corner of the rectangle. |
| width | float | The width of the rectangle. |
| height | float | The height of the rectangle. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initializes a new instance of the  com.aspose.psd.RectangleF  structure with the specified location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  that represents the upper-left corner of the rectangular region. |
| size | [SizeF](../../com.aspose.psd/sizef) | A  com.aspose.psd.SizeF  that represents the width and height of the rectangular region. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Determines if the specified point is contained within this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to test. |

**Returns:**
boolean - This method returns true if the point represented by the  point  parameter is contained within this  com.aspose.psd.RectangleF  structure; otherwise false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Determines if the rectangular region represented by  rect  is entirely contained within this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  to test. |

**Returns:**
boolean - This method returns true if the rectangular region represented by  rect  is entirely contained within the rectangular region represented by this  com.aspose.psd.RectangleF ; otherwise false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Determines if the specified point is contained within this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the point to test. |
| y | float | The y-coordinate of the point to test. |

**Returns:**
boolean - This method returns true if the point defined by  x  and  y  is contained within this  com.aspose.psd.RectangleF  structure; otherwise false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Tests whether  obj  is a  com.aspose.psd.RectangleF  with the same location and size of this  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to test. |

**Returns:**
boolean - This method returns true if  obj  is a  com.aspose.psd.RectangleF  and its X, Y, Width, and Height properties are equal to the corresponding properties of this  com.aspose.psd.RectangleF ; otherwise, false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Creates a  com.aspose.psd.RectangleF  structure with upper-left corner and lower-right corner at the specified locations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | float | The x-coordinate of the upper-left corner of the rectangular region. |
| top | float | The y-coordinate of the upper-left corner of the rectangular region. |
| right | float | The x-coordinate of the lower-right corner of the rectangular region. |
| bottom | float | The y-coordinate of the lower-right corner of the rectangular region. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Creates a new  Rectangle  from two points specified. Two verticles of the created  Rectangle  will be equal to the passed  point1  and  point2 . These would be typically the opposite vertices.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | The first  Point  for the new rectangle. |
| point2 | [PointF](../../com.aspose.psd/pointf) | The second  Point  for the new rectangle. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Gets or sets the y-coordinate that is the sum of  com.aspose.psd.RectangleF.Y  and  com.aspose.psd.RectangleF.Height  of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The y-coordinate that is the sum of  com.aspose.psd.RectangleF.Y  and  com.aspose.psd.RectangleF.Height  of this  com.aspose.psd.RectangleF  structure.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Gets a new instance of the  com.aspose.psd.RectangleF  structure that has  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  and  com.aspose.psd.RectangleF.Height  values set to zero.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Gets or sets the height of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The height of this  com.aspose.psd.RectangleF  structure.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The x-coordinate of the left edge of this  com.aspose.psd.RectangleF  structure.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Gets or sets the x-coordinate that is the sum of  com.aspose.psd.RectangleF.X  and  com.aspose.psd.RectangleF.Width  of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The x-coordinate that is the sum of  com.aspose.psd.RectangleF.X  and  com.aspose.psd.RectangleF.Width  of this  com.aspose.psd.RectangleF  structure.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Gets or sets the size of this  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The y-coordinate of the top edge of this  com.aspose.psd.RectangleF  structure.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Gets or sets the width of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The width of this  com.aspose.psd.RectangleF  structure.
### getX() {#getX--}
```
public float getX()
```


Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The x-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getY() {#getY--}
```
public float getY()
```


Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Returns:**
float - The y-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this  com.aspose.psd.RectangleF  structure.

**Returns:**
int - The hash code for this  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Creates and returns an inflated copy of the specified  com.aspose.psd.RectangleF  structure. The copy is inflated by the specified amount. The original rectangle remains unmodified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  to be copied. This rectangle is not modified. |
| x | float | The amount to inflate the copy of the rectangle horizontally. |
| y | float | The amount to inflate the copy of the rectangle vertically. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Inflates this  com.aspose.psd.RectangleF  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | The amount to inflate this rectangle. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Inflates this  com.aspose.psd.RectangleF  structure by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The amount to inflate this  com.aspose.psd.RectangleF  structure horizontally. |
| y | float | The amount to inflate this  com.aspose.psd.RectangleF  structure vertically. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Replaces this  com.aspose.psd.RectangleF  structure with the intersection of itself and the specified  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle to intersect. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Returns a  com.aspose.psd.RectangleF  structure that represents the intersection of two rectangles. If there is no intersection, and empty  com.aspose.psd.RectangleF  is returned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | A first rectangle to intersect. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | A second rectangle to intersect. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Determines if this rectangle intersects with  rect .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle to test. |

**Returns:**
boolean - This method returns true if there is any intersection.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether the  com.aspose.psd.RectangleF.Width  or  com.aspose.psd.RectangleF.Height  property of this  com.aspose.psd.RectangleF  has a value of zero.

**Returns:**
boolean - This property returns true if the  com.aspose.psd.RectangleF.Width  or  com.aspose.psd.RectangleF.Height  property of this  com.aspose.psd.RectangleF  has a value of zero; otherwise, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | The amount to offset the location. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Adjusts the location of this rectangle by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The amount to offset the location horizontally. |
| y | float | The amount to offset the location vertically. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implements the operator /.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle. |
| divider | float | The divider. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Tests whether two  com.aspose.psd.RectangleF  structures have equal location and size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure that is to the left of the equality operator. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure that is to the right of the equality operator. |

**Returns:**
boolean - This operator returns true if the two specified  com.aspose.psd.RectangleF  structures have equal  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , and  com.aspose.psd.RectangleF.Height  properties.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Tests whether two  com.aspose.psd.RectangleF  structures differ in location or size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure that is to the left of the inequality operator. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | The  com.aspose.psd.RectangleF  structure that is to the right of the inequality operator. |

**Returns:**
boolean - This operator returns true if any of the  com.aspose.psd.RectangleF.X  ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , or  com.aspose.psd.RectangleF.Height  properties of the two  com.aspose.psd.RectangleF  structures are unequal; otherwise false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implements the operator \*.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | The rectangle. |
| multiplier | float | The multiplier. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Gets or sets the y-coordinate that is the sum of  com.aspose.psd.RectangleF.Y  and  com.aspose.psd.RectangleF.Height  of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Gets or sets the height of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Gets or sets the x-coordinate of the left edge of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Gets or sets the coordinates of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Gets or sets the x-coordinate that is the sum of  com.aspose.psd.RectangleF.X  and  com.aspose.psd.RectangleF.Width  of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Gets or sets the size of this  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Gets or sets the y-coordinate of the top edge of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Gets or sets the width of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Gets or sets the x-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Gets or sets the y-coordinate of the upper-left corner of this  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### toString() {#toString--}
```
public String toString()
```


Converts the attributes of this  com.aspose.psd.RectangleF  to a human-readable string.

**Returns:**
java.lang.String - A string that contains the position, width, and height of this  com.aspose.psd.RectangleF  structure.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Converts the specified  com.aspose.psd.Rectangle  structure to a  com.aspose.psd.RectangleF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | The  com.aspose.psd.Rectangle  structure to convert. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Creates the smallest possible third rectangle that can contain both of two rectangles that form a union.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | A first rectangle to union. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | A second rectangle to union. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

