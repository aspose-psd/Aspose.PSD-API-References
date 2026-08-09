---
title: "PieShape"
second_title: "Java için Aspose.PSD API Referansı"
description: "Pasta dilimi şekli temsil eder."
type: docs
weight: 14
url: /tr/java/com.aspose.psd.shapes/pieshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Pasta dilimi şekli temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PieShape()](#PieShape--) | PieShape sınıfının yeni bir örneğini başlatır. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.psd.RectangleF-float-float-) | PieShape sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Nesnenin sınırlarını alır. |
| [getCenter()](#getCenter--) | Şeklin merkezini alır. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Sol alt dikdörtgen noktasını alır. |
| [getLeftTop()](#getLeftTop--) | Sol üst dikdörtgen noktasını alır. |
| [getRectangleHeight()](#getRectangleHeight--) | Dikdörtgen yüksekliğini alır. |
| [getRectangleWidth()](#getRectangleWidth--) | Dikdörtgen genişliğini alır. |
| [getRightBottom()](#getRightBottom--) | Sağ alt dikdörtgen noktasını alır. |
| [getRightTop()](#getRightTop--) | Sağ üst dikdörtgen noktasını alır. |
| [getSegments()](#getSegments--) | Şekil segmentlerini alır. |
| [getStartAngle()](#getStartAngle--) | Başlangıç açısını alır veya ayarlar. |
| [getSweepAngle()](#getSweepAngle--) | Tarama açısını alır veya ayarlar. |
| [hasSegments()](#hasSegments--) | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setStartAngle(float value)](#setStartAngle-float-) | Başlangıç açısını alır veya ayarlar. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Tarama açısını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PieShape() {#PieShape--}
```
public PieShape()
```


PieShape sınıfının yeni bir örneğini başlatır.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.psd.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


PieShape sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Bu dikdörtgen. |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

