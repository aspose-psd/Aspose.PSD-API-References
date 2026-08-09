---
title: "Figure"
second_title: "Java için Aspose.PSD API Referansı"
description: "Şekil."
type: docs
weight: 42
url: /tr/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Şekil. Şekiller için bir kapsayıcı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Figure()](#Figure--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Şekle bir şekil ekler. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Şekle bir dizi şekil ekler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır veya ayarlar. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Nesnenin sınırlarını alır. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Nesnenin sınırlarını alır. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Şeklin tüm segmentlerini alır. |
| [getShapes()](#getShapes--) | Şeklin şekillerini alır. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Bu şeklin kapalı olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Şekilden bir şekil kaldırır. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Şekilden bir dizi şekli kaldırır. |
| [reverse()](#reverse--) | Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir. |
| [setClosed(boolean value)](#setClosed-boolean-) | Bu şeklin kapalı olup olmadığını gösteren bir değeri ayarlar. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Belirtilen dönüşümü şekle uygular. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Figure() {#Figure--}
```
public Figure()
```


### addShape(Shape shape) {#addShape-com.aspose.psd.Shape-}
```
public void addShape(Shape shape)
```


Şekle bir şekil ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Eklenecek şekil. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Şekle bir dizi şekil ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Eklenecek şekiller. |

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


Nesnenin sınırlarını alır veya ayarlar.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Şeklin tüm segmentlerini alır.

**Returns:**
com.aspose.psd.ShapeSegment[] - Şeklin segmentleri.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Şeklin şekillerini alır.

**Returns:**
com.aspose.psd.Shape[] - Şeklin şekilleri.
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


Bu şeklin kapalı olup olmadığını gösteren bir değeri alır. Kapalı bir şekil, yalnızca ilk ve son şeklin sürekli şekiller olduğu durumda fark yaratır. Böyle bir durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanır.

**Returns:**
boolean -  True  eğer bu şekil kapalıysa; aksi takdirde,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeShape(Shape shape) {#removeShape-com.aspose.psd.Shape-}
```
public void removeShape(Shape shape)
```


Şekilden bir şekil kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Kaldırılacak şekil. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Şekilden bir dizi şekli kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Kaldırılacak şekil aralığı. |

### reverse() {#reverse--}
```
public void reverse()
```


Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Bu şeklin kapalı olup olmadığını gösteren bir değeri ayarlar. Kapalı bir şekil, yalnızca ilk ve son şeklin sürekli şekiller olduğu durumda fark yaratır. Böyle bir durumda, ilk şeklin ilk noktası, son şeklin son noktasından düz bir çizgiyle bağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | True  eğer bu şekil kapalıysa; aksi takdirde,  false . |

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

