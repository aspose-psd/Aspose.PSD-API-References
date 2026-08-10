---
title: "Struktur RectangleF"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struktur Aspose.PSD.RectangleF. Menyimpan sekumpulan empat angka floating‑point yang mewakili lokasi dan ukuran sebuah persegi panjang."
type: docs
weight: 5850
url: /id/net/aspose.psd/rectanglef/
---
{{< psd/tize >}}
## RectangleF structure

Menyimpan sekumpulan empat angka floating-point yang mewakili lokasi dan ukuran sebuah persegi panjang.

```csharp
public struct RectangleF
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Menginisialisasi instance baru dari struktur `RectangleF` dengan lokasi dan ukuran yang ditentukan. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Menginisialisasi instance baru dari struktur `RectangleF` dengan lokasi dan ukuran yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Mendapatkan instance baru dari struktur `RectangleF` yang memiliki nilai [`X`](./x/), [`Y`](./y/), [`Width`](./width/) dan [`Height`](./height/) diatur ke nol. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Mendapatkan atau mengatur koordinat y yang merupakan jumlah dari [`Y`](./y/) dan [`Height`](./height/) dari struktur `RectangleF` ini. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Mendapatkan atau mengatur tinggi dari struktur `RectangleF` ini. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah properti [`Width`](./width/) atau [`Height`](./height/) dari `RectangleF` ini memiliki nilai nol. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur `RectangleF` ini. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur `RectangleF` ini. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Mendapatkan atau mengatur koordinat x yang merupakan jumlah dari [`X`](./x/) dan [`Width`](./width/) dari struktur `RectangleF` ini. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Mendapatkan atau mengatur ukuran `RectangleF` ini. |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Mendapatkan atau mengatur koordinat y dari tepi atas struktur `RectangleF` ini. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Mendapatkan atau mengatur lebar struktur `RectangleF` ini. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur `RectangleF` ini. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur `RectangleF` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Membuat struktur `RectangleF` dengan sudut kiri atas dan sudut kanan bawah pada lokasi yang ditentukan. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Membuat sebuah [`Rectangle`](../rectangle/) baru dari dua titik yang ditentukan. Dua titik sudut dari [`Rectangle`](../rectangle/) yang dibuat akan sama dengan *point1* dan *point2* yang diberikan. Biasanya ini merupakan titik sudut yang berlawanan. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Membuat dan mengembalikan salinan yang diperbesar dari struktur `RectangleF` yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Rectangle asli tetap tidak berubah. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Mengembalikan struktur `RectangleF` yang mewakili irisan dua rectangle. Jika tidak ada irisan, `RectangleF` kosong akan dikembalikan. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Membuat rectangle ketiga terkecil yang mungkin yang dapat menampung kedua rectangle yang membentuk sebuah union. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Menentukan apakah titik yang ditentukan berada di dalam struktur `RectangleF` ini. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Menentukan apakah wilayah persegi panjang yang diwakili oleh *rect* sepenuhnya berada di dalam struktur `RectangleF` ini. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Menentukan apakah titik yang ditentukan berada di dalam struktur `RectangleF` ini. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Menguji apakah *obj* adalah `RectangleF` dengan lokasi dan ukuran yang sama dengan `RectangleF` ini. |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Mendapatkan kode hash untuk struktur `RectangleF` ini. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Memperbesar `RectangleF` ini sebesar jumlah yang ditentukan. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Memperbesar struktur `RectangleF` ini sebesar jumlah yang ditentukan. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Mengganti struktur `RectangleF` ini dengan irisan antara dirinya sendiri dan struktur `RectangleF` yang ditentukan. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Menentukan apakah rectangle ini beririsan dengan *rect*. |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Menormalkan rectangle dengan membuat lebar dan tinggi menjadi positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Mengonversi atribut `RectangleF` ini menjadi string yang mudah dibaca. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Mengimplementasikan operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Menguji apakah dua struktur `RectangleF` memiliki lokasi dan ukuran yang sama. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Mengonversi struktur [`Rectangle`](../rectangle/) yang ditentukan menjadi struktur `RectangleF`. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Menguji apakah dua struktur `RectangleF` berbeda dalam lokasi atau ukuran. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Mengimplementasikan operator *. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


