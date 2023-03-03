---
title: Class Matrix
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Matrix kelas. Menggantikan Matriks GDI.
type: docs
weight: 5090
url: /id/net/aspose.psd/matrix/
---
## Matrix class

Menggantikan Matriks GDI+.

```csharp
public class Matrix
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Matrix](matrix/#constructor)() | Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas. |
| [Matrix](matrix/#constructor_1)(Matrix) | Membuat salinan dari`Matrix` kelas. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Menginisialisasi instance baru dari`Matrix` kelas ke transformasi geometris yang ditentukan oleh persegi panjang dan susunan titik yang ditentukan. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Menginisialisasi instance baru dari`Matrix` kelas ke transformasi geometris yang ditentukan oleh persegi panjang dan susunan titik yang ditentukan. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Menginisialisasi instance baru dari`Matrix` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Mendapat array nilai floating-point yang mewakili elemen ini`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Mendapat elemen matriks pada baris pertama kolom pertama. Merupakan skala sepanjang sumbu X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Mendapat elemen matriks pada baris pertama kolom kedua. Merupakan geser sepanjang sumbu Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Mendapat elemen matriks pada baris kedua kolom pertama. Merupakan geser sepanjang sumbu X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Mendapat elemen matriks pada baris kedua kolom kedua. Merupakan skala sepanjang sumbu Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Mendapat elemen matriks pada baris ketiga kolom pertama. Mewakili terjemahan sepanjang sumbu X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Mendapat elemen matriks pada baris ketiga kolom pertama. Merupakan terjemahan sepanjang sumbu Y. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Menentukan apakah yang ditentukanObject sama dengan instance ini. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Mendapat salinan elemen matriks. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Mengalikan Matriks ini dengan matriks yang ditentukan dalam parameter matriks menggunakan (default) Prepend order. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Mengalikan Matriks ini dengan matriks yang ditentukan dalam parameter matriks, dan dalam urutan yang ditentukan dalam parameter urutan. |
| [Reset](../../aspose.psd/matrix/reset/)() | Mereset Matriks ini agar memiliki elemen matriks identitas. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Menerapkan rotasi searah jarum jam dari jumlah yang ditentukan dalam parameter sudut, di sekitar titik asal (koordinat nol x dan y) untuk Matriks ini dalam urutan default (Awali). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Menerapkan rotasi searah jarum jam dari jumlah yang ditentukan dalam parameter sudut, di sekitar titik asal (koordinat nol x dan y) untuk Matriks ini dalam urutan yang ditentukan. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Menerapkan rotasi searah jarum jam di sekitar titik yang ditentukan ke Matriks ini dalam urutan default (Awali). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Menerapkan rotasi searah jarum jam di sekitar titik yang ditentukan ke Matriks ini dalam urutan yang ditentukan. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matriks ini menggunakan (default) Prepend order. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) untuk ini`Matrix` menggunakan urutan yang ditentukan. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Mengembalikan aString yang mewakili instance ini. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Menerapkan transformasi geometris yang diwakili oleh ini`Matrix` ke array poin tertentu. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Menerapkan vektor terjemahan yang ditentukan untuk ini`Matrix` menggunakan (default) Prepend order. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Menerapkan vektor terjemahan yang ditentukan ke Matriks ini dalam urutan yang ditentukan. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Menentukan apakah dua matriks sama. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Bit bendera ini menunjukkan bahwa transformasi yang ditentukan oleh objek ini melakukan pembalikan gambar cermin di sekitar beberapa sumbu yang mengubah sistem koordinat tangan kanan yang biasanya menjadi sistem tangan kiri selain konversi yang ditunjukkan oleh bit bendera lainnya. Sistem koordinat tangan kanan adalah salah satu di mana sumbu X positif berputar berlawanan arah jarum jam untuk melapisi sumbu Y positif mirip dengan arah jari-jari di tangan kanan melengkung ketika Anda menatap ujung ibu jari Anda. Sistem koordinat tangan kiri adalah sistem di mana sumbu X positif berputar searah jarum jam untuk melapisi sumbu Y positif yang serupa ke arah jari-jari di tangan kiri Anda melengkung. Tidak ada cara matematis untuk menentukan sudut transformasi pembalikan asli atau pencerminan karena semua sudut pembalikan identik dengan rotasi penyesuaian yang sesuai. CATATAN: TypeFlip ditambahkan setelah GENERAL_TRANSFORM berada dalam sirkulasi public dan bit bendera tidak lagi dapat dengan mudah dinomori ulang tanpa memperkenalkan ketidakcocokan biner di kode luar. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Bit bendera ini menunjukkan bahwa transformasi yang ditentukan oleh objek ini melakukan rotasi dengan sudut sembarang selain konversi yang ditunjukkan oleh bit bendera lain. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah awal vektor dan tanpa mengubah panjang vektor. Bit flag ini saling eksklusif dengan the |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Skala umum mengalikan panjang vektor dengan jumlah yang berbeda dalam arah x dan y tanpa mengubah sudut antara vektor tegak lurus. Bit flag ini saling eksklusif dengan flag TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Konstanta ini menunjukkan bahwa transformasi yang ditentukan oleh objek ini melakukan konversi sewenang-wenang dari koordinat input. Jika transformasi ini dapat diklasifikasikan oleh salah satu konstanta di atas, tipenya akan berupa konstanta TypeIdentity atau kombinasi a dari flag yang sesuai bit untuk berbagai konversi koordinat yang dilakukan transformasi ini. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Transformasi identitas adalah transformasi yang koordinat outputnya selalu sama dengan koordinat input. Jika transformasi ini selain transformasi identitas, jenisnya adalah konstanta GENERAL_TRANSFORM atau a kombinasi dari bit flag yang sesuai untuk berbagai konversi koordinat yang dilakukan transformasi ini. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Konstanta ini adalah topeng bit untuk salah satu bit bendera rotasi. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Konstanta ini adalah topeng bit untuk salah satu bit bendera skala. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Bit bendera ini menunjukkan bahwa transformasi yang ditentukan oleh objek ini melakukan rotasi kuadran dengan kelipatan 90 derajat di selain konversi yang ditunjukkan oleh bit bendera lainnya. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah aslinya vektor dan tanpa mengubah panjang vektor. Bit bendera ini saling eksklusif dengan bendera TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Suatu translasi memindahkan koordinat dengan jumlah konstan di x dan y tanpa mengubah panjang atau sudut vektor. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Skala seragam mengalikan panjang vektor dengan jumlah yang sama pada arah x dan y tanpa mengubah sudut antara vektor. Bit flag ini saling eksklusif dengan flag TypeGeneralScale. |

### Perkataan

Sebagian besar algoritme diambil dari Sun's AffineTransform.java. Nama Java untuk elemen matriks yang digunakan secara internal. Peta nama java ke yang .net ke deskripsi: m00 Skala M11 X m10 M12 Geser Y m01 M21 Geser X m11 Skala M22d_ m3 Y_x002 Terjemahkan X m12 M32 Terjemahkan Y

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


