---
title: "Size"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili ukuran."
type: docs
weight: 98
url: /id/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Mewakili ukuran.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | Menginisialisasi sebuah instance baru dari struktur  Aspose.Imaging.Size  dari  Aspose.Imaging.Point  yang ditentukan. |
| [Size(int width, int height)](#Size-int-int-) | Menginisialisasi sebuah instance baru dari struktur  Aspose.Imaging.Size  dari dimensi yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | Menambahkan lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  ke lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya. |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan membulatkan nilai-nilai struktur  Aspose.Imaging.Size  ke nilai integer berikutnya yang lebih tinggi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menguji untuk melihat apakah objek yang ditentukan adalah  Aspose.Imaging.Size  dengan dimensi yang sama dengan  Aspose.Imaging.Size . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Mendapatkan instance baru dari struktur  Aspose.Imaging.Size  yang memiliki nilai  Aspose.Imaging.Size.Width  dan  Aspose.Imaging.Size.Height  diatur ke nol. |
| [getHeight()](#getHeight--) | Mendapatkan atau mengatur komponen vertikal dari  Aspose.Imaging.Size  ini. |
| [getWidth()](#getWidth--) | Mendapatkan atau mengatur komponen horizontal dari  Aspose.Imaging.Size  ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk struktur  Aspose.Imaging.Size  ini. |
| [isEmpty()](#isEmpty--) | Mendapatkan nilai yang menunjukkan apakah  Aspose.Imaging.Size  ini memiliki lebar dan tinggi sebesar 0. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | Menambahkan lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  ke lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | Menguji apakah dua struktur  Aspose.Imaging.Size  sama. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | Menguji apakah dua struktur  Aspose.Imaging.Size  berbeda. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | Mengurangi lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  dari lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya. |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan membulatkan nilai-nilai struktur  Aspose.Imaging.SizeF  ke nilai integer terdekat. |
| [setHeight(int value)](#setHeight-int-) | Mendapatkan atau mengatur komponen vertikal dari  Aspose.Imaging.Size  ini. |
| [setWidth(int value)](#setWidth-int-) | Mendapatkan atau mengatur komponen horizontal dari  Aspose.Imaging.Size  ini. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | Mengurangi lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  dari lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya. |
| [toString()](#toString--) | Membuat string yang dapat dibaca manusia yang mewakili  Aspose.Imaging.Size  ini. |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | Mengonversi  Aspose.Imaging.Size  yang ditentukan menjadi  Aspose.Imaging.Point . |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | Mengonversi  Aspose.Imaging.Size  yang ditentukan menjadi  Aspose.Imaging.SizeF . |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan memotong nilai-nilai struktur  Aspose.Imaging.SizeF  ke nilai integer terdekat yang lebih rendah. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


Menginisialisasi sebuah instance baru dari struktur  Aspose.Imaging.Size  dari  Aspose.Imaging.Point  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Aspose.Imaging.Point  yang digunakan untuk menginisialisasi  Aspose.Imaging.Size  ini. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Menginisialisasi sebuah instance baru dari struktur  Aspose.Imaging.Size  dari dimensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Komponen lebar dari  Aspose.Imaging.Size  baru. |
| tinggi | int | Komponen tinggi dari  Aspose.Imaging.Size  baru. |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


Menambahkan lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  ke lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size  pertama untuk ditambahkan. |
| size2 | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size  kedua untuk ditambahkan. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan membulatkan nilai-nilai struktur  Aspose.Imaging.Size  ke nilai integer berikutnya yang lebih tinggi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Struktur  Aspose.Imaging.SizeF  untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menguji untuk melihat apakah objek yang ditentukan adalah  Aspose.Imaging.Size  dengan dimensi yang sama dengan  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan diuji. |

**Returns:**
boolean - True jika  obj  adalah  Aspose.Imaging.Size  dan memiliki lebar serta tinggi yang sama dengan  Aspose.Imaging.Size  ini; jika tidak, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Mendapatkan instance baru dari struktur  Aspose.Imaging.Size  yang memiliki nilai  Aspose.Imaging.Size.Width  dan  Aspose.Imaging.Size.Height  diatur ke nol.

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Mendapatkan atau mengatur komponen vertikal dari  Aspose.Imaging.Size  ini.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Mendapatkan atau mengatur komponen horizontal dari  Aspose.Imaging.Size  ini.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk struktur  Aspose.Imaging.Size  ini.

**Returns:**
int - Nilai integer yang menentukan nilai hash untuk struktur  Aspose.Imaging.Size  ini.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Mendapatkan nilai yang menunjukkan apakah  Aspose.Imaging.Size  ini memiliki lebar dan tinggi sebesar 0.

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Menambahkan lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  ke lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size  pertama untuk ditambahkan. |
| size2 | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size  kedua untuk ditambahkan. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Menguji apakah dua struktur  Aspose.Imaging.Size  sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | Struktur  Aspose.Imaging.Size  di sisi kiri operator kesetaraan. |
| size2 | [Size](../../com.aspose.psd/size) | Struktur  Aspose.Imaging.Size  di sisi kanan operator kesetaraan. |

**Returns:**
boolean - True jika  size1  dan  size2  memiliki lebar dan tinggi yang sama; jika tidak, false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Menguji apakah dua struktur  Aspose.Imaging.Size  berbeda.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sebelah kiri operator ketidaksamaan. |
| size2 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sebelah kanan operator ketidaksamaan. |

**Returns:**
boolean - True jika size1 dan size2 berbeda baik dalam lebar maupun tinggi; false jika size1 dan size2 sama.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Mengurangi lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  dari lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sisi kiri operator pengurangan. |
| size2 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sisi kanan operator pengurangan. |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan membulatkan nilai-nilai struktur  Aspose.Imaging.SizeF  ke nilai integer terdekat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Struktur  Aspose.Imaging.SizeF  untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Mendapatkan atau mengatur komponen vertikal dari  Aspose.Imaging.Size  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Mendapatkan atau mengatur komponen horizontal dari  Aspose.Imaging.Size  ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Mengurangi lebar dan tinggi dari satu struktur  Aspose.Imaging.Size  dari lebar dan tinggi struktur  Aspose.Imaging.Size  lainnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sisi kiri operator pengurangan. |
| size2 | [Size](../../com.aspose.psd/size) | The Struktur Aspose.Imaging.Size di sisi kanan operator pengurangan. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Membuat string yang dapat dibaca manusia yang mewakili  Aspose.Imaging.Size  ini.

**Returns:**
java.lang.String - Sebuah string yang mewakili Aspose.Imaging.Size ini.
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


Mengonversi  Aspose.Imaging.Size  yang ditentukan menjadi  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size yang akan dikonversi. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


Mengonversi  Aspose.Imaging.Size  yang ditentukan menjadi  Aspose.Imaging.SizeF .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Aspose.Imaging.Size yang akan dikonversi. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


Mengonversi struktur  Aspose.Imaging.SizeF  yang ditentukan menjadi struktur  Aspose.Imaging.Size  dengan memotong nilai-nilai struktur  Aspose.Imaging.SizeF  ke nilai integer terdekat yang lebih rendah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Struktur  Aspose.Imaging.SizeF  untuk dikonversi. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

