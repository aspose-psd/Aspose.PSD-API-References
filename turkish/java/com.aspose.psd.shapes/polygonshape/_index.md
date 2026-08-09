---
title: "PolygonShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Poligon şekli temsil eder."
type: docs
weight: 15
url: /tr/java/com.aspose.psd.shapes/polygonshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Poligon şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | PolygonShape sınıfının yeni bir örneğini başlatır. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.psd.PointF---) | PolygonShape sınıfının yeni bir örneğini başlatır. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.psd.PointF---boolean-) | PolygonShape sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Nesnenin sınırlarını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Şeklin bitiş noktasını alır. |
| [getPoints()](#getPoints--) | Eğri noktalarını alır veya ayarlar. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [getStartPoint()](#getStartPoint--) | Şeklin başlangıç noktasını alır. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Bu şeklin nokta sırasını tersine çevirir. |
| [setClosed(boolean value)](#setClosed-boolean-) | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Eğri noktalarını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


PolygonShape sınıfının yeni bir örneğini başlatır.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.psd.PointF---}
```
public PolygonShape(PointF[] points)
```


PolygonShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.psd.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


PolygonShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |
| isClosed | boolean | true olarak ayarlanırsa çokgen kapalı olur. |

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
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Nesnenin sınırlarını alır.

Değer: Nesnenin sınırları.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Nesnenin sınırlarını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](../../com.aspose.psd/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Şeklin merkezini alır.

Değer: Şeklin merkezi.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Şeklin bitiş noktasını alır.

Değer: Bitiş şekil noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Eğri noktalarını alır veya ayarlar.

Değer: Eğri noktaları.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Şeklin başlangıç noktasını alır.

Değer: Başlangıç şekil noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır.

Değer:  Doğru  eğer şeklin segmentleri varsa; aksi takdirde,  yanlış .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Şekil kapalıysa true; aksi takdirde false.

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




### reverse() {#reverse--}
```
public void reverse()
```


Bu şeklin nokta sırasını tersine çevirir.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Şekil kapalıysa true; aksi takdirde false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Eğri noktalarını alır veya ayarlar.

Değer: Eğri noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Belirtilen dönüşümü şekle uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Uygulanacak dönüşüm. |

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

