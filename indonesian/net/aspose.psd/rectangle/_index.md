---
title: "Struktur Rectangle"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struktur Aspose.PSD.Rectangle. Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang."
type: docs
weight: 5840
url: /id/net/aspose.psd/rectangle/
---
{{< psd/tize >}}
## Rectangle structure

Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang.

```csharp
public struct Rectangle
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Menginisialisasi instance baru dari struktur `Rectangle` dengan lokasi dan ukuran yang ditentukan. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Menginisialisasi instance baru dari struktur `Rectangle` dengan lokasi dan ukuran yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Mendapatkan instance baru dari struktur `Rectangle` yang memiliki nilai [`X`](./x/), [`Y`](./y/), [`Width`](./width/) dan [`Height`](./height/) disetel ke nol. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Mendapatkan atau mengatur koordinat y yang merupakan jumlah nilai properti [`Y`](./y/) dan [`Height`](./height/) dari struktur `Rectangle` ini. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Mendapatkan atau mengatur tinggi dari struktur `Rectangle` ini. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah semua properti numerik dari `Rectangle` ini memiliki nilai nol. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Mendapatkan atau mengatur koordinat x dari tepi kiri struktur `Rectangle` ini. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Mendapatkan atau mengatur koordinat sudut kiri atas dari struktur `Rectangle` ini. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Mendapatkan atau mengatur koordinat x yang merupakan jumlah nilai properti [`X`](./x/) dan [`Width`](./width/) dari struktur `Rectangle` ini. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Mendapatkan atau mengatur ukuran dari `Rectangle` ini. |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Mendapatkan atau mengatur koordinat y dari tepi atas struktur `Rectangle` ini. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Mendapatkan atau mengatur lebar struktur `Rectangle` ini. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Mendapatkan atau mengatur koordinat x dari sudut kiri atas struktur `Rectangle` ini. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Mendapatkan atau mengatur koordinat y dari sudut kiri atas struktur `Rectangle` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Mengonversi struktur [`RectangleF`](../rectanglef/) yang ditentukan menjadi struktur `Rectangle` dengan membulatkan nilai [`RectangleF`](../rectanglef/) ke nilai integer berikutnya yang lebih tinggi. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Membuat struktur `Rectangle` dengan lokasi tepi yang ditentukan. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Membuat `Rectangle` baru dari dua titik yang ditentukan. Dua sisi vertikal dari `Rectangle` yang dibuat akan sama dengan *point1* dan *point2* yang diberikan. Ini biasanya merupakan titik-titik berlawanan. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Membuat dan mengembalikan salinan `Rectangle` yang diperbesar dari struktur `Rectangle` yang ditentukan. Salinan tersebut diperbesar sebesar jumlah yang ditentukan. Struktur `Rectangle` asli tetap tidak berubah. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Mengembalikan struktur `Rectangle` ketiga yang mewakili irisan dari dua struktur `Rectangle` lainnya. Jika tidak ada irisan, `Rectangle` kosong dikembalikan. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Mengonversi [`RectangleF`](../rectanglef/) yang ditentukan menjadi `Rectangle` dengan membulatkan nilai [`RectangleF`](../rectanglef/) ke nilai integer terdekat. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Mengonversi [`RectangleF`](../rectanglef/) yang ditentukan menjadi `Rectangle` dengan memotong nilai [`RectangleF`](../rectanglef/). |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Mendapatkan struktur `Rectangle` yang berisi gabungan dua struktur `Rectangle`. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Menentukan apakah titik yang ditentukan berada di dalam struktur `Rectangle` ini. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh *rect* sepenuhnya berada di dalam struktur `Rectangle` ini. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Menentukan apakah titik yang ditentukan berada di dalam struktur `Rectangle` ini. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Menguji apakah *obj* adalah struktur `Rectangle` dengan lokasi dan ukuran yang sama dengan struktur `Rectangle` ini. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Mengembalikan kode hash untuk struktur `Rectangle` ini. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Memperbesar `Rectangle` ini sebesar jumlah yang ditentukan. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Memperbesar `Rectangle` ini sebesar jumlah yang ditentukan. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Mengganti `Rectangle` ini dengan irisan antara dirinya sendiri dan `Rectangle` yang ditentukan. |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Menentukan apakah rectangle ini beririsan dengan *rect*. |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Menormalkan rectangle dengan membuat lebar dan tinggi menjadi positif, kiri lebih kecil dari kanan, dan atas lebih kecil dari bawah. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Menyesuaikan lokasi persegi panjang ini sebesar jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Mengonversi atribut `Rectangle` ini menjadi string yang dapat dibaca manusia. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Menguji apakah dua struktur `Rectangle` memiliki lokasi dan ukuran yang sama. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Menguji apakah dua struktur `Rectangle` berbeda dalam lokasi atau ukuran. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


