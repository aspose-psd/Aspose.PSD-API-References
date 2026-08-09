---
title: "CurveShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kıvrımlı bir spline şekli temsil eder."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.shapes/curveshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.PolygonShape](../../com.aspose.psd.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Kıvrımlı bir spline şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurveShape()](#CurveShape--) | CurveShape sınıfının yeni bir örneğini başlatır. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.psd.PointF---) | CurveShape sınıfının yeni bir örneğini başlatır. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---boolean-) | CurveShape sınıfının yeni bir örneğini başlatır. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.psd.PointF---float-) | CurveShape sınıfının yeni bir örneğini başlatır. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.psd.PointF---float-boolean-) | CurveShape sınıfının yeni bir örneğini başlatır. |
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
| [getTension()](#getTension--) | Eğri gerilimini alır veya ayarlar. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Bu şeklin nokta sırasını tersine çevirir. |
| [setClosed(boolean value)](#setClosed-boolean-) | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Eğri noktalarını alır veya ayarlar. |
| [setTension(float value)](#setTension-float-) | Eğri gerilimini alır veya ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


CurveShape sınıfının yeni bir örneğini başlatır.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.psd.PointF---}
```
public CurveShape(PointF[] points)
```


CurveShape sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


CurveShape sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.psd.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


CurveShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |
| gerilim | float | Eğri gerilimi. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.psd.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


CurveShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Noktalar dizisi. |
| gerilim | float | Eğri gerilimi. |
| isClosed | boolean | true olarak ayarlanırsa eğri kapalı olur. |

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
### getTension() {#getTension--}
```
public float getTension()
```


Eğri gerilimini alır veya ayarlar.

Değer: Eğri gerilimi.

**Returns:**
float
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

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Eğri gerilimini alır veya ayarlar.

Değer: Eğri gerilimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

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

