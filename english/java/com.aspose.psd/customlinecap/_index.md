---
title: CustomLineCap
second_title: Aspose.PSD for Java API Reference
description: Encapsulates a custom user-defined line cap.
type: docs
weight: 34
url: /java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Encapsulates a custom user-defined line cap.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Initializes a new instance of the  CustomLineCap  class with the specified outline and fill. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Initializes a new instance of the  CustomLineCap  class from the specified existing  LineCap  enumeration with the specified outline and fill. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Initializes a new instance of the  CustomLineCap  class from the specified existing  LineCap  enumeration with the specified outline, fill, and inset. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Gets the  LineCap  enumeration on which this  CustomLineCap  is based. |
| [getBaseInset()](#getBaseInset--) | Gets the distance between the cap and the line. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Gets the object that defines the fill for the custom cap. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Gets the caps used to start and end lines that make up this custom cap. |
| [getStrokeJoin()](#getStrokeJoin--) | Gets the  LineJoin  enumeration that determines how lines that compose this  CustomLineCap  object are joined. |
| [getStrokePath()](#getStrokePath--) | Gets the object that defines the outline of the custom cap. |
| [getWidthScale()](#getWidthScale--) | Gets the amount by which to scale this  CustomLineCap  Class object with respect to the width of the  System.Drawing.Pen  object. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Sets the  LineCap  enumeration on which this  CustomLineCap  is based. |
| [setBaseInset(float value)](#setBaseInset-float-) | Sets the distance between the cap and the line. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Sets the object that defines the fill for the custom cap. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Sets the caps used to start and end lines that make up this custom cap. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Sets the  LineJoin  enumeration that determines how lines that compose this  CustomLineCap  object are joined. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Sets the object that defines the outline of the custom cap. |
| [setWidthScale(float value)](#setWidthScale-float-) | Sets the amount by which to scale this  CustomLineCap  Class object with respect to the width of the  System.Drawing.Pen  object. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Initializes a new instance of the  CustomLineCap  class with the specified outline and fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the outline of the custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Initializes a new instance of the  CustomLineCap  class from the specified existing  LineCap  enumeration with the specified outline and fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the outline of the custom cap. |
| baseCap | int | The line cap from which to create the custom cap. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Initializes a new instance of the  CustomLineCap  class from the specified existing  LineCap  enumeration with the specified outline, fill, and inset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the fill for the custom cap. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | A  GraphicsPath  object that defines the outline of the custom cap. |
| baseCap | int | The line cap from which to create the custom cap. |
| baseInset | float | The distance between the cap and the line. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Gets the  LineCap  enumeration on which this  CustomLineCap  is based.

**Returns:**
int - The  LineCap  enumeration on which this  CustomLineCap  is based.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Gets the distance between the cap and the line.

**Returns:**
float - The distance between the beginning of the cap and the end of the line.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Gets the object that defines the fill for the custom cap.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Gets the caps used to start and end lines that make up this custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startCap | int[] | The  LineCap  enumeration used at the beginning of a line within this cap. |
| endCap | int[] | The  LineCap  enumeration used at the end of a line within this cap. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Gets the  LineJoin  enumeration that determines how lines that compose this  CustomLineCap  object are joined.

**Returns:**
int - The  LineJoin  enumeration this  CustomLineCap  object uses to join lines.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Gets the object that defines the outline of the custom cap.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Gets the amount by which to scale this  CustomLineCap  Class object with respect to the width of the  System.Drawing.Pen  object.

**Returns:**
float - The amount by which to scale the cap.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Sets the  LineCap  enumeration on which this  CustomLineCap  is based.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The  LineCap  enumeration on which this  CustomLineCap  is based. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Sets the distance between the cap and the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The distance between the beginning of the cap and the end of the line. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Sets the object that defines the fill for the custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | The object that defines the fill for the custom cap. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Sets the caps used to start and end lines that make up this custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startCap | int | The  LineCap  enumeration used at the beginning of a line within this cap. |
| endCap | int | The  LineCap  enumeration used at the end of a line within this cap. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Sets the  LineJoin  enumeration that determines how lines that compose this  CustomLineCap  object are joined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The  LineJoin  enumeration this  CustomLineCap  object uses to join lines. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Sets the object that defines the outline of the custom cap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | The object that defines the outline of the custom cap. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Sets the amount by which to scale this  CustomLineCap  Class object with respect to the width of the  System.Drawing.Pen  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The amount by which to scale the cap. |

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

