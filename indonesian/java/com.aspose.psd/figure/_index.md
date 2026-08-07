---
title: "Gambar"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Figur."
type: docs
weight: 42
url: /id/java/com.aspose.psd/figure/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Figur. Sebuah kontainer untuk bentuk.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Figure()](#Figure--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addShape(Shape shape)](#addShape-com.aspose.psd.Shape-) | Menambahkan sebuah bentuk ke figur. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.psd.Shape---) | Menambahkan rentang bentuk ke figur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Mendapatkan atau mengatur batas objek. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Mendapatkan batas objek. |
| [getClass()](#getClass--) |  |
| [getSegments()](#getSegments--) | Mendapatkan semua segmen figur. |
| [getShapes()](#getShapes--) | Mendapatkan bentuk-bentuk figur. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | Mendapatkan nilai yang menunjukkan apakah figur ini tertutup. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeShape(Shape shape)](#removeShape-com.aspose.psd.Shape-) | Menghapus sebuah bentuk dari figur. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.psd.Shape---) | Menghapus rentang bentuk dari figur. |
| [reverse()](#reverse--) | Membalik urutan bentuk figur ini dan urutan titik bentuk. |
| [setClosed(boolean value)](#setClosed-boolean-) | Mengatur nilai yang menunjukkan apakah figur ini tertutup. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan ke bentuk. |
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


Menambahkan sebuah bentuk ke figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Bentuk yang akan ditambahkan. |

### addShapes(Shape[] shapes) {#addShapes-com.aspose.psd.Shape---}
```
public void addShapes(Shape[] shapes)
```


Menambahkan rentang bentuk ke figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Bentuk-bentuk yang akan ditambahkan. |

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


Mendapatkan atau mengatur batas objek.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
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


Mendapatkan semua segmen figur.

**Returns:**
com.aspose.psd.ShapeSegment[] - Segmen figur.
### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Mendapatkan bentuk-bentuk figur.

**Returns:**
com.aspose.psd.Shape[] - Bentuk-bentuk figur.
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


Mendapatkan nilai yang menunjukkan apakah figur ini tertutup. Figur tertutup hanya akan berpengaruh bila bentuk pertama dan terakhir dari figur merupakan bentuk kontinu. Dalam kasus tersebut, titik pertama dari bentuk pertama akan terhubung dengan garis lurus dari titik terakhir bentuk terakhir.

**Returns:**
boolean -  True  jika figur ini tertutup; jika tidak,  false .
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


Menghapus sebuah bentuk dari figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.psd/shape) | Bentuk yang akan dihapus. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.psd.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Menghapus rentang bentuk dari figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.psd/shape) | Rentang bentuk yang akan dihapus. |

### reverse() {#reverse--}
```
public void reverse()
```


Membalik urutan bentuk figur ini dan urutan titik bentuk.

### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Mengatur nilai yang menunjukkan apakah figur ini tertutup. Figur tertutup hanya akan berpengaruh bila bentuk pertama dan terakhir dari figur merupakan bentuk kontinu. Dalam kasus tersebut, titik pertama dari bentuk pertama akan terhubung dengan garis lurus dari titik terakhir bentuk terakhir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | True  jika gambar ini tertutup; jika tidak,  false . |

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

