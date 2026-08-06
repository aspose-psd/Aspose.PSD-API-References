---
title: "PathShape"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "الشكل الناتج من عقد منحنى بيزييه."
type: docs
weight: 16
url: /ar/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

الشكل الناتج من عقد منحنى بيزييه.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PathShape()](#PathShape--) | ينشئ مثلاً جديداً من الفئة [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | ينشئ مثلاً جديداً من الفئة [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | يحصل على مصفوفة من عقد بيزيير. |
| [getPathOperations()](#getPathOperations--) | يحصل أو يضبط عمليات المسار (العمليات المنطقية). |
| [getShapeIndex()](#getShapeIndex--) | يحصل أو يضبط فهرس شكل المسار الحالي في الطبقة. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | يعين مصفوفة من عقد بيزيير. |
| [setPathOperations(int value)](#setPathOperations-int-) | يحصل أو يضبط عمليات المسار (العمليات المنطقية). |
| [setShapeIndex(int value)](#setShapeIndex-int-) | يحصل أو يضبط فهرس شكل المسار الحالي في الطبقة. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | ينشئ سجلات  VectorPathRecord  بناءً على هذا المثيل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


ينشئ مثلاً جديداً من الفئة [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


ينشئ مثلاً جديداً من الفئة [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | سجل الطول. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | سجلات عقد بيزيير. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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
### getItems() {#getItems--}
```
public final BezierKnotRecord[] getItems()
```


يحصل على مصفوفة من عقد بيزيير.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - مصفوفة من BezierKnotRecord
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


يحصل أو يضبط عمليات المسار (العمليات المنطقية).

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


يحصل أو يضبط فهرس شكل المسار الحالي في الطبقة.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً.

القيمة:  true  إذا كان هذا المثيل مغلقاً؛ وإلا،  false .

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




### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً.

القيمة:  true  إذا كان هذا المثيل مغلقاً؛ وإلا،  false .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


يعين مصفوفة من عقد بيزيير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | مصفوفة من عقد بيزيير |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


يحصل أو يضبط عمليات المسار (العمليات المنطقية).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


يحصل أو يضبط فهرس شكل المسار الحالي في الطبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toVectorPathRecords() {#toVectorPathRecords--}
```
public final System.Collections.Generic.IGenericEnumerable<VectorPathRecord> toVectorPathRecords()
```


ينشئ سجلات  VectorPathRecord  بناءً على هذا المثيل.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - يُرجع LengthRecord واحد و BezierKnotRecord لكل نقطة في هذا المثيل.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

