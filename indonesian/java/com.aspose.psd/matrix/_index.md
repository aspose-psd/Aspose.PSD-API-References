---
title: "Matrix"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mengganti Matrix GDI."
type: docs
weight: 69
url: /id/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Mengganti Matrix GDI+.

Sebagian besar algoritma diambil dari AffineTransform.java milik Sun. Nama-nama Java untuk elemen matriks yang digunakan secara internal. Pemetaan nama java ke .net beserta deskripsinya: m00 M11 Skala X m10 M12 Geser Y m01 M21 Geser X m11 M22 Skala Y m02 M31 Translasi X m12 M32 Translasi Y
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Matrix()](#Matrix--) | Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Menginisialisasi instance baru dari kelas Matrix. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Membuat salinan dari kelas Matrix. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Menginisialisasi instance baru dari kelas Aspose.Imaging.Matrix ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Menginisialisasi instance baru dari kelas Aspose.Imaging.Matrix ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan pembalikan gambar cermin tentang suatu sumbu yang mengubah sistem koordinat kanan-tangan menjadi sistem kiri-tangan selain konversi yang ditunjukkan oleh bit flag lainnya. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi dengan sudut sembarang selain konversi yang ditunjukkan oleh bit flag lainnya. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Skala umum mengalikan panjang vektor dengan jumlah yang berbeda pada arah x dan y tanpa mengubah sudut antara vektor tegak lurus. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Konstanta ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan konversi sewenang-wenang dari koordinat input. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Transformasi identitas adalah transformasi di mana koordinat output selalu sama dengan koordinat input. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Konstanta ini adalah masker bit untuk setiap bit flag rotasi. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Konstanta ini adalah masker bit untuk setiap bit flag skala. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi kuadran dengan kelipatan 90 derajat selain konversi yang ditunjukkan oleh bit flag lainnya. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Translasi memindahkan koordinat sebesar jumlah konstan pada x dan y tanpa mengubah panjang atau sudut vektor. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Skala seragam mengalikan panjang vektor dengan jumlah yang sama pada arah x dan y tanpa mengubah sudut antar vektor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah  System.Object  yang ditentukan sama dengan instance ini. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Mengambil salinan elemen matriks. |
| [getM11()](#getM11--) | Mengambil elemen matriks pada baris pertama kolom pertama. |
| [getM12()](#getM12--) | Mengambil elemen matriks pada baris pertama kolom kedua. |
| [getM21()](#getM21--) | Mengambil elemen matriks pada baris kedua kolom pertama. |
| [getM22()](#getM22--) | Mengambil elemen matriks pada baris kedua kolom kedua. |
| [getM31()](#getM31--) | Mengambil elemen matriks pada baris ketiga kolom pertama. |
| [getM32()](#getM32--) | Mengambil elemen matriks pada baris ketiga kolom pertama. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Menentukan apakah dua matriks sama. |
| [isIdentity()](#isIdentity--) | Mengembalikan `true` jika `AffineTransform` ini adalah transformasi identitas. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix menggunakan urutan Prepend (default). |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix, dan dalam urutan yang ditentukan dalam parameter order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Mengatur ulang Matrix ini sehingga memiliki elemen-elemen matriks identitas. |
| [rotate(float angle)](#rotate-float-) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan default (Prepend). |
| [rotate(float angle, int order)](#rotate-float-int-) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan yang ditentukan. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan default (Prepend). |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan yang ditentukan. |
| [scale(float sx, float sy)](#scale-float-float-) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan Prepend (default). |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan yang ditentukan. |
| [toString()](#toString--) | Mengembalikan sebuah  System.String  yang mewakili instance ini. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Menerapkan transformasi geometrik yang diwakili oleh Matrix ini ke array titik yang ditentukan. |
| [translate(float tx, float ty)](#translate-float-float-) | Menerapkan vektor translasi yang ditentukan ke Matrix ini menggunakan urutan (default) Prepend. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Menginisialisasi instance baru dari kelas Matrix.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Membuat salinan dari kelas Matrix.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | matriks dasar untuk penyesuaian |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Menginisialisasi instance baru dari kelas Aspose.Imaging.Matrix ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah struktur **Aspose.Imaging.RectangleF** yang mewakili persegi panjang yang akan diubah. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Sebuah array berisi tiga struktur **Aspose.Imaging.PointF** yang mewakili titik-titik sebuah paralelogram yang akan menjadi tujuan transformasi sudut kiri atas, kanan atas, dan kiri bawah persegi panjang. Sudut kanan bawah paralelogram diimplikasikan oleh tiga sudut pertama. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Menginisialisasi instance baru dari kelas Aspose.Imaging.Matrix ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Sebuah struktur **Aspose.Imaging.Rectangle** yang mewakili persegi panjang yang akan diubah. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Sebuah array berisi tiga struktur **Aspose.Imaging.Point** yang mewakili titik-titik sebuah paralelogram yang akan menjadi tujuan transformasi sudut kiri atas, kanan atas, dan kiri bawah persegi panjang. Sudut kanan bawah paralelogram diimplikasikan oleh tiga sudut pertama. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Bita flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan pembalikan cermin pada suatu sumbu yang mengubah sistem koordinat kanan (right handed) menjadi sistem koordinat kiri (left handed) selain konversi yang ditunjukkan oleh bita flag lainnya. Sistem koordinat kanan adalah sistem di mana sumbu X positif berputar berlawanan arah jarum jam untuk menumpuk pada sumbu Y positif, mirip dengan arah jari tangan kanan melengkung ketika Anda melihat ibu jari secara langsung. Sistem koordinat kiri adalah sistem di mana sumbu X positif berputar searah jarum jam untuk menumpuk pada sumbu Y positif, mirip dengan arah jari tangan kiri melengkung. Tidak ada cara matematis untuk menentukan sudut pembalikan atau pencerminan asli karena semua sudut pembalikan identik dengan rotasi penyesuaian yang tepat. CATATAN: TypeFlip ditambahkan setelah GENERAL\_TRANSFORM beredar secara publik dan bita flag tidak dapat lagi dinomori ulang secara nyaman tanpa memperkenalkan ketidakcocokan biner dalam kode eksternal.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Bita flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi dengan sudut sewenang-wenang selain konversi yang ditunjukkan oleh bita flag lainnya. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah asli vektor dan tanpa mengubah panjang vektor. Bita flag ini bersifat eksklusif dengan the

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Skala umum mengalikan panjang vektor dengan nilai yang berbeda pada arah x dan y tanpa mengubah sudut antara vektor yang tegak lurus. Bita flag ini bersifat eksklusif dengan flag TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Konstanta ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan konversi sewenang-wenang pada koordinat masukan. Jika transformasi ini dapat diklasifikasikan oleh salah satu konstanta di atas, tipenya akan menjadi konstanta **TypeIdentity** atau kombinasi bita flag yang sesuai untuk berbagai konversi koordinat yang dilakukan oleh transformasi ini.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Transformasi identitas adalah transformasi di mana koordinat keluaran selalu sama dengan koordinat masukan. Jika transformasi ini bukan transformasi identitas, tipenya akan menjadi konstanta **GENERAL\_TRANSFORM** atau kombinasi bita flag yang sesuai untuk berbagai konversi koordinat yang dilakukan oleh transformasi ini.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Konstanta ini adalah masker bit untuk setiap bit flag rotasi.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Konstanta ini adalah masker bit untuk setiap bit flag skala.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Bita flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi kuadran dengan kelipatan 90 derajat selain konversi yang ditunjukkan oleh bita flag lainnya. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah asli vektor dan tanpa mengubah panjang vektor. Bita flag ini bersifat eksklusif dengan flag **TypeGeneralRotation**.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Translasi memindahkan koordinat sebesar jumlah konstan pada x dan y tanpa mengubah panjang atau sudut vektor.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Skala seragam mengalikan panjang vektor dengan jumlah yang sama di kedua arah x dan y tanpa mengubah sudut antara vektor. Bit flag ini saling eksklusif dengan flag TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah  System.Object  yang ditentukan sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | System.Object yang akan dibandingkan dengan instance ini. |

**Returns:**
boolean - true jika System.Object yang ditentukan sama dengan instance ini; jika tidak, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Mengambil salinan elemen matriks.

**Returns:**
float[] - Salinan elemen matriks.
### getM11() {#getM11--}
```
public float getM11()
```


Mendapatkan elemen matriks pada baris pertama kolom pertama. Mewakili skala sepanjang sumbu X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Mendapatkan elemen matriks pada baris pertama kolom kedua. Mewakili geseran sepanjang sumbu Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Mendapatkan elemen matriks pada baris kedua kolom pertama. Mewakili geseran sepanjang sumbu X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Mendapatkan elemen matriks pada baris kedua kolom kedua. Mewakili skala sepanjang sumbu Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Menentukan apakah dua matriks sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Matriks pertama untuk dibandingkan. |
| b | [Matrix](../../com.aspose.psd/matrix) | Matriks kedua untuk dibandingkan. |

**Returns:**
boolean - Benar jika matriks-matriks sama.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Mengembalikan `true` jika `AffineTransform` ini adalah transformasi identitas.

**Returns:**
boolean - `true` jika `AffineTransform` ini adalah transformasi identitas; `false` sebaliknya.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix menggunakan urutan Prepend (default).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Matriks untuk dikalikan dengan. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix, dan dalam urutan yang ditentukan dalam parameter order.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx. tx. tx. |
| urutan | int | urutan. urutan. urutan. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Mengatur ulang Matrix ini sehingga memiliki elemen-elemen matriks identitas.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan default (Prepend).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut rotasi. |
| urutan | int | Urutan matriks. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan default (Prepend).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut. |
| point | [PointF](../../com.aspose.psd/pointf) | Titik. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | float | Sudut. |
| point | [PointF](../../com.aspose.psd/pointf) | Titik. |
| urutan | int | Urutan. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan Prepend (default).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sx | float | sx. sx. sx. |
| sy | float | sy. sy. sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Skala X. |
| scaleY | float | Skala Y. |
| urutan | int | Urutan. |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan sebuah  System.String  yang mewakili instance ini.

**Returns:**
java.lang.String - Sebuah  System.String  yang mewakili instance ini.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Menerapkan transformasi geometrik yang diwakili oleh Matrix ini ke array titik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Titik-titik. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Menerapkan vektor translasi yang ditentukan ke Matrix ini menggunakan urutan (default) Prepend.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tx | float | tx. tx. tx. |
| ty | float | ty. ty. ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offsetX | float | Offset X. |
| offsetY | float | Offset Y. |
| urutan | int | Urutan. |

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

