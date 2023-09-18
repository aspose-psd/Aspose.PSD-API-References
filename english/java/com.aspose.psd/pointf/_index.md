---
title: PointF
second_title: Aspose.PSD for Java API Reference
description: Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
type: docs
weight: 84
url: /java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.
## Constructors

| Constructor | Description |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initializes a new instance of the  com.aspose.psd.PointF  structure with the specified coordinates. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | Translates a given  com.aspose.psd.PointF  by the specified  com.aspose.psd.Size . |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Translates a given  com.aspose.psd.PointF  by a specified  com.aspose.psd.SizeF . |
| [equals(Object obj)](#equals-java.lang.Object-) | Specifies whether this  com.aspose.psd.PointF  contains the same coordinates as the specified  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gets a new instance of the  com.aspose.psd.PointF  structure that has  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  values set to zero. |
| [getX()](#getX--) | Gets or sets the x-coordinate of this  com.aspose.psd.PointF . |
| [getY()](#getY--) | Gets or sets the y-coordinate of this  com.aspose.psd.PointF . |
| [hashCode()](#hashCode--) | Returns a hash code for this  com.aspose.psd.PointF  structure. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this  com.aspose.psd.PointF  is empty. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | Translates a  com.aspose.psd.PointF  by a given  com.aspose.psd.Size . |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Translates the  com.aspose.psd.PointF  by the specified  com.aspose.psd.SizeF . |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Compares two  com.aspose.psd.PointF  structures. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Determines whether the coordinates of the specified points are not equal. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | Translates a  com.aspose.psd.PointF  by the negative of a given  com.aspose.psd.Size . |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Translates a  com.aspose.psd.PointF  by the negative of a specified  com.aspose.psd.SizeF . |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of this  com.aspose.psd.PointF . |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of this  com.aspose.psd.PointF . |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | Translates a  com.aspose.psd.PointF  by the negative of a specified size. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Translates a  com.aspose.psd.PointF  by the negative of a specified size. |
| [toString()](#toString--) | Converts this  com.aspose.psd.PointF  to a human readable string. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initializes a new instance of the  com.aspose.psd.PointF  structure with the specified coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The horizontal position of the point. |
| y | float | The vertical position of the point. |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


Translates a given  com.aspose.psd.PointF  by the specified  com.aspose.psd.Size .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [Size](../../com.aspose.psd/size) | The  com.aspose.psd.Size  that specifies the numbers to add to the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Translates a given  com.aspose.psd.PointF  by a specified  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [SizeF](../../com.aspose.psd/sizef) | The  com.aspose.psd.SizeF  that specifies the numbers to add to the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specifies whether this  com.aspose.psd.PointF  contains the same coordinates as the specified  System.Object .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to test. |

**Returns:**
boolean - This method returns true if  obj  is a  com.aspose.psd.PointF  and has the same coordinates as this  com.aspose.psd.Point .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Gets a new instance of the  com.aspose.psd.PointF  structure that has  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  values set to zero.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


Gets or sets the x-coordinate of this  com.aspose.psd.PointF .

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


Gets or sets the y-coordinate of this  com.aspose.psd.PointF .

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this  com.aspose.psd.PointF  structure.

**Returns:**
int - An integer value that specifies a hash value for this  com.aspose.psd.PointF  structure.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this  com.aspose.psd.PointF  is empty.

**Returns:**
boolean - True if both  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  are 0; otherwise, false.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Translates a  com.aspose.psd.PointF  by a given  com.aspose.psd.Size .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [Size](../../com.aspose.psd/size) | A  com.aspose.psd.Size  that specifies the pair of numbers to add to the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Translates the  com.aspose.psd.PointF  by the specified  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [SizeF](../../com.aspose.psd/sizef) | The  com.aspose.psd.SizeF  that specifies the numbers to add to the x- and y-coordinates of the  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Compares two  com.aspose.psd.PointF  structures. The result specifies whether the values of the  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  properties of the two  com.aspose.psd.PointF  structures are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | A first  com.aspose.psd.PointF  to compare. |
| point2 | [PointF](../../com.aspose.psd/pointf) | A second  com.aspose.psd.PointF  to compare. |

**Returns:**
boolean - True if the  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  values of the first and second  com.aspose.psd.PointF  structures are equal; otherwise, false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Determines whether the coordinates of the specified points are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | A first  com.aspose.psd.PointF  to compare. |
| point2 | [PointF](../../com.aspose.psd/pointf) | A second  com.aspose.psd.PointF  to compare. |

**Returns:**
boolean - True to indicate the  com.aspose.psd.PointF.X  and  com.aspose.psd.PointF.Y  values of  point1  and  point2  are not equal; otherwise, false.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Translates a  com.aspose.psd.PointF  by the negative of a given  com.aspose.psd.Size .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | A  com.aspose.psd.PointF  to translate. |
| size | [Size](../../com.aspose.psd/size) | A  com.aspose.psd.Size  that specifies the numbers to subtract from the x- and y-coordinates of the  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Translates a  com.aspose.psd.PointF  by the negative of a specified  com.aspose.psd.SizeF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [SizeF](../../com.aspose.psd/sizef) | The  com.aspose.psd.SizeF  that specifies the numbers to subtract from the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Gets or sets the x-coordinate of this  com.aspose.psd.PointF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Gets or sets the y-coordinate of this  com.aspose.psd.PointF .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Translates a  com.aspose.psd.PointF  by the negative of a specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [Size](../../com.aspose.psd/size) | The  com.aspose.psd.Size  that specifies the numbers to subtract from the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Translates a  com.aspose.psd.PointF  by the negative of a specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | The  com.aspose.psd.PointF  to translate. |
| size | [SizeF](../../com.aspose.psd/sizef) | The  com.aspose.psd.SizeF  that specifies the numbers to subtract from the coordinates of  point . |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


Converts this  com.aspose.psd.PointF  to a human readable string.

**Returns:**
java.lang.String - A string that represents this  com.aspose.psd.PointF .
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

