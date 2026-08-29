---
title: "EllipseShape"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili bentuk elips."
type: docs
weight: 13
url: /id/java/com.aspose.psd.shapes/ellipseshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds), [com.aspose.psd.Shape](../../com.aspose.psd/shape), [com.aspose.psd.shapes.RectangleProjectedShape](../../com.aspose.psd.shapes/rectangleprojectedshape), [com.aspose.psd.shapes.RectangleShape](../../com.aspose.psd.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Mewakili bentuk elips.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Menginisialisasi instance baru dari kelas  EllipseShape  . |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.psd.RectangleF-) | Menginisialisasi instance baru dari kelas  EllipseShape  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Mendapatkan batas objek. |
| [getCenter()](#getCenter--) | Mendapatkan pusat bentuk. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Mendapatkan titik kiri bawah persegi panjang. |
| [getLeftTop()](#getLeftTop--) | Mendapatkan titik kiri atas persegi panjang. |
| [getRectangleHeight()](#getRectangleHeight--) | Mendapatkan tinggi persegi panjang. |
| [getRectangleWidth()](#getRectangleWidth--) | Mendapatkan lebar persegi panjang. |
| [getRightBottom()](#getRightBottom--) | Mendapatkan titik kanan bawah persegi panjang. |
| [getRightTop()](#getRightTop--) | Mendapatkan titik kanan atas persegi panjang. |
| [getSegments()](#getSegments--) | Mendapatkan segmen bentuk. |
| [hasSegments()](#hasSegments--) | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Menginisialisasi instance baru dari kelas  EllipseShape  .

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.psd.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Menginisialisasi instance baru dari kelas  EllipseShape  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang. |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

