---
title: "Pen"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan objek yang digunakan untuk menggambar garis, kurva, dan bentuk."
type: docs
weight: 77
url: /id/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Mendefinisikan objek yang digunakan untuk menggambar garis, kurva, dan gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Menginisialisasi instance baru dari kelas  Pen  dengan warna yang ditentukan. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Menginisialisasi instance baru dari kelas  Pen  dengan properti  Color  dan  Pen.Width  yang ditentukan. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Menginisialisasi instance baru dari kelas  Pen  dengan  Brush  yang ditentukan. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Menginisialisasi instance baru dari kelas  Pen  dengan  Brush  dan  Pen.Width  yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Mendapatkan perataan untuk  Pen  ini. |
| [getBrush()](#getBrush--) | Mendapatkan  Brush  yang menentukan atribut  Pen  ini. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Mendapatkan warna  Pen  ini. |
| [getCompoundArray()](#getCompoundArray--) | Mendapatkan array nilai yang menentukan pena komposit. |
| [getCustomEndCap()](#getCustomEndCap--) | Mendapatkan cap khusus untuk digunakan di akhir garis yang digambar dengan  Pen  ini. |
| [getCustomStartCap()](#getCustomStartCap--) | Mendapatkan cap khusus untuk digunakan di awal garis yang digambar dengan  Pen  ini. |
| [getDashCap()](#getDashCap--) | Mendapatkan gaya cap yang digunakan di akhir dash yang membentuk garis bergaris yang digambar dengan  Pen  ini. |
| [getDashOffset()](#getDashOffset--) | Mendapatkan jarak dari awal garis ke permulaan pola dash. |
| [getDashPattern()](#getDashPattern--) | Mendapatkan array dash khusus dan spasi. |
| [getDashStyle()](#getDashStyle--) | Mendapatkan gaya yang digunakan untuk garis bergaris yang digambar dengan  Pen  ini. |
| [getEndCap()](#getEndCap--) | Mendapatkan gaya cap yang digunakan di akhir garis yang digambar dengan  Pen  ini. |
| [getLineJoin()](#getLineJoin--) | Mendapatkan gaya sambungan untuk ujung dua garis berurutan yang digambar dengan  Pen  ini. |
| [getMiterLimit()](#getMiterLimit--) | Mendapatkan batas ketebalan sambungan pada sudut miter. |
| [getOpacity()](#getOpacity--) | Mendapatkan opasitas objek. |
| [getPenType()](#getPenType--) | Mendapatkan gaya garis yang digambar dengan  Pen  ini. |
| [getStartCap()](#getStartCap--) | Mendapatkan gaya cap yang digunakan di awal garis yang digambar dengan  Pen  ini. |
| [getTransform()](#getTransform--) | Mendapatkan salinan transformasi geometrik untuk  Pen  ini. |
| [getWidth()](#getWidth--) | Mendapatkan lebar  Pen  ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Mengalikan matriks transformasi untuk  Pen  ini dengan  Matrix  yang ditentukan. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Mengalikan matriks transformasi untuk  Pen  ini dengan  Matrix  yang ditentukan dalam urutan yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Mengatur ulang matriks transformasi geometris untuk Pen ini menjadi identitas. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Memutar transformasi geometris lokal sebesar sudut yang ditentukan. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Memutar transformasi geometris lokal sebesar sudut yang ditentukan dalam urutan yang ditentukan. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Menskalakan transformasi geometris lokal dengan faktor yang ditentukan dalam urutan yang ditentukan. |
| [setAlignment(int value)](#setAlignment-int-) | Mengatur perataan untuk Pen ini. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Mengatur Brush yang menentukan atribut Pen ini. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Mengatur warna Pen ini. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Mengatur array nilai yang menentukan pena gabungan. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Mengatur tutup khusus untuk digunakan di akhir garis yang digambar dengan Pen ini. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Mengatur tutup khusus untuk digunakan di awal garis yang digambar dengan Pen ini. |
| [setDashCap(int value)](#setDashCap-int-) | Mengatur gaya tutup yang digunakan di akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan Pen ini. |
| [setDashOffset(float value)](#setDashOffset-float-) | Mengatur jarak dari awal garis ke permulaan pola dash. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Mengatur array dash khusus dan spasi. |
| [setDashStyle(int value)](#setDashStyle-int-) | Mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan Pen ini. |
| [setEndCap(int value)](#setEndCap-int-) | Mengatur gaya tutup yang digunakan di akhir garis yang digambar dengan Pen ini. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Mengatur nilai yang menentukan gaya tutup yang digunakan untuk mengakhiri garis yang digambar oleh Pen ini. |
| [setLineJoin(int value)](#setLineJoin-int-) | Mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Mengatur batas ketebalan sambungan pada sudut miring. |
| [setOpacity(float value)](#setOpacity-float-) | Mengatur opasitas objek. |
| [setStartCap(int value)](#setStartCap-int-) | Mengatur gaya tutup yang digunakan di awal garis yang digambar dengan Pen ini. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Mengatur salinan transformasi geometris untuk Pen ini. |
| [setWidth(float value)](#setWidth-float-) | Mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Menginisialisasi instance baru dari kelas  Pen  dengan warna yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Struktur Color yang menunjukkan warna Pen ini. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Menginisialisasi instance baru dari kelas  Pen  dengan properti  Color  dan  Pen.Width  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Struktur Color yang menunjukkan warna Pen ini. |
| lebar | float | Nilai yang menunjukkan lebar Pen ini. |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Menginisialisasi instance baru dari kelas  Pen  dengan  Brush  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan properti isian Pen ini. |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Menginisialisasi instance baru dari kelas  Pen  dengan  Brush  dan  Pen.Width  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Brush yang menentukan karakteristik Pen ini. |
| lebar | float | Lebar Pen baru. |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Mendapatkan perataan untuk  Pen  ini.

**Returns:**
int - PenAlignment yang mewakili perataan untuk Pen ini.
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Mendapatkan  Brush  yang menentukan atribut  Pen  ini.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Mendapatkan warna  Pen  ini.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Mendapatkan array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan spasi.

**Returns:**
float[] - Array angka real yang menentukan array komposit. Elemen dalam array harus berurutan naik, tidak kurang dari 0, dan tidak lebih dari 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Mendapatkan cap khusus untuk digunakan di akhir garis yang digambar dengan  Pen  ini.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Mendapatkan cap khusus untuk digunakan di awal garis yang digambar dengan  Pen  ini.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Mendapatkan gaya cap yang digunakan di akhir dash yang membentuk garis bergaris yang digambar dengan  Pen  ini.

**Returns:**
int - Salah satu nilai DashCap yang mewakili gaya tutup yang digunakan di awal dan akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan Pen ini.
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Mendapatkan jarak dari awal garis ke permulaan pola dash.

**Returns:**
float - Jarak dari awal garis ke permulaan pola dash.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Mendapatkan array dash khusus dan spasi.

**Returns:**
float[] - Array angka real yang menentukan panjang dash dan spasi yang bergantian dalam garis putus-putus.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Mendapatkan gaya yang digunakan untuk garis bergaris yang digambar dengan  Pen  ini.

**Returns:**
int - DashStyle yang mewakili gaya yang digunakan untuk garis putus-putus yang digambar dengan Pen ini.
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Mendapatkan gaya cap yang digunakan di akhir garis yang digambar dengan  Pen  ini.

**Returns:**
int - Salah satu nilai LineCap yang mewakili gaya tutup yang digunakan di akhir garis yang digambar dengan Pen ini.
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Mendapatkan gaya sambungan untuk ujung dua garis berurutan yang digambar dengan  Pen  ini.

**Returns:**
int - LineJoin yang mewakili gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini.
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Mendapatkan batas ketebalan sambungan pada sudut miter.

**Returns:**
float - Batas ketebalan sambungan pada sudut miter.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Mendapatkan opasitas objek. Nilainya harus antara 0 dan 1. Nilai 0 berarti objek sepenuhnya terlihat, nilai 1 berarti objek sepenuhnya tidak tembus pandang.

**Returns:**
float - Nilai opasitas.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Mendapatkan gaya garis yang digambar dengan  Pen  ini.

**Returns:**
int - Enumerasi PenType yang menentukan gaya garis yang digambar dengan Pen ini.
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Mendapatkan gaya cap yang digunakan di awal garis yang digambar dengan  Pen  ini.

**Returns:**
int - Salah satu nilai LineCap yang mewakili gaya tutup yang digunakan di awal garis yang digambar dengan Pen ini.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Mendapatkan salinan transformasi geometrik untuk  Pen  ini.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Mendapatkan lebar  Pen  ini, dalam satuan objek Graphics yang digunakan untuk menggambar.

**Returns:**
float - Lebar Pen ini.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Mengalikan matriks transformasi untuk  Pen  ini dengan  Matrix  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Objek Matrix yang digunakan untuk mengalikan matriks transformasi. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Mengalikan matriks transformasi untuk  Pen  ini dengan  Matrix  yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix yang digunakan untuk mengalikan matriks transformasi. |
| urutan | int | Urutan pelaksanaan operasi perkalian. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Mengatur ulang matriks transformasi geometris untuk Pen ini menjadi identitas.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Memutar transformasi geometris lokal sebesar sudut yang ditentukan. Metode ini menambahkan rotasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Memutar transformasi geometris lokal sebesar sudut yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |
| urutan | int | MatrixOrder yang menentukan apakah menambahkan atau menempatkan di depan matriks rotasi. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Menskalakan transformasi geometris lokal dengan faktor yang ditentukan. Metode ini menambahkan matriks skala ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Menskalakan transformasi geometris lokal dengan faktor yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu x. |
| sy | float | Faktor yang digunakan untuk menskalakan transformasi pada arah sumbu y. |
| urutan | int | Sebuah MatrixOrder yang menentukan apakah akan menambahkan atau menempelkan matriks skala. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Mengatur perataan untuk Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Sebuah PenAlignment yang mewakili perataan untuk Pen ini. |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Mengatur Brush yang menentukan atribut Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Sebuah Brush yang menentukan atribut-atribut Pen ini. |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Mengatur warna Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Sebuah struktur Color yang mewakili warna Pen ini. |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Mengatur array nilai yang menentukan pena komposit. Pena komposit menggambar garis komposit yang terdiri dari garis paralel dan spasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float[] | Array angka real yang menentukan array komposit. Elemen-elemen dalam array harus dalam urutan naik, tidak kurang dari 0, dan tidak lebih dari 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Mengatur tutup khusus untuk digunakan di akhir garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Sebuah CustomLineCap yang mewakili penutup yang digunakan di akhir garis yang digambar dengan Pen ini. |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Mengatur tutup khusus untuk digunakan di awal garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Sebuah CustomLineCap yang mewakili penutup yang digunakan di awal garis yang digambar dengan Pen ini. |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Mengatur gaya tutup yang digunakan di akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Salah satu nilai DashCap yang mewakili gaya penutup yang digunakan di awal dan akhir garis putus-putus yang membentuk garis bergaris yang digambar dengan Pen ini. |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Mengatur jarak dari awal garis ke permulaan pola dash.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Jarak dari awal garis hingga permulaan pola dash. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Mengatur array dash khusus dan spasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float[] | Array angka real yang menentukan panjang dash dan spasi yang bergantian dalam garis bergaris. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Mengatur gaya yang digunakan untuk garis putus-putus yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Sebuah DashStyle yang mewakili gaya yang digunakan untuk garis bergaris yang digambar dengan Pen ini. |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Mengatur gaya tutup yang digunakan di akhir garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Salah satu nilai LineCap yang mewakili gaya penutup yang digunakan di akhir garis yang digambar dengan Pen ini. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Mengatur nilai yang menentukan gaya tutup yang digunakan untuk mengakhiri garis yang digambar oleh Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startCap | int | Sebuah LineCap yang mewakili gaya penutup yang digunakan di awal garis yang digambar dengan Pen ini. |
| endCap | int | Sebuah LineCap yang mewakili gaya penutup yang digunakan di akhir garis yang digambar dengan Pen ini. |
| dashCap | int | Sebuah LineCap yang mewakili gaya penutup yang digunakan di awal atau akhir garis bergaris yang digambar dengan Pen ini. |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Mengatur gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Sebuah LineJoin yang mewakili gaya sambungan untuk ujung dua garis berurutan yang digambar dengan Pen ini. |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Mengatur batas ketebalan sambungan pada sudut miring.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Batas ketebalan sambungan pada sudut miring. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Mengatur opasitas objek. Nilainya harus antara 0 dan 1. Nilai 0 berarti objek sepenuhnya terlihat, nilai 1 berarti objek sepenuhnya tidak tembus pandang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai opasitas. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Mengatur gaya tutup yang digunakan di awal garis yang digambar dengan Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Salah satu nilai LineCap yang mewakili gaya penutup yang digunakan di awal garis yang digambar dengan Pen ini. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Mengatur salinan transformasi geometris untuk Pen ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Salinan Matrix yang mewakili transformasi geometris untuk Pen ini. |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Mengatur lebar Pen ini, dalam satuan objek Graphics yang digunakan untuk menggambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Lebar Pen ini. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke depan transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Menerjemahkan transformasi geometris lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| urutan | int | Urutan (menyisipkan di awal atau menambahkan di akhir) penerapan translasi. |

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

