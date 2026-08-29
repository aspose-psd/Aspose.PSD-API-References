---
title: "Rectangle"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Menyimpan sekumpulan empat bilangan bulat yang mewakili lokasi dan ukuran sebuah persegi panjang."
type: docs
weight: 88
url: /id/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Menyimpan sekumpulan empat bilangan bulat yang mewakili lokasi dan ukuran sebuah persegi panjang.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Menginisialisasi instance baru dari struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang ditentukan. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Menginisialisasi instance baru dari struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Mengonversi struktur  com.aspose.psd.RectangleF  yang ditentukan menjadi struktur  com.aspose.psd.Rectangle  dengan membulatkan nilai  com.aspose.psd.RectangleF  ke nilai integer berikutnya yang lebih tinggi. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.Rectangle  ini. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh  rect  sepenuhnya berada di dalam struktur  com.aspose.psd.Rectangle  ini. |
| [contains(int x, int y)](#contains-int-int-) | Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.Rectangle  ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji apakah  obj  adalah struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang sama dengan struktur  com.aspose.psd.Rectangle  ini. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Membuat struktur  com.aspose.psd.Rectangle  dengan lokasi tepi yang ditentukan. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Membuat  Rectangle  baru dari dua titik yang ditentukan. |
| [getBottom()](#getBottom--) | Mendapatkan atau mengatur koordinat y yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  dari struktur  com.aspose.psd.Rectangle  ini. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Mendapatkan instance baru dari struktur  com.aspose.psd.Rectangle  yang memiliki nilai  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  dan  com.aspose.psd.Rectangle.Height  diatur menjadi nol. |
| [getHeight()](#getHeight--) | Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.Rectangle  ini. |
| [getLeft()](#getLeft--) | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini. |
| [getLocation()](#getLocation--) | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini. |
| [getRight()](#getRight--) | Mendapatkan atau mengatur koordinat x yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari struktur  com.aspose.psd.Rectangle  ini. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran dari  com.aspose.psd.Rectangle  ini. |
| [getTop()](#getTop--) | Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar dari struktur  com.aspose.psd.Rectangle  ini. |
| [getX()](#getX--) | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini. |
| [getY()](#getY--) | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk struktur  com.aspose.psd.Rectangle  ini. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Membuat dan mengembalikan salinan yang diperluas dari struktur  com.aspose.psd.Rectangle  yang ditentukan. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Memperluas  com.aspose.psd.Rectangle  ini sebesar jumlah yang ditentukan. |
| [inflate(int width, int height)](#inflate-int-int-) | Memperluas  com.aspose.psd.Rectangle  ini sebesar jumlah yang ditentukan. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Mengganti  com.aspose.psd.Rectangle  ini dengan irisan antara dirinya sendiri dan  com.aspose.psd.Rectangle  yang ditentukan. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Mengembalikan struktur  com.aspose.psd.Rectangle  ketiga yang merepresentasikan irisan antara dua struktur  com.aspose.psd.Rectangle  lainnya. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Menentukan apakah persegi panjang ini berpotongan dengan  rect . |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari  com.aspose.psd.Rectangle  ini memiliki nilai nol. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Mendapatkan nilai yang menunjukkan apakah  Rectangle  ini setidaknya sebagian terlihat |
| [normalize()](#normalize--) | Menormalkan persegi panjang dengan membuat lebar dan tingginya positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [offset(int x, int y)](#offset-int-int-) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Menguji apakah dua struktur  com.aspose.psd.Rectangle  memiliki lokasi dan ukuran yang sama. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Menguji apakah dua struktur  com.aspose.psd.Rectangle  berbeda dalam lokasi atau ukuran. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Mengonversi  com.aspose.psd.RectangleF  yang ditentukan menjadi  com.aspose.psd.Rectangle  dengan membulatkan nilai  com.aspose.psd.RectangleF  ke nilai integer terdekat. |
| [setBottom(int value)](#setBottom-int-) | Mendapatkan atau mengatur koordinat y yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  dari struktur  com.aspose.psd.Rectangle  ini. |
| [setHeight(int value)](#setHeight-int-) | Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.Rectangle  ini. |
| [setLeft(int value)](#setLeft-int-) | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini. |
| [setRight(int value)](#setRight-int-) | Mendapatkan atau mengatur koordinat x yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari struktur  com.aspose.psd.Rectangle  ini. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Mendapatkan atau mengatur ukuran dari  com.aspose.psd.Rectangle  ini. |
| [setTop(int value)](#setTop-int-) | Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini. |
| [setWidth(int value)](#setWidth-int-) | Mengatur lebar struktur  com.aspose.psd.Rectangle  ini. |
| [setX(int value)](#setX-int-) | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini. |
| [setY(int value)](#setY-int-) | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini. |
| [toString()](#toString--) | Mengonversi atribut dari  com.aspose.psd.Rectangle  ini menjadi string yang dapat dibaca manusia. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Mengonversi  com.aspose.psd.RectangleF  yang ditentukan menjadi  com.aspose.psd.Rectangle  dengan memotong nilai  com.aspose.psd.RectangleF . |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Mendapatkan struktur  com.aspose.psd.Rectangle  yang berisi gabungan dari dua struktur  com.aspose.psd.Rectangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Menginisialisasi instance baru dari struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang. |
| lebar | int | Lebar persegi panjang. |
| tinggi | int | Tinggi persegi panjang. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Menginisialisasi instance baru dari struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Sebuah  com.aspose.psd.Point  yang mewakili sudut kiri-atas dari wilayah persegi panjang. |
| size | [Size](../../com.aspose.psd/size) | Sebuah  com.aspose.psd.Size  yang mewakili lebar dan tinggi wilayah persegi panjang. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Mengonversi struktur  com.aspose.psd.RectangleF  yang ditentukan menjadi struktur  com.aspose.psd.Rectangle  dengan membulatkan nilai  com.aspose.psd.RectangleF  ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Struktur  com.aspose.psd.RectangleF  yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) |   com.aspose.psd.Point  yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang direpresentasikan oleh  point  berada dalam struktur  com.aspose.psd.Rectangle  ini; jika tidak false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh  rect  sepenuhnya berada di dalam struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) |   com.aspose.psd.Rectangle  yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika wilayah persegi panjang yang direpresentasikan oleh  rect  sepenuhnya berada dalam struktur  com.aspose.psd.Rectangle  ini; jika tidak false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Menentukan apakah titik yang ditentukan berada di dalam struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang didefinisikan oleh  x  dan  y  berada dalam struktur  com.aspose.psd.Rectangle  ini; jika tidak false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menguji apakah  obj  adalah struktur  com.aspose.psd.Rectangle  dengan lokasi dan ukuran yang sama dengan struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika  obj  adalah struktur  com.aspose.psd.Rectangle  dan properti  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , serta  com.aspose.psd.Rectangle.Height ‑nya sama dengan properti yang bersesuaian pada struktur  com.aspose.psd.Rectangle  ini; jika tidak, false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Membuat struktur  com.aspose.psd.Rectangle  dengan lokasi tepi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kiri | int | Koordinat x dari sudut kiri-atas struktur  com.aspose.psd.Rectangle  ini. |
| atas | int | Koordinat y dari sudut kiri-atas struktur  com.aspose.psd.Rectangle  ini. |
| kanan | int | Koordinat x dari sudut kanan-bawah struktur  com.aspose.psd.Rectangle  ini. |
| bawah | int | Koordinat y dari sudut kanan-bawah struktur  com.aspose.psd.Rectangle  ini. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Membuat sebuah  Rectangle  baru dari dua titik yang ditentukan. Dua sisi vertikal dari  Rectangle  yang dibuat akan sama dengan  point1  dan  point2 . Ini biasanya merupakan titik yang berlawanan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Point pertama untuk rectangle baru. |
| point2 | [Point](../../com.aspose.psd/point) | Point kedua untuk rectangle baru. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Mendapatkan atau mengatur koordinat y yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  dari struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat y yang merupakan hasil penjumlahan  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  dari  com.aspose.psd.Rectangle  ini.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Mendapatkan instance baru dari struktur  com.aspose.psd.Rectangle  yang memiliki nilai  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  dan  com.aspose.psd.Rectangle.Height  diatur menjadi nol.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Tinggi struktur  com.aspose.psd.Rectangle  ini.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Mendapatkan atau mengatur koordinat x yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat x yang merupakan hasil penjumlahan  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari  com.aspose.psd.Rectangle  ini.
### getSize() {#getSize--}
```
public Size getSize()
```


Mendapatkan atau mengatur ukuran dari  com.aspose.psd.Rectangle  ini.

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan lebar dari struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Lebar dari struktur  com.aspose.psd.Rectangle  ini.
### getX() {#getX--}
```
public int getX()
```


Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat x dari sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini.
### getY() {#getY--}
```
public int getY()
```


Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Koordinat y dari sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk struktur  com.aspose.psd.Rectangle  ini.

**Returns:**
int - Sebuah integer yang merepresentasikan kode hash untuk persegi panjang ini.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Membuat dan mengembalikan salinan yang diperbesar dari struktur  com.aspose.psd.Rectangle  yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Struktur  com.aspose.psd.Rectangle  asli tetap tidak berubah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle yang akan dijadikan awal. Persegi panjang ini tidak diubah. |
| x | int | Jumlah untuk memperbesar  com.aspose.psd.Rectangle  ini secara horizontal. |
| y | int | Jumlah untuk memperbesar  com.aspose.psd.Rectangle  ini secara vertikal. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Memperluas  com.aspose.psd.Rectangle  ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Jumlah untuk memperluas rectangle ini. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Memperluas  com.aspose.psd.Rectangle  ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Jumlah untuk memperbesar  com.aspose.psd.Rectangle  ini secara horizontal. |
| tinggi | int | Jumlah untuk memperbesar  com.aspose.psd.Rectangle  ini secara vertikal. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Mengganti  com.aspose.psd.Rectangle  ini dengan irisan antara dirinya sendiri dan  com.aspose.psd.Rectangle  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | com.aspose.psd.Rectangle yang akan diinterseksi. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Mengembalikan struktur  com.aspose.psd.Rectangle  ketiga yang mewakili interseksi dari dua struktur  com.aspose.psd.Rectangle  lainnya. Jika tidak ada interseksi, sebuah  com.aspose.psd.Rectangle  kosong dikembalikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle pertama untuk diinterseksikan. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle kedua untuk diinterseksikan. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Menentukan apakah persegi panjang ini berpotongan dengan  rect .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rectangle untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika ada interseksi apa pun, jika tidak false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari  com.aspose.psd.Rectangle  ini memiliki nilai nol.

**Returns:**
boolean - Properti ini mengembalikan true jika properti  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , dan  com.aspose.psd.Rectangle.Y  dari  com.aspose.psd.Rectangle  ini semuanya bernilai nol; jika tidak, false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Mendapatkan nilai yang menunjukkan apakah  Rectangle  ini setidaknya sebagian terlihat

**Returns:**
boolean - true jika  Rectangle  ini setidaknya sebagian terlihat; jika tidak, false.
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Jumlah untuk menggeser lokasi. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Offset horizontal. |
| y | int | Offset vertikal. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Menguji apakah dua struktur  com.aspose.psd.Rectangle  memiliki lokasi dan ukuran yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  yang berada di sebelah kiri operator kesetaraan. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  yang berada di sebelah kanan operator kesetaraan. |

**Returns:**
boolean - Operator ini mengembalikan true jika dua struktur  com.aspose.psd.Rectangle  memiliki properti  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , dan  com.aspose.psd.Rectangle.Height  yang sama.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Menguji apakah dua struktur  com.aspose.psd.Rectangle  berbeda dalam lokasi atau ukuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  yang berada di sebelah kiri operator ketidaksamaan. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Struktur  com.aspose.psd.Rectangle  yang berada di sebelah kanan operator ketidaksamaan. |

**Returns:**
boolean - Operator ini mengembalikan true jika salah satu properti  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  atau  com.aspose.psd.Rectangle.Height  dari dua struktur  com.aspose.psd.Rectangle  tidak sama; jika tidak false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Mengonversi  com.aspose.psd.RectangleF  yang ditentukan menjadi  com.aspose.psd.Rectangle  dengan membulatkan nilai  com.aspose.psd.RectangleF  ke nilai integer terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Mendapatkan atau mengatur koordinat y yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  dari struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat y yang merupakan hasil penjumlahan dari  com.aspose.psd.Rectangle.Y  dan  com.aspose.psd.Rectangle.Height  pada  com.aspose.psd.Rectangle  ini. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Mendapatkan atau mengatur tinggi dari struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Tinggi dari struktur  com.aspose.psd.Rectangle  ini. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Mendapatkan atau mengatur koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat x dari tepi kiri struktur  com.aspose.psd.Rectangle  ini. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Sebuah  Point  yang mewakili sudut kiri atas dari struktur  com.aspose.psd.Rectangle  ini. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Mendapatkan atau mengatur koordinat x yang merupakan hasil penjumlahan nilai properti  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat x yang merupakan hasil penjumlahan  com.aspose.psd.Rectangle.X  dan  com.aspose.psd.Rectangle.Width  dari struktur  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Mendapatkan atau mengatur ukuran dari  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Sebuah  com.aspose.psd.Size  yang mewakili lebar dan tinggi dari struktur  com.aspose.psd.Rectangle  ini. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Mendapatkan atau mengatur koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat y dari tepi atas struktur  com.aspose.psd.Rectangle  ini. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Mengatur lebar struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Lebar dari struktur  com.aspose.psd.Rectangle  ini. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat x dari sudut kiri-atas struktur  com.aspose.psd.Rectangle  ini. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur  com.aspose.psd.Rectangle  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Koordinat y dari sudut kiri-atas struktur  com.aspose.psd.Rectangle  ini. |

### toString() {#toString--}
```
public String toString()
```


Mengonversi atribut dari  com.aspose.psd.Rectangle  ini menjadi string yang dapat dibaca manusia.

**Returns:**
java.lang.String - Sebuah string yang berisi posisi, lebar, dan tinggi dari struktur  com.aspose.psd.Rectangle  ini.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Mengonversi  com.aspose.psd.RectangleF  yang ditentukan menjadi  com.aspose.psd.Rectangle  dengan memotong nilai  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | com.aspose.psd.RectangleF yang akan dikonversi. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Mendapatkan struktur  com.aspose.psd.Rectangle  yang berisi gabungan dari dua struktur  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang pertama untuk digabungkan. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang kedua untuk digabungkan. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

