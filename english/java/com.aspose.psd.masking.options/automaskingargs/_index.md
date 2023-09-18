---
title: AutoMaskingArgs
second_title: Aspose.PSD for Java API Reference
description: Represents the arguments that are specified for automated masking methods
type: docs
weight: 11
url: /java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Represents the arguments that are specified for automated masking methods
## Constructors

| Constructor | Description |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Gets the maximum number of iterations. |
| [getNumberOfObjects()](#getNumberOfObjects--) | Gets the number of objects to separate initial image to (optional), default value is 2 (object and background). |
| [getObjectsPoints()](#getObjectsPoints--) | Gets the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Gets the objects rectangles that belong to separated objects (optional). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Gets the points that no longer belong to any object (optional). |
| [getPrecision()](#getPrecision--) | Gets the precision of segmentation method (optional). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Sets the maximum number of iterations. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | Sets the number of objects to separate initial image to (optional), default value is 2 (object and background). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Sets the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Sets the objects rectangles that belong to separated objects (optional). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Sets the points that no longer belong to any object (optional). |
| [setPrecision(double value)](#setPrecision-double-) | Sets the precision of segmentation method (optional). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Gets the maximum number of iterations.

Value: The maximum maximum number of iterations.

**Returns:**
int - the maximum number of iterations.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


Gets the number of objects to separate initial image to (optional), default value is 2 (object and background).

Value: The number of objects.

**Returns:**
int - the number of objects to separate initial image to (optional), default value is 2 (object and background).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Gets the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image. This parameter is used to increase segmentation method precision.

Value: The objects points.

**Returns:**
com.aspose.psd.Point[][] - the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Gets the objects rectangles that belong to separated objects (optional). This parameter is used to increase segmentation method precision.

Value: The objects rectangles.

**Returns:**
com.aspose.psd.Rectangle[] - the objects rectangles that belong to separated objects (optional).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Gets the points that no longer belong to any object (optional). This parameter is used only in case of re-segmentation.

Value: The orphaned points.

**Returns:**
com.aspose.psd.Point[] - the points that no longer belong to any object (optional).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Gets the precision of segmentation method (optional).

Value: The precision of segmentation method (optional).

**Returns:**
double - the precision of segmentation method (optional).
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Sets the maximum number of iterations.

Value: The maximum maximum number of iterations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the maximum number of iterations. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


Sets the number of objects to separate initial image to (optional), default value is 2 (object and background).

Value: The number of objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the number of objects to separate initial image to (optional), default value is 2 (object and background). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Sets the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image. This parameter is used to increase segmentation method precision.

Value: The objects points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | the points that belong to separated objects (optional) NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Sets the objects rectangles that belong to separated objects (optional). This parameter is used to increase segmentation method precision.

Value: The objects rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | the objects rectangles that belong to separated objects (optional). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Sets the points that no longer belong to any object (optional). This parameter is used only in case of re-segmentation.

Value: The orphaned points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | the points that no longer belong to any object (optional). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Sets the precision of segmentation method (optional).

Value: The precision of segmentation method (optional).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the precision of segmentation method (optional). |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

