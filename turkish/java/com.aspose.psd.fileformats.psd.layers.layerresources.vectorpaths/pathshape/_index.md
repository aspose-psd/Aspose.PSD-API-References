---
title: "PathShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bezier eğrisinin düğümlerinden oluşan şekil."
type: docs
weight: 16
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape)
```
public class PathShape implements IPathShape
```

Bezier eğrisinin düğümlerinden oluşan şekil.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PathShape()](#PathShape--) | Yeni bir [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) sınıfının örneğini başlatır. |
| [PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)](#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Yeni bir [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItems()](#getItems--) | Bezier düğümlerinin dizisini alır. |
| [getPathOperations()](#getPathOperations--) | Yol işlemlerini (Boolean işlemler) alır veya ayarlar. |
| [getShapeIndex()](#getShapeIndex--) | Katmandaki mevcut yol şeklinin dizinini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Bu örneğin kapalı olup olmadığını gösteren değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClosed(boolean value)](#setClosed-boolean-) | Bu örneğin kapalı olup olmadığını gösteren değeri alır veya ayarlar. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Bezier düğümlerinin dizisini atar. |
| [setPathOperations(int value)](#setPathOperations-int-) | Yol işlemlerini (Boolean işlemler) alır veya ayarlar. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Katmandaki mevcut yol şeklinin dizinini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [toVectorPathRecords()](#toVectorPathRecords--) | Bu örneğe dayanarak  VectorPathRecord  kayıtlarını oluşturur. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathShape() {#PathShape--}
```
public PathShape()
```


Yeni bir [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) sınıfının örneğini başlatır.

### PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords) {#PathShape-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.LengthRecord-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public PathShape(LengthRecord lengthRecord, BezierKnotRecord[] bezierKnotRecords)
```


Yeni bir [PathShape](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/pathshape) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lengthRecord | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) | Uzunluk kaydı. |
| bezierKnotRecords | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier düğüm kayıtları. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Bezier düğümlerinin dizisini alır.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - BezierKnotRecord dizisi
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Yol işlemlerini (Boolean işlemler) alır veya ayarlar.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Katmandaki mevcut yol şeklinin dizinini alır veya ayarlar.

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


Bu örneğin kapalı olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  bu örnek kapalıysa; aksi takdirde,  false .

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


Bu örneğin kapalı olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  bu örnek kapalıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public final void setItems(BezierKnotRecord[] bezierPoints)
```


Bezier düğümlerinin dizisini atar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Bezier düğümlerinin dizisi |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Yol işlemlerini (Boolean işlemler) alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Katmandaki mevcut yol şeklinin dizinini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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


Bu örneğe dayanarak  VectorPathRecord  kayıtlarını oluşturur.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord> - Bu örnekteki her nokta için bir LengthRecord ve bir BezierKnotRecord döndürür.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

