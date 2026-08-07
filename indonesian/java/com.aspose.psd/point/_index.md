---
title: "Point"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili pasangan terurut koordinat x dan y integer yang mendefinisikan sebuah titik dalam bidang dua dimensi."
type: docs
weight: 82
url: /id/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Mewakili pasangan terurut koordinat x dan y integer yang mendefinisikan sebuah titik dalam bidang dua dimensi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Menginisialisasi instance baru dari struktur Aspose.Imaging.Point dengan koordinat yang ditentukan. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Menginisialisasi instance baru dari struktur Aspose.Imaging.Point dari struktur Aspose.Imaging.Size. |
| [Point(int dw)](#Point-int-) | Menginisialisasi instance baru dari struktur Aspose.Imaging.Point menggunakan koordinat yang ditentukan oleh nilai integer. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Mewakili format titik. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Menambahkan Aspose.Imaging.Size yang ditentukan ke Aspose.Imaging.Point yang ditentukan. |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi Aspose.Imaging.Point dengan membulatkan nilai-nilai Aspose.Imaging.PointF ke nilai integer berikutnya yang lebih tinggi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Aspose.Imaging.Point ini berisi koordinat yang sama dengan System.Object yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Mendapatkan instance baru dari struktur Aspose.Imaging.Point yang memiliki nilai Aspose.Imaging.Point.X dan Aspose.Imaging.Point.Y diatur ke nol. |
| [getX()](#getX--) | Mendapatkan atau mengatur koordinat x dari Aspose.Imaging.Point ini. |
| [getY()](#getY--) | Mendapatkan atau mengatur koordinat y dari Aspose.Imaging.Point ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk Aspose.Imaging.Point ini. |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah Aspose.Imaging.Point ini kosong. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Menerjemahkan Aspose.Imaging.Point ini dengan Aspose.Imaging.Point yang ditentukan. |
| [offset(int dx, int dy)](#offset-int-int-) | Menerjemahkan Aspose.Imaging.Point ini dengan jumlah yang ditentukan. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Menerjemahkan Aspose.Imaging.Point dengan Aspose.Imaging.Size yang diberikan. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Membandingkan dua objek Aspose.Imaging.Point. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Membandingkan dua objek Aspose.Imaging.Point. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Menerjemahkan Aspose.Imaging.Point dengan nilai negatif dari Aspose.Imaging.Size yang diberikan. |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi objek Aspose.Imaging.Point dengan membulatkan nilai Aspose.Imaging.Point ke integer terdekat. |
| [setX(int value)](#setX-int-) | Mendapatkan atau mengatur koordinat x dari Aspose.Imaging.Point ini. |
| [setY(int value)](#setY-int-) | Mendapatkan atau mengatur koordinat y dari Aspose.Imaging.Point ini. |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Mengembalikan hasil pengurangan Aspose.Imaging.Size yang ditentukan dari Aspose.Imaging.Point yang ditentukan. |
| [toString()](#toString--) | Mengonversi Aspose.Imaging.Point ini menjadi string yang dapat dibaca manusia. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Mengonversi struktur Point yang ditentukan menjadi struktur PointF. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Mengonversi struktur Aspose.Imaging.Point yang ditentukan menjadi struktur Aspose.Imaging.Size. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi Aspose.Imaging.Point dengan memotong nilai-nilai Aspose.Imaging.Point. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Menginisialisasi instance baru dari struktur Aspose.Imaging.Point dengan koordinat yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Posisi horizontal titik. |
| y | int | Posisi vertikal titik. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Menginisialisasi instance baru dari struktur Aspose.Imaging.Point dari struktur Aspose.Imaging.Size.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Berisi koordinat titik baru. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Menginisialisasi instance baru dari struktur Aspose.Imaging.Point menggunakan koordinat yang ditentukan oleh nilai integer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dw | int | Integer 32-bit yang menentukan koordinat untuk titik baru. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Mewakili format titik.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Menambahkan Aspose.Imaging.Size yang ditentukan ke Aspose.Imaging.Point yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point yang akan ditambahkan. |
| size | [Size](../../com.aspose.psd/size) | Ukuran  Aspose.Imaging.Size  untuk ditambahkan ke  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi Aspose.Imaging.Point dengan membulatkan nilai-nilai Aspose.Imaging.PointF ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Yang  Aspose.Imaging.PointF  untuk dikonversi. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Aspose.Imaging.Point ini berisi koordinat yang sama dengan System.Object yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan diuji. |

**Returns:**
boolean - True jika  obj  adalah  Aspose.Imaging.Point  dan memiliki koordinat yang sama dengan  Aspose.Imaging.Point  ini.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Mendapatkan instance baru dari struktur Aspose.Imaging.Point yang memiliki nilai Aspose.Imaging.Point.X dan Aspose.Imaging.Point.Y diatur ke nol.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Mendapatkan atau mengatur koordinat x dari Aspose.Imaging.Point ini.

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Mendapatkan atau mengatur koordinat y dari Aspose.Imaging.Point ini.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk Aspose.Imaging.Point ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah Aspose.Imaging.Point ini kosong.

**Returns:**
boolean - True jika kedua  Aspose.Imaging.Point.X  dan  Aspose.Imaging.Point.Y  adalah 0; jika tidak, false.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

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




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Menerjemahkan Aspose.Imaging.Point ini dengan Aspose.Imaging.Point yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Aspose.Imaging.Point  digunakan untuk mengoffset  Aspose.Imaging.Point  ini. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Menerjemahkan Aspose.Imaging.Point ini dengan jumlah yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | int | Jumlah untuk mengoffset koordinat x. |
| dy | int | Jumlah untuk mengoffset koordinat y. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Menerjemahkan Aspose.Imaging.Point dengan Aspose.Imaging.Size yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Aspose.Imaging.Point  untuk diterjemahkan. |
| size | [Size](../../com.aspose.psd/size) | Sebuah  Aspose.Imaging.Size  yang menentukan pasangan angka untuk ditambahkan ke koordinat  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Membandingkan dua  Aspose.Imaging.Point  objek. Hasil menentukan apakah nilai properti  Aspose.Imaging.Point.X  dan  Aspose.Imaging.Point.Y  dari dua  Aspose.Imaging.Point  objek tersebut sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Sebuah  Aspose.Imaging.Point  pertama untuk dibandingkan. |
| point2 | [Point](../../com.aspose.psd/point) | Sebuah  Aspose.Imaging.Point  kedua untuk dibandingkan. |

**Returns:**
boolean - True jika  Aspose.Imaging.Point.X  dan  Aspose.Imaging.Point.Y  nilai dari  point1  dan  point2  sama; jika tidak, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Membandingkan dua  Aspose.Imaging.Point  objek. Hasil menentukan apakah nilai properti  Aspose.Imaging.Point.X  atau  Aspose.Imaging.Point.Y  dari dua  Aspose.Imaging.Point  objek tidak sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Sebuah  Aspose.Imaging.Point  pertama untuk dibandingkan. |
| point2 | [Point](../../com.aspose.psd/point) | Sebuah  Aspose.Imaging.Point  kedua untuk dibandingkan. |

**Returns:**
boolean - True jika nilai properti  Aspose.Imaging.Point.X  atau  Aspose.Imaging.Point.Y  dari  point1  dan  point2  berbeda; jika tidak, false.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Menerjemahkan Aspose.Imaging.Point dengan nilai negatif dari Aspose.Imaging.Size yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Aspose.Imaging.Point  untuk diterjemahkan. |
| size | [Size](../../com.aspose.psd/size) | Sebuah  Aspose.Imaging.Size  yang menentukan pasangan angka untuk dikurangkan dari koordinat  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi objek Aspose.Imaging.Point dengan membulatkan nilai Aspose.Imaging.Point ke integer terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Yang  Aspose.Imaging.PointF  untuk dikonversi. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Mendapatkan atau mengatur koordinat x dari Aspose.Imaging.Point ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Mendapatkan atau mengatur koordinat y dari Aspose.Imaging.Point ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Mengembalikan hasil pengurangan Aspose.Imaging.Size yang ditentukan dari Aspose.Imaging.Point yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Aspose.Imaging.Point  akan dikurangkan dari. |
| size | [Size](../../com.aspose.psd/size) | Yang  Aspose.Imaging.Size  untuk dikurangkan dari  point . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Mengonversi Aspose.Imaging.Point ini menjadi string yang dapat dibaca manusia.

**Returns:**
java.lang.String - Sebuah  System.String  yang mewakili instance ini.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Mengonversi struktur Point yang ditentukan menjadi struktur PointF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Point  akan dikonversi. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Mengonversi struktur Aspose.Imaging.Point yang ditentukan menjadi struktur Aspose.Imaging.Size.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Yang  Aspose.Imaging.Point  akan dikonversi. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Mengonversi Aspose.Imaging.PointF yang ditentukan menjadi Aspose.Imaging.Point dengan memotong nilai-nilai Aspose.Imaging.Point.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Yang  Aspose.Imaging.PointF  untuk dikonversi. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

