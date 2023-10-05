---
title: Point
second_title: Aspose.PSD for Java API Reference
description: Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 83
url: /java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initializes a new instance of the  Aspose.Imaging.Point  structure with the specified coordinates. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Initializes a new instance of the  Aspose.Imaging.Point  structure from the  Aspose.Imaging.Size  structure. |
| [Point(int dw)](#Point-int-) | Initializes a new instance of the  Aspose.Imaging.Point  structure using coordinates specified by an integer value. |
## Fields

| Field | Description |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Represents the point format. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Adds the specified  Aspose.Imaging.Size  to the specified  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  by rounding the values of the  Aspose.Imaging.PointF  to the next higher integer values. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifies whether this  Aspose.Imaging.Point  contains the same coordinates as the specified  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gets a new instance of the  Aspose.Imaging.Point  structure that has  Aspose.Imaging.Point.X  and  Aspose.Imaging.Point.Y  values set to zero. |
| [getX()](#getX--) | Gets or sets the x-coordinate of this  Aspose.Imaging.Point . |
| [getY()](#getY--) | Gets or sets the y-coordinate of this  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Returns a hash code for this  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this  Aspose.Imaging.Point  is empty. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Translates this  Aspose.Imaging.Point  by the specified  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Translates this  Aspose.Imaging.Point  by the specified amount. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Translates a  Aspose.Imaging.Point  by a given  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compares two  Aspose.Imaging.Point  objects. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Compares two  Aspose.Imaging.Point  objects. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Translates a  Aspose.Imaging.Point  by the negative of a given  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  object by rounding the  Aspose.Imaging.Point  values to the nearest integer. |
| [setX(int value)](#setX-int-) | Gets or sets the x-coordinate of this  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Gets or sets the y-coordinate of this  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Returns the result of subtracting specified  Aspose.Imaging.Size  from the specified  Aspose.Imaging.Point . |
| [toString()](#toString--) | Converts this  Aspose.Imaging.Point  to a human-readable string. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Converts the specified  Point  structure to the  PointF  structure. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Converts the specified  Aspose.Imaging.Point  structure to a  Aspose.Imaging.Size  structure. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  by truncating the values of the  Aspose.Imaging.Point . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initializes a new instance of the  Aspose.Imaging.Point  structure with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The horizontal position of the point. |
| y | int | The vertical position of the point. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Initializes a new instance of the  Aspose.Imaging.Point  structure from the  Aspose.Imaging.Size  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Contains the new point coordinates. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initializes a new instance of the  Aspose.Imaging.Point  structure using coordinates specified by an integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dw | int | A 32-bit integer that specifies the coordinates for the new point. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Represents the point format.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Adds the specified  Aspose.Imaging.Size  to the specified  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  to add to. |
| size | [Size](../../com.aspose.psd/size) | The  Aspose.Imaging.Size  to add to the  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  by rounding the values of the  Aspose.Imaging.PointF  to the next higher integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  Aspose.Imaging.PointF  to convert. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifies whether this  Aspose.Imaging.Point  contains the same coordinates as the specified  System.Object .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to test. |

**Returns:**
boolean - True if  obj  is a  Aspose.Imaging.Point  and has the same coordinates as this  Aspose.Imaging.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Gets a new instance of the  Aspose.Imaging.Point  structure that has  Aspose.Imaging.Point.X  and  Aspose.Imaging.Point.Y  values set to zero.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Gets or sets the x-coordinate of this  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Gets or sets the y-coordinate of this  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this  Aspose.Imaging.Point .

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this  Aspose.Imaging.Point  is empty.

**Returns:**
boolean - True if both  Aspose.Imaging.Point.X  and  Aspose.Imaging.Point.Y  are 0; otherwise, false.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Translates this  Aspose.Imaging.Point  by the specified  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  used to offset this  Aspose.Imaging.Point . |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Translates this  Aspose.Imaging.Point  by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | int | The amount to offset the x-coordinate. |
| dy | int | The amount to offset the y-coordinate. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Translates a  Aspose.Imaging.Point  by a given  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  to translate. |
| size | [Size](../../com.aspose.psd/size) | A  Aspose.Imaging.Size  that specifies the pair of numbers to add to the coordinates of  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Compares two  Aspose.Imaging.Point  objects. The result specifies whether the values of the  Aspose.Imaging.Point.X  and  Aspose.Imaging.Point.Y  properties of the two  Aspose.Imaging.Point  objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | A first  Aspose.Imaging.Point  to compare. |
| point2 | [Point](../../com.aspose.psd/point) | A second  Aspose.Imaging.Point  to compare. |

**Returns:**
boolean - True if the  Aspose.Imaging.Point.X  and  Aspose.Imaging.Point.Y  values of  point1  and  point2  are equal; otherwise, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Compares two  Aspose.Imaging.Point  objects. The result specifies whether the values of the  Aspose.Imaging.Point.X  or  Aspose.Imaging.Point.Y  properties of the two  Aspose.Imaging.Point  objects are unequal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | A first  Aspose.Imaging.Point  to compare. |
| point2 | [Point](../../com.aspose.psd/point) | A second  Aspose.Imaging.Point  to compare. |

**Returns:**
boolean - True if the values of either the  Aspose.Imaging.Point.X  properties or the  Aspose.Imaging.Point.Y  properties of  point1  and  point2  differ; otherwise, false.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Translates a  Aspose.Imaging.Point  by the negative of a given  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  to translate. |
| size | [Size](../../com.aspose.psd/size) | A  Aspose.Imaging.Size  that specifies the pair of numbers to subtract from the coordinates of  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  object by rounding the  Aspose.Imaging.Point  values to the nearest integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  Aspose.Imaging.PointF  to convert. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Gets or sets the x-coordinate of this  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Gets or sets the y-coordinate of this  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Returns the result of subtracting specified  Aspose.Imaging.Size  from the specified  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  to be subtracted from. |
| size | [Size](../../com.aspose.psd/size) | The  Aspose.Imaging.Size  to subtract from the  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Converts this  Aspose.Imaging.Point  to a human-readable string.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Converts the specified  Point  structure to the  PointF  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Point  to be converted. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Converts the specified  Aspose.Imaging.Point  structure to a  Aspose.Imaging.Size  structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | The  Aspose.Imaging.Point  to be converted. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Converts the specified  Aspose.Imaging.PointF  to a  Aspose.Imaging.Point  by truncating the values of the  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  Aspose.Imaging.PointF  to convert. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

