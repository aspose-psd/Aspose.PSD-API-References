---
title: Struct Rectangle
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Rectangle struct. Menyimpan sekumpulan empat bilangan bulat yang mewakili lokasi dan ukuran persegi panjang.
type: docs
weight: 5340
url: /id/net/aspose.psd/rectangle/
---
## Rectangle structure

Menyimpan sekumpulan empat bilangan bulat yang mewakili lokasi dan ukuran persegi panjang.

```csharp
public struct Rectangle
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Rectangle](rectangle/#constructor)(Point, Size) | Menginisialisasi instance baru dari`Rectangle` struktur dengan lokasi dan ukuran yang ditentukan. |
| [Rectangle](rectangle/#constructor_1)(int, int, int, int) | Menginisialisasi instance baru dari`Rectangle` struktur dengan lokasi dan ukuran yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| static [Empty](../../aspose.psd/rectangle/empty/) { get; } | Mendapat instance baru dari`Rectangle` struktur yang dimiliki[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Dan[`Height`](./height/) nilai disetel ke nol. |
| [Bottom](../../aspose.psd/rectangle/bottom/) { get; set; } | Mendapat atau menetapkan koordinat y yang merupakan jumlah dari[`Y`](./y/) Dan[`Height`](./height/) nilai properti ini`Rectangle`struktur. |
| [Height](../../aspose.psd/rectangle/height/) { get; set; } | Mendapat atau mengatur ketinggian ini`Rectangle`struktur. |
| [IsEmpty](../../aspose.psd/rectangle/isempty/) { get; } | Mendapat nilai yang menunjukkan apakah semua properti numerik ini`Rectangle` memiliki nilai nol. |
| [Left](../../aspose.psd/rectangle/left/) { get; set; } | Mendapat atau menetapkan koordinat x dari tepi kiri ini`Rectangle`struktur. |
| [Location](../../aspose.psd/rectangle/location/) { get; set; } | Mendapat atau menetapkan koordinat sudut kiri atas ini`Rectangle`struktur. |
| [Right](../../aspose.psd/rectangle/right/) { get; set; } | Mendapat atau menetapkan koordinat x yang merupakan jumlah dari[`X`](./x/) Dan[`Width`](./width/) nilai properti ini`Rectangle`struktur. |
| [Size](../../aspose.psd/rectangle/size/) { get; set; } | Mendapat atau menyetel ukuran ini`Rectangle` . |
| [Top](../../aspose.psd/rectangle/top/) { get; set; } | Mendapat atau menetapkan koordinat y dari tepi atas ini`Rectangle`struktur. |
| [Width](../../aspose.psd/rectangle/width/) { get; set; } | Mendapat atau mengatur lebar ini`Rectangle`struktur. |
| [X](../../aspose.psd/rectangle/x/) { get; set; } | Mendapat atau menyetel koordinat x sudut kiri atas ini`Rectangle`struktur. |
| [Y](../../aspose.psd/rectangle/y/) { get; set; } | Mendapat atau menetapkan koordinat y dari sudut kiri atas ini`Rectangle`struktur. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [Ceiling](../../aspose.psd/rectangle/ceiling/)(RectangleF) | Mengonversi yang ditentukan[`RectangleF`](../rectanglef/) struktur ke a`Rectangle` struktur dengan membulatkan[`RectangleF`](../rectanglef/) nilai ke nilai integer berikutnya yang lebih tinggi. |
| static [FromLeftTopRightBottom](../../aspose.psd/rectangle/fromlefttoprightbottom/)(int, int, int, int) | Membuat a`Rectangle` struktur dengan lokasi tepi yang ditentukan. |
| static [FromPoints](../../aspose.psd/rectangle/frompoints/)(Point, Point) | Membuat yang baru`Rectangle` dari dua titik yang ditentukan. Dua vertikal dari yang dibuat`Rectangle` akan sama dengan lulus*point1* Dan*point2* . Ini biasanya adalah simpul yang berlawanan. |
| static [Inflate](../../aspose.psd/rectangle/inflate/)(Rectangle, int, int) | Membuat dan mengembalikan salinan yang digelembungkan dari yang ditentukan`Rectangle`struktur. Salinan digelembungkan dengan jumlah yang ditentukan. Asli`Rectangle` struktur tetap tidak dimodifikasi. |
| static [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle, Rectangle) | Mengembalikan sepertiga`Rectangle` struktur yang mewakili persimpangan dua lainnya`Rectangle` struktur. Jika tidak ada persimpangan, kosong`Rectangle` dikembalikan. |
| static [Round](../../aspose.psd/rectangle/round/)(RectangleF) | Mengonversi yang ditentukan[`RectangleF`](../rectanglef/) ke a`Rectangle` dengan membulatkan[`RectangleF`](../rectanglef/) nilai ke nilai bilangan bulat terdekat. |
| static [Truncate](../../aspose.psd/rectangle/truncate/)(RectangleF) | Mengonversi yang ditentukan[`RectangleF`](../rectanglef/) ke a`Rectangle` dengan memotong[`RectangleF`](../rectanglef/) nilai. |
| static [Union](../../aspose.psd/rectangle/union/)(Rectangle, Rectangle) | Mendapat a`Rectangle` struktur yang mengandung penyatuan dua`Rectangle` struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains)(Point) | Menentukan apakah titik yang ditentukan terkandung di dalamnya`Rectangle`struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_1)(Rectangle) | Menentukan apakah wilayah persegi panjang diwakili oleh*rect* sepenuhnya terkandung dalam ini`Rectangle`struktur. |
| [Contains](../../aspose.psd/rectangle/contains/#contains_2)(int, int) | Menentukan apakah titik yang ditentukan terkandung di dalamnya`Rectangle`struktur. |
| override [Equals](../../aspose.psd/rectangle/equals/)(object) | Menguji apakah*obj* adalah`Rectangle`struktur dengan lokasi dan ukuran yang sama ini`Rectangle`struktur. |
| override [GetHashCode](../../aspose.psd/rectangle/gethashcode/)() | Mengembalikan kode hash untuk ini`Rectangle`struktur. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate)(Size) | Mengembang ini`Rectangle`dengan jumlah yang ditentukan. |
| [Inflate](../../aspose.psd/rectangle/inflate/#inflate_1)(int, int) | Mengembang ini`Rectangle`dengan jumlah yang ditentukan. |
| [Intersect](../../aspose.psd/rectangle/intersect/)(Rectangle) | Menggantikan ini`Rectangle` dengan perpotongan dirinya dan yang ditentukan`Rectangle` . |
| [IntersectsWith](../../aspose.psd/rectangle/intersectswith/)(Rectangle) | Menentukan apakah persegi panjang ini berpotongan dengan*rect* . |
| [Normalize](../../aspose.psd/rectangle/normalize/)() | Menormalkan persegi panjang dengan menjadikan lebar dan tingginya positif, kiri lebih kecil dari kanan dan atas lebih kecil dari bawah. |
| [Offset](../../aspose.psd/rectangle/offset/#offset)(Point) | Menyesuaikan lokasi persegi panjang ini dengan jumlah yang ditentukan. |
| [Offset](../../aspose.psd/rectangle/offset/#offset_1)(int, int) | Menyesuaikan lokasi persegi panjang ini dengan jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/rectangle/tostring/)() | Mengubah atribut ini`Rectangle` ke string yang dapat dibaca manusia. |
| [operator ==](../../aspose.psd/rectangle/op_equality/) | Menguji apakah dua`Rectangle` struktur memiliki lokasi dan ukuran yang sama. |
| [operator !=](../../aspose.psd/rectangle/op_inequality/) | Menguji apakah dua`Rectangle` struktur berbeda dalam lokasi atau ukuran. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


