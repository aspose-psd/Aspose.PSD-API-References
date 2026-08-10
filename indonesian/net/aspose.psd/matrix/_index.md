---
title: "Kelas Matrix"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Matrix. Mengganti GDI Matrix"
type: docs
weight: 5580
url: /id/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

Mengganti Matrix GDI+.

```csharp
public class Matrix
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Matrix](matrix/#constructor)() | Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas. |
| [Matrix](matrix/#constructor_1)(Matrix) | Membuat salinan dari kelas `Matrix`. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Menginisialisasi instance baru dari kelas `Matrix` ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Menginisialisasi instance baru dari kelas `Matrix` ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Menginisialisasi instance baru dari kelas `Matrix`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Mendapatkan array nilai floating-point yang mewakili elemen-elemen `Matrix` ini. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Mendapatkan elemen matriks pada baris pertama kolom pertama. Mewakili skala sepanjang sumbu X. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Mendapatkan elemen matriks pada baris pertama kolom kedua. Mewakili geseran sepanjang sumbu Y. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Mendapatkan elemen matriks pada baris kedua kolom pertama. Mewakili geseran sepanjang sumbu X. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Mendapatkan elemen matriks pada baris kedua kolom kedua. Mewakili skala sepanjang sumbu Y. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu X. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu Y. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Menentukan apakah Objek yang ditentukan sama dengan instance ini. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Mendapatkan salinan elemen-elemen matriks. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix menggunakan urutan (default) Prepend. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix, dan dalam urutan yang ditentukan dalam parameter order. |
| [Reset](../../aspose.psd/matrix/reset/)() | Mengatur ulang Matrix ini sehingga memiliki elemen-elemen dari matriks identitas. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan default (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan yang ditentukan. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan default (Prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan pada Matrix ini dalam urutan yang ditentukan. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan (default) Prepend. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke `Matrix` ini menggunakan urutan yang ditentukan. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Mengembalikan String yang mewakili instance ini. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Menerapkan transformasi geometrik yang diwakili oleh `Matrix` ini ke array titik yang ditentukan. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Menerapkan vektor translasi yang ditentukan ke `Matrix` ini menggunakan urutan (default) Prepend. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Menentukan apakah dua matriks sama. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Bita flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan pembalikan citra cermin tentang suatu sumbu yang mengubah sistem koordinat kanan menjadi sistem koordinat kiri selain konversi yang ditunjukkan oleh bita flag lainnya. Sistem koordinat kanan adalah sistem di mana sumbu X positif berputar berlawanan arah jarum jam untuk menumpuk sumbu Y positif, mirip dengan arah jari-jari tangan kanan Anda melengkung ketika Anda melihat ujung ibu jari. Sistem koordinat kiri adalah sistem di mana sumbu X positif berputar searah jarum jam untuk menumpuk sumbu Y positif, mirip dengan arah jari-jari tangan kiri Anda melengkung. Tidak ada cara matematis untuk menentukan sudut pembalikan atau transformasi cermin asli karena semua sudut pembalikan identik dengan rotasi penyesuaian yang tepat. CATATAN: TypeFlip ditambahkan setelah GENERAL_TRANSFORM beredar secara publik dan bita flag tidak dapat lagi dinomori ulang secara nyaman tanpa memperkenalkan ketidakcocokan biner dalam kode eksternal. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Bita flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi dengan sudut sewenang-wenang selain konversi yang ditunjukkan oleh bita flag lainnya. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah asli vektor dan tanpa mengubah panjang vektor. Bita flag ini bersifat saling eksklusif dengan |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Skala umum mengalikan panjang vektor dengan jumlah yang berbeda pada arah x dan y tanpa mengubah sudut antara vektor yang tegak lurus. Bita flag ini bersifat saling eksklusif dengan flag TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Konstanta ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan konversi sewenang-wenang dari koordinat input. Jika transformasi ini dapat diklasifikasikan oleh salah satu konstanta di atas, tipe akan menjadi konstanta TypeIdentity atau kombinasi bita flag yang sesuai untuk berbagai konversi koordinat yang dilakukan oleh transformasi ini. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Transformasi identitas adalah transformasi di mana koordinat output selalu sama dengan koordinat input. Jika transformasi ini bukan transformasi identitas, tipe akan menjadi konstanta GENERAL_TRANSFORM atau kombinasi bita flag yang sesuai untuk berbagai konversi koordinat yang dilakukan oleh transformasi ini. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Konstanta ini adalah bit mask untuk salah satu bita flag rotasi. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Konstanta ini adalah bit mask untuk salah satu bita flag skala. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini melakukan rotasi kuadran sebesar kelipatan 90 derajat selain konversi yang ditunjukkan oleh bit flag lainnya. Rotasi mengubah sudut vektor dengan jumlah yang sama terlepas dari arah asli vektor dan tanpa mengubah panjang vektor. Bit flag ini bersifat saling eksklusif dengan flag TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Translasi memindahkan koordinat sebesar nilai konstan pada sumbu x dan y tanpa mengubah panjang atau sudut vektor. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Skala seragam mengalikan panjang vektor dengan jumlah yang sama pada kedua arah x dan y tanpa mengubah sudut antar vektor. Bit flag ini bersifat saling eksklusif dengan flag TypeGeneralScale. |

## Catatan

Sebagian besar algoritma diambil dari AffineTransform.java milik Sun. Nama-nama Java untuk elemen matriks yang digunakan secara internal. Pemetaan nama java ke .net beserta deskripsinya: m00 M11 Skala X m10 M12 Shear Y m01 M21 Shear X m11 M22 Skala Y m02 M31 Translasi X m12 M32 Translasi Y

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


