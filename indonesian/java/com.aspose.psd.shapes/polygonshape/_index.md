---
title: "PolygonShape"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili bentuk poligon."
type: docs
weight: 15
url: /id/java/com.aspose.psd.shapes/polygonshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Mewakili bentuk poligon.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Menginisialisasi instance baru dari kelas  PolygonShape  . |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.psd.PointF---) | Menginisialisasi instance baru dari kelas  PolygonShape  . |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.psd.PointF---boolean-) | Menginisialisasi instance baru dari kelas  PolygonShape  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Mendapatkan batas objek. |
| [getCenter()](#getCenter--) | Mendapatkan pusat bentuk. |
| [getClass()](#getClass--) |  |
| [getEndPoint()](#getEndPoint--) | Mendapatkan titik akhir shape. |
| [getPoints()](#getPoints--) | Mendapatkan atau mengatur titik kurva. |
| [getSegments()](#getSegments--) | Mendapatkan segmen bentuk. |
| [getStartPoint()](#getStartPoint--) | Mendapatkan titik awal shape. |
| [hasSegments()](#hasSegments--) | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk ditutup. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Membalik urutan titik untuk shape ini. |
| [setClosed(boolean value)](#setClosed-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk ditutup. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.psd.PointF---) | Mendapatkan atau mengatur titik kurva. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Menginisialisasi instance baru dari kelas  PolygonShape  .

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.psd.PointF---}
```
public PolygonShape(PointF[] points)
```


Menginisialisasi instance baru dari kelas  PolygonShape  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array titik. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.psd.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Menginisialisasi instance baru dari kelas  PolygonShape  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Array titik. |
| isClosed | boolean | Jika diatur ke  true  poligon ditutup. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Mendapatkan batas objek.

Nilai: Batas objek.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Mendapatkan batas objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas dihitung. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Mendapatkan batas objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas dihitung. |
| pen | [Pen](../../com.aspose.psd/pen) | Pulpen yang digunakan untuk objek. Ini dapat memengaruhi ukuran batas objek. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Mendapatkan pusat bentuk.

Nilai: Pusat bentuk.

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


Mendapatkan titik akhir shape.

Nilai: Titik akhir bentuk.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Mendapatkan atau mengatur titik kurva.

Nilai: Titik kurva.

**Returns:**
com.aspose.psd.PointF[]
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Mendapatkan segmen bentuk.

Nilai: Segmen bentuk.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Mendapatkan titik awal shape.

Nilai: Titik awal bentuk.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen.

Nilai:  True  jika bentuk memiliki segmen; sebaliknya,  false .

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


Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk ditutup.

Nilai:  true  jika bentuk ditutup; sebaliknya,  false .

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


Membalik urutan titik untuk shape ini.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk ditutup.

Nilai:  true  jika bentuk ditutup; sebaliknya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setPoints(PointF[] value) {#setPoints-com.aspose.psd.PointF---}
```
public void setPoints(PointF[] value)
```


Mendapatkan atau mengatur titik kurva.

Nilai: Titik kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Transformasi yang akan diterapkan. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

