---
title: "PathShape"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Bezier कर्व के नॉट्स से प्राप्त आकृति।"
type: docs
weight: 16
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

Bezier कर्व के नॉट्स से प्राप्त आकृति।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PathShape()](#PathShape--) | एक नया उदाहरण प्रारंभ करता है [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) क्लास का। |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | एक नया उदाहरण प्रारंभ करता है [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Bezier नॉट्स की सरणी प्राप्त करता है। |
| [getPathOperations()](#getPathOperations--) | पाथ ऑपरेशन्स (बूलियन ऑपरेशन्स) प्राप्त करता है या सेट करता है। |
| [getShapeIndex()](#getShapeIndex--) | लेयर में वर्तमान पाथ आकार का सूचकांक प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | इस उदाहरण के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | इस उदाहरण के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bezier नॉट्स की सरणी असाइन करता है। |
| [setPathOperations(int value)](#setPathOperations-int-) | पाथ ऑपरेशन्स (बूलियन ऑपरेशन्स) प्राप्त करता है या सेट करता है। |
| [setShapeIndex(int value)](#setShapeIndex-int-) | लेयर में वर्तमान पाथ आकार का सूचकांक प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | इस उदाहरण के आधार पर VectorPathRecord रिकॉर्ड बनाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


एक नया उदाहरण प्रारंभ करता है [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) क्लास का।

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


एक नया उदाहरण प्रारंभ करता है [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | लंबाई रिकॉर्ड। |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier नॉट रिकॉर्ड्स। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


Bezier नॉट्स की सरणी प्राप्त करता है।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord की सरणी
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


पाथ ऑपरेशन्स (बूलियन ऑपरेशन्स) प्राप्त करता है या सेट करता है।

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


लेयर में वर्तमान पाथ आकार का सूचकांक प्राप्त करता है या सेट करता है।

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


इस उदाहरण के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: true यदि यह उदाहरण बंद है; अन्यथा false।

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


इस उदाहरण के बंद होने को दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान: true यदि यह उदाहरण बंद है; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Bezier नॉट्स की सरणी असाइन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier नॉट्स की सरणी |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


पाथ ऑपरेशन्स (बूलियन ऑपरेशन्स) प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


लेयर में वर्तमान पाथ आकार का सूचकांक प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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


इस उदाहरण के आधार पर VectorPathRecord रिकॉर्ड बनाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - इस उदाहरण के प्रत्येक बिंदु के लिए एक LengthRecord और BezierKnotRecord लौटाता है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

