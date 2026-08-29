---
title: "ArcShape"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili bentuk busur."
type: docs
weight: 10
url: /id/java/com.aspose.psd.shapes/arcshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape), [com.aspose.psd.shapes.EllipseShape](../../com.aspose.psd.shapes/ellipseshape), [com.aspose.psd.shapes.PieShape](../../com.aspose.psd.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.psd.IOrderedShape](../../com.aspose.psd/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Mewakili bentuk busur.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ArcShape()](#ArcShape--) | Menginisialisasi sebuah instance baru dari kelas  ArcShape  . |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.psd.RectangleF-float-float-) | Menginisialisasi sebuah instance baru dari kelas  ArcShape  . |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-) | Menginisialisasi sebuah instance baru dari kelas  ArcShape  . |
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
| [getLeftBottom()](#getLeftBottom--) | Mendapatkan titik kiri bawah persegi panjang. |
| [getLeftTop()](#getLeftTop--) | Mendapatkan titik kiri atas persegi panjang. |
| [getRectangleHeight()](#getRectangleHeight--) | Mendapatkan tinggi persegi panjang. |
| [getRectangleWidth()](#getRectangleWidth--) | Mendapatkan lebar persegi panjang. |
| [getRightBottom()](#getRightBottom--) | Mendapatkan titik kanan bawah persegi panjang. |
| [getRightTop()](#getRightTop--) | Mendapatkan titik kanan atas persegi panjang. |
| [getSegments()](#getSegments--) | Mendapatkan segmen bentuk. |
| [getStartAngle()](#getStartAngle--) | Mendapatkan atau mengatur sudut awal. |
| [getStartPoint()](#getStartPoint--) | Mendapatkan titik awal shape. |
| [getSweepAngle()](#getSweepAngle--) | Mendapatkan atau mengatur sudut sapuan. |
| [hasSegments()](#hasSegments--) | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Membalik urutan titik untuk shape ini. |
| [setClosed(boolean value)](#setClosed-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. |
| [setStartAngle(float value)](#setStartAngle-float-) | Mendapatkan atau mengatur sudut awal. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Mendapatkan atau mengatur sudut sapuan. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Menginisialisasi sebuah instance baru dari kelas  ArcShape  .

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.psd.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Menginisialisasi sebuah instance baru dari kelas  ArcShape  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang. |
| startAngle | float | Sudut awal. |
| sweepAngle | float | Sudut sapuan. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.psd.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Menginisialisasi sebuah instance baru dari kelas  ArcShape  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang. |
| startAngle | float | Sudut awal. |
| sweepAngle | float | Sudut sapuan. |
| isClosed | boolean | Jika disetel ke  true  busur ditutup. Busur yang ditutup sebenarnya terdegradasi menjadi elips. |

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
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Mendapatkan titik kiri bawah persegi panjang.

Nilai: Titik kiri bawah persegi panjang.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Mendapatkan titik kiri atas persegi panjang.

Nilai: Titik kiri atas persegi panjang.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Mendapatkan tinggi persegi panjang.

Nilai: Tinggi persegi panjang.

**Returns:**
double
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Mendapatkan lebar persegi panjang.

Nilai: Lebar persegi panjang.

**Returns:**
double
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Mendapatkan titik kanan bawah persegi panjang.

Nilai: Titik kanan bawah persegi panjang.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Mendapatkan titik kanan atas persegi panjang.

Nilai: Titik kanan atas persegi panjang.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Mendapatkan segmen bentuk.

Nilai: Segmen bentuk.

**Returns:**
com.aspose.psd.ShapeSegment[]
### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Mendapatkan atau mengatur sudut awal.

Nilai: Sudut awal.

**Returns:**
float
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Mendapatkan titik awal shape.

Nilai: Titik awal bentuk.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Mendapatkan atau mengatur sudut sapuan.

Nilai: Sudut sapuan.

**Returns:**
float
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


Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. Saat memproses bentuk terurut yang ditutup, titik awal dan akhir tidak memiliki arti.

Nilai:  True  jika bentuk terurut ini ditutup; jika tidak,  false .

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


Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk terurut ditutup. Saat memproses bentuk terurut yang ditutup, titik awal dan akhir tidak memiliki arti.

Nilai:  True  jika bentuk terurut ini ditutup; jika tidak,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Mendapatkan atau mengatur sudut awal.

Nilai: Sudut awal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Mendapatkan atau mengatur sudut sapuan.

Nilai: Sudut sapuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

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

