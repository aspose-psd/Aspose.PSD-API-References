---
title: "ArcShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir yay şekli temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Bir yay şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArcShape()](#ArcShape--) | ArcShape sınıfının yeni bir örneğini başlatır. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | ArcShape sınıfının yeni bir örneğini başlatır. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | ArcShape sınıfının yeni bir örneğini başlatır. |
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
| [getLeftBottom()](#getLeftBottom--) | Sol alt dikdörtgen noktasını alır. |
| [getLeftTop()](#getLeftTop--) | Sol üst dikdörtgen noktasını alır. |
| [getRectangleHeight()](#getRectangleHeight--) | Dikdörtgen yüksekliğini alır. |
| [getRectangleWidth()](#getRectangleWidth--) | Dikdörtgen genişliğini alır. |
| [getRightBottom()](#getRightBottom--) | Sağ alt dikdörtgen noktasını alır. |
| [getRightTop()](#getRightTop--) | Sağ üst dikdörtgen noktasını alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [getStartAngle()](#getStartAngle--) | Başlangıç açısını alır veya ayarlar. |
| [getStartPoint()](#getStartPoint--) | Şeklin başlangıç noktasını alır. |
| [getSweepAngle()](#getSweepAngle--) | Tarama açısını alır veya ayarlar. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Siparişli şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Bu şeklin nokta sırasını tersine çevirir. |
| [setClosed(boolean value)](#setClosed-boolean-) | Siparişli şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setStartAngle(float value)](#setStartAngle-float-) | Başlangıç açısını alır veya ayarlar. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Tarama açısını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


ArcShape sınıfının yeni bir örneğini başlatır.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


ArcShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Bu dikdörtgen. |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


ArcShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Bu dikdörtgen. |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |
| isClosed | boolean | true olarak ayarlanırsa yay kapalı olur. Kapalı yay aslında bir elipseye dönüşür. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Sol alt dikdörtgen noktasını alır.

Değer: Sol alt dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Sol üst dikdörtgen noktasını alır.

Değer: Sol üst dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Dikdörtgen yüksekliğini alır.

Değer: Dikdörtgen yüksekliği.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Dikdörtgen genişliğini alır.

Değer: Dikdörtgen genişliği.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Sağ alt dikdörtgen noktasını alır.

Değer: Sağ alt dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Sağ üst dikdörtgen noktasını alır.

Değer: Sağ üst dikdörtgen noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şekil segmentlerini alır.

Değer: Şekil segmentleri.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Başlangıç açısını alır veya ayarlar.

Değer: Başlangıç açısı.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Şeklin başlangıç noktasını alır.

Değer: Başlangıç şekil noktası.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Tarama açısını alır veya ayarlar.

Değer: Tarama açısı.

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


Siparişli şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı siparişli şekli işlerken başlangıç ve bitiş noktaları bir anlam taşımaz.

Değer:  True  eğer bu siparişli şekil kapalıysa; aksi takdirde,  false .

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


Siparişli şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı siparişli şekli işlerken başlangıç ve bitiş noktaları bir anlam taşımaz.

Değer:  True  eğer bu siparişli şekil kapalıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Başlangıç açısını alır veya ayarlar.

Değer: Başlangıç açısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Tarama açısını alır veya ayarlar.

Değer: Tarama açısı.

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

