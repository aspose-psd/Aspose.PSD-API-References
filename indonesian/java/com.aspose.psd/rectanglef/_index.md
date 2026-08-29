---
title: "RectangleF"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Menyimpan sekumpulan empat bilangan floating-point yang mewakili lokasi dan ukuran sebuah persegi panjang."
type: docs
weight: 89
url: /id/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Menyimpan sekumpulan empat bilangan floating-point yang mewakili lokasi dan ukuran sebuah persegi panjang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Menginisialisasi sebuah instance baru dari struktur  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang ditentukan. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Menginisialisasi sebuah instance baru dari struktur  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.RectangleF  ini. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh  rect  sepenuhnya berada di dalam struktur  com.aspose.psd.RectangleF  ini. |
| [contains(float x, float y)](#contains-float-float-) | Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.RectangleF  ini. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Membagi nilai persegi panjang saat ini untuk mengubah nilai skala vertikal dan horizontal matriks dan mengembalikan sebuah instance [RectangleF](../../com.aspose.psd/rectanglef) baru dengan nilai hasil. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji apakah  obj  adalah  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang sama dengan  com.aspose.psd.RectangleF  ini. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Membuat struktur  com.aspose.psd.RectangleF  dengan sudut kiri atas dan sudut kanan bawah pada lokasi yang ditentukan. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Membuat  Rectangle  baru dari dua titik yang ditentukan. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari  com.aspose.psd.RectangleF.Y  dan  com.aspose.psd.RectangleF.Height  pada struktur  com.aspose.psd.RectangleF  ini. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Mendapatkan sebuah instance baru dari struktur  com.aspose.psd.RectangleF  yang memiliki nilai  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  dan  com.aspose.psd.RectangleF.Height  diatur ke nol. |
| [getHeight()](#getHeight--) | Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.RectangleF  ini. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.RectangleF  ini. |
| [getLocation()](#getLocation--) | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.RectangleF  ini. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari  com.aspose.psd.RectangleF.X  dan  com.aspose.psd.RectangleF.Width  dari struktur  com.aspose.psd.RectangleF  ini. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran dari  com.aspose.psd.RectangleF  ini. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.RectangleF  ini. |
| [getWidth()](#getWidth--) | Mendapatkan atau mengatur lebar dari struktur  com.aspose.psd.RectangleF  ini. |
| [getX()](#getX--) | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini. |
| [getY()](#getY--) | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash untuk struktur  com.aspose.psd.RectangleF  ini. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Membuat dan mengembalikan salinan yang diperluas dari struktur  com.aspose.psd.RectangleF  yang ditentukan. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Mengembangkan  com.aspose.psd.RectangleF  ini sebesar jumlah yang ditentukan. |
| [inflate(float x, float y)](#inflate-float-float-) | Mengembangkan struktur  com.aspose.psd.RectangleF  ini sebesar jumlah yang ditentukan. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Mengganti struktur  com.aspose.psd.RectangleF  ini dengan irisan antara dirinya sendiri dan struktur  com.aspose.psd.RectangleF  yang ditentukan. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Mengembalikan struktur  com.aspose.psd.RectangleF  yang mewakili irisan dua persegi panjang. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Menentukan apakah persegi panjang ini berpotongan dengan  rect . |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah properti  com.aspose.psd.RectangleF.Width  atau  com.aspose.psd.RectangleF.Height  dari  com.aspose.psd.RectangleF  ini memiliki nilai nol. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Mengalikan nilai persegi panjang saat ini untuk mengubah nilai skala vertikal dan horizontal matriks dan mengembalikan instance [RectangleF](../../com.aspose.psd/rectanglef) baru dengan nilai hasil. |
| [normalize()](#normalize--) | Menormalkan persegi panjang dengan membuat lebar dan tingginya positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(float x, float y)](#offset-float-float-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Mengimplementasikan operator /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Menguji apakah dua struktur  com.aspose.psd.RectangleF  memiliki lokasi dan ukuran yang sama. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Menguji apakah dua struktur  com.aspose.psd.RectangleF  berbeda dalam lokasi atau ukuran. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Mengimplementasikan operator \*. |
| [setBottom(float value)](#setBottom-float-) | Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari  com.aspose.psd.RectangleF.Y  dan  com.aspose.psd.RectangleF.Height  pada struktur  com.aspose.psd.RectangleF  ini. |
| [setHeight(float value)](#setHeight-float-) | Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.RectangleF  ini. |
| [setLeft(float value)](#setLeft-float-) | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.RectangleF  ini. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.RectangleF  ini. |
| [setRight(float value)](#setRight-float-) | Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari  com.aspose.psd.RectangleF.X  dan  com.aspose.psd.RectangleF.Width  dari struktur  com.aspose.psd.RectangleF  ini. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Mendapatkan atau mengatur ukuran dari  com.aspose.psd.RectangleF  ini. |
| [setTop(float value)](#setTop-float-) | Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.RectangleF  ini. |
| [setWidth(float value)](#setWidth-float-) | Mendapatkan atau mengatur lebar dari struktur  com.aspose.psd.RectangleF  ini. |
| [setX(float value)](#setX-float-) | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini. |
| [setY(float value)](#setY-float-) | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Mengonversi [RectangleF](../../com.aspose.psd/rectanglef) menjadi struktur [Rectangle](../../com.aspose.psd/rectangle) dengan nilai persegi panjang yang dipotong. |
| [toString()](#toString--) | Mengonversi atribut dari  com.aspose.psd.RectangleF  ini menjadi string yang dapat dibaca manusia. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Mengonversi struktur  com.aspose.psd.Rectangle  yang ditentukan menjadi struktur  com.aspose.psd.RectangleF . |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Membuat persegi panjang ketiga terkecil yang dapat menampung kedua persegi panjang yang membentuk sebuah union. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Menginisialisasi sebuah instance baru dari struktur  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang. |
| lebar | float | Lebar persegi panjang. |
| tinggi | float | Tinggi persegi panjang. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Menginisialisasi sebuah instance baru dari struktur  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Sebuah com.aspose.psd.PointF yang mewakili sudut kiri atas wilayah persegi panjang. |
| size | [SizeF](../../com.aspose.psd/sizef) | Sebuah com.aspose.psd.SizeF yang mewakili lebar dan tinggi wilayah persegi panjang. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | com.aspose.psd.PointF yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang diwakili oleh parameter point berada di dalam struktur com.aspose.psd.RectangleF ini; jika tidak false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh  rect  sepenuhnya berada di dalam struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika wilayah persegi panjang yang diwakili oleh rect sepenuhnya berada di dalam wilayah persegi panjang yang diwakili oleh com.aspose.psd.RectangleF ini; jika tidak false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang didefinisikan oleh x dan y berada di dalam struktur com.aspose.psd.RectangleF ini; jika tidak false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Membagi nilai persegi panjang saat ini untuk mengubah nilai skala vertikal dan horizontal matriks dan mengembalikan sebuah instance [RectangleF](../../com.aspose.psd/rectanglef) baru dengan nilai hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| transformMatrix | double[] | Matriks transformasi lapisan. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menguji apakah  obj  adalah  com.aspose.psd.RectangleF  dengan lokasi dan ukuran yang sama dengan  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika obj adalah com.aspose.psd.RectangleF dan properti X, Y, Width, dan Height‑nya sama dengan properti yang bersesuaian pada com.aspose.psd.RectangleF ini; jika tidak, false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Membuat struktur  com.aspose.psd.RectangleF  dengan sudut kiri atas dan sudut kanan bawah pada lokasi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | float | Koordinat x dari sudut kiri atas wilayah persegi panjang. |
| atas | float | Koordinat y dari sudut kiri atas wilayah persegi panjang. |
| kanan | float | Koordinat x dari sudut kanan bawah wilayah persegi panjang. |
| bawah | float | Koordinat y dari sudut kanan bawah wilayah persegi panjang. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Membuat sebuah Rectangle baru dari dua titik yang ditentukan. Dua verteks dari Rectangle yang dibuat akan sama dengan point1 dan point2 yang diberikan. Ini biasanya merupakan verteks yang berlawanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Point pertama untuk rectangle baru. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Point kedua untuk rectangle baru. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari  com.aspose.psd.RectangleF.Y  dan  com.aspose.psd.RectangleF.Height  pada struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat y yang merupakan hasil penjumlahan com.aspose.psd.RectangleF.Y dan com.aspose.psd.RectangleF.Height dari struktur com.aspose.psd.RectangleF ini.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Mendapatkan sebuah instance baru dari struktur  com.aspose.psd.RectangleF  yang memiliki nilai  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  dan  com.aspose.psd.RectangleF.Height  diatur ke nol.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Tinggi dari struktur com.aspose.psd.RectangleF ini.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat x dari tepi kiri struktur com.aspose.psd.RectangleF ini.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari  com.aspose.psd.RectangleF.X  dan  com.aspose.psd.RectangleF.Width  dari struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat x yang merupakan hasil penjumlahan com.aspose.psd.RectangleF.X dan com.aspose.psd.RectangleF.Width dari struktur com.aspose.psd.RectangleF ini.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Mendapatkan atau mengatur ukuran dari  com.aspose.psd.RectangleF  ini.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat y dari tepi atas struktur com.aspose.psd.RectangleF ini.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Mendapatkan atau mengatur lebar dari struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Lebar dari struktur com.aspose.psd.RectangleF ini.
### getX() {#getX--}
```
public float getX()
```


Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat x dari sudut kiri atas struktur com.aspose.psd.RectangleF ini.
### getY() {#getY--}
```
public float getY()
```


Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
float - Koordinat y dari sudut kiri atas struktur com.aspose.psd.RectangleF ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash untuk struktur  com.aspose.psd.RectangleF  ini.

**Returns:**
int - Kode hash untuk com.aspose.psd.RectangleF ini.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Membuat dan mengembalikan salinan yang diperluas dari struktur com.aspose.psd.RectangleF yang ditentukan. Salinan tersebut diperluas sebesar jumlah yang ditentukan. Rectangle asli tetap tidak berubah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yang akan disalin. Rectangle ini tidak diubah. |
| x | float | Jumlah untuk memperluas salinan rectangle secara horizontal. |
| y | float | Jumlah untuk memperluas salinan rectangle secara vertikal. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Mengembangkan  com.aspose.psd.RectangleF  ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Jumlah untuk memperluas rectangle ini. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Mengembangkan struktur  com.aspose.psd.RectangleF  ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Jumlah untuk memperluas struktur com.aspose.psd.RectangleF ini secara horizontal. |
| y | float | Jumlah untuk memperluas struktur com.aspose.psd.RectangleF ini secara vertikal. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Mengganti struktur  com.aspose.psd.RectangleF  ini dengan irisan antara dirinya sendiri dan struktur  com.aspose.psd.RectangleF  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Rectangle untuk diinterseksikan. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Mengembalikan struktur com.aspose.psd.RectangleF yang mewakili interseksi dua rectangle. Jika tidak ada interseksi, sebuah com.aspose.psd.RectangleF kosong dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Rectangle pertama untuk diinterseksikan. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Rectangle kedua untuk diinterseksikan. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Menentukan apakah persegi panjang ini berpotongan dengan  rect .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Rectangle untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika ada interseksi apapun.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah properti  com.aspose.psd.RectangleF.Width  atau  com.aspose.psd.RectangleF.Height  dari  com.aspose.psd.RectangleF  ini memiliki nilai nol.

**Returns:**
boolean - Properti ini mengembalikan true jika properti com.aspose.psd.RectangleF.Width atau com.aspose.psd.RectangleF.Height dari com.aspose.psd.RectangleF ini memiliki nilai nol; jika tidak, false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Mengalikan nilai persegi panjang saat ini untuk mengubah nilai skala vertikal dan horizontal matriks dan mengembalikan instance [RectangleF](../../com.aspose.psd/rectanglef) baru dengan nilai hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| transformMatrix | double[] | Matriks transformasi lapisan. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


Menormalkan persegi panjang dengan membuat lebar dan tingginya positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Jumlah untuk menggeser lokasi. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Jumlah untuk menggeser lokasi secara horizontal. |
| y | float | Jumlah untuk menggeser lokasi secara vertikal. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Mengimplementasikan operator /.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang. |
| pembagi | float | Pembagi. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Menguji apakah dua struktur  com.aspose.psd.RectangleF  memiliki lokasi dan ukuran yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF yang berada di sebelah kiri operator kesetaraan. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF yang berada di sebelah kanan operator kesetaraan. |

**Returns:**
boolean - Operator ini mengembalikan true jika dua struktur com.aspose.psd.RectangleF yang ditentukan memiliki properti com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width, dan com.aspose.psd.RectangleF.Height yang sama.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Menguji apakah dua struktur  com.aspose.psd.RectangleF  berbeda dalam lokasi atau ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF yang berada di sebelah kiri operator ketidaksamaan. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur com.aspose.psd.RectangleF yang berada di sebelah kanan operator ketidaksamaan. |

**Returns:**
boolean - Operator ini mengembalikan true jika salah satu properti com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width, atau com.aspose.psd.RectangleF.Height dari dua struktur com.aspose.psd.RectangleF tidak sama; jika tidak false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Mengimplementasikan operator \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang. |
| pengganda | float | Pengganda. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari  com.aspose.psd.RectangleF.Y  dan  com.aspose.psd.RectangleF.Height  pada struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari  com.aspose.psd.RectangleF.X  dan  com.aspose.psd.RectangleF.Width  dari struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Mendapatkan atau mengatur ukuran dari  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Mendapatkan atau mengatur lebar dari struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.RectangleF  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Mengonversi [RectangleF](../../com.aspose.psd/rectanglef) menjadi struktur [Rectangle](../../com.aspose.psd/rectangle) dengan nilai persegi panjang yang dipotong.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Mengonversi atribut dari  com.aspose.psd.RectangleF  ini menjadi string yang dapat dibaca manusia.

**Returns:**
java.lang.String - String yang berisi posisi, lebar, dan tinggi dari struktur com.aspose.psd.RectangleF ini.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Mengonversi struktur  com.aspose.psd.Rectangle  yang ditentukan menjadi struktur  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Struktur com.aspose.psd.Rectangle yang akan dikonversi. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Membuat persegi panjang ketiga terkecil yang dapat menampung kedua persegi panjang yang membentuk sebuah union.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang pertama untuk digabungkan. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Persegi panjang kedua untuk digabungkan. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

