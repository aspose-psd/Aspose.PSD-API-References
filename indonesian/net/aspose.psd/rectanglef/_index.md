---
title: Struct RectangleF
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.RectangleF struct. Menyimpan satu set empat angka floatingpoint yang mewakili lokasi dan ukuran persegi panjang.
type: docs
weight: 5350
url: /id/net/aspose.psd/rectanglef/
---
## RectangleF structure

Menyimpan satu set empat angka floating-point yang mewakili lokasi dan ukuran persegi panjang.

```csharp
public struct RectangleF
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [RectangleF](rectanglef/#constructor)(PointF, SizeF) | Menginisialisasi instance baru dari`RectangleF` struktur dengan lokasi dan ukuran yang ditentukan. |
| [RectangleF](rectanglef/#constructor_1)(float, float, float, float) | Menginisialisasi instance baru dari`RectangleF` struktur dengan lokasi dan ukuran yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| static [Empty](../../aspose.psd/rectanglef/empty/) { get; } | Mendapat instance baru dari`RectangleF` struktur yang dimiliki[`X`](./x/) ,[`Y`](./y/) ,[`Width`](./width/) Dan[`Height`](./height/) nilai disetel ke nol. |
| [Bottom](../../aspose.psd/rectanglef/bottom/) { get; set; } | Mendapat atau menetapkan koordinat y yang merupakan jumlah dari[`Y`](./y/) Dan[`Height`](./height/) ini`RectangleF`struktur. |
| [Height](../../aspose.psd/rectanglef/height/) { get; set; } | Mendapat atau mengatur ketinggian ini`RectangleF`struktur. |
| [IsEmpty](../../aspose.psd/rectanglef/isempty/) { get; } | Mendapat nilai yang menunjukkan apakah[`Width`](./width/) atau[`Height`](./height/) milik ini`RectangleF` memiliki nilai nol. |
| [Left](../../aspose.psd/rectanglef/left/) { get; set; } | Mendapat atau menetapkan koordinat x dari tepi kiri ini`RectangleF`struktur. |
| [Location](../../aspose.psd/rectanglef/location/) { get; set; } | Mendapat atau menetapkan koordinat sudut kiri atas ini`RectangleF`struktur. |
| [Right](../../aspose.psd/rectanglef/right/) { get; set; } | Mendapat atau menetapkan koordinat x yang merupakan jumlah dari[`X`](./x/) Dan[`Width`](./width/) ini`RectangleF`struktur. |
| [Size](../../aspose.psd/rectanglef/size/) { get; set; } | Mendapat atau menyetel ukuran ini`RectangleF` . |
| [Top](../../aspose.psd/rectanglef/top/) { get; set; } | Mendapat atau menetapkan koordinat y dari tepi atas ini`RectangleF`struktur. |
| [Width](../../aspose.psd/rectanglef/width/) { get; set; } | Mendapat atau mengatur lebar ini`RectangleF`struktur. |
| [X](../../aspose.psd/rectanglef/x/) { get; set; } | Mendapat atau menyetel koordinat x sudut kiri atas ini`RectangleF`struktur. |
| [Y](../../aspose.psd/rectanglef/y/) { get; set; } | Mendapat atau menetapkan koordinat y dari sudut kiri atas ini`RectangleF`struktur. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.psd/rectanglef/fromlefttoprightbottom/)(float, float, float, float) | Membuat a`RectangleF` struktur dengan pojok kiri atas dan pojok kanan bawah di lokasi yang ditentukan. |
| static [FromPoints](../../aspose.psd/rectanglef/frompoints/)(PointF, PointF) | Membuat yang baru[`Rectangle`](../rectangle/) dari dua titik yang ditentukan. Dua simpul dari yang dibuat[`Rectangle`](../rectangle/) akan sama dengan lulus*point1* Dan*point2* . Ini biasanya adalah simpul yang berlawanan. |
| static [Inflate](../../aspose.psd/rectanglef/inflate/)(RectangleF, float, float) | Membuat dan mengembalikan salinan yang digelembungkan dari yang ditentukan`RectangleF`struktur. Salinan digelembungkan dengan jumlah yang ditentukan. Persegi panjang asli tetap tidak diubah. |
| static [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF, RectangleF) | Mengembalikan a`RectangleF` struktur yang mewakili persimpangan dua persegi panjang. Jika tidak ada persimpangan, dan kosong`RectangleF` dikembalikan. |
| static [Union](../../aspose.psd/rectanglef/union/)(RectangleF, RectangleF) | Membuat persegi panjang ketiga sekecil mungkin yang dapat memuat kedua persegi panjang yang membentuk gabungan. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains)(PointF) | Menentukan apakah titik yang ditentukan terkandung di dalamnya`RectangleF`struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_1)(RectangleF) | Menentukan apakah wilayah persegi panjang diwakili oleh*rect* sepenuhnya terkandung dalam ini`RectangleF`struktur. |
| [Contains](../../aspose.psd/rectanglef/contains/#contains_2)(float, float) | Menentukan apakah titik yang ditentukan terkandung di dalamnya`RectangleF`struktur. |
| override [Equals](../../aspose.psd/rectanglef/equals/)(object) | Menguji apakah*obj* adalah`RectangleF` dengan lokasi dan ukuran yang sama ini`RectangleF` . |
| override [GetHashCode](../../aspose.psd/rectanglef/gethashcode/)() | Mendapat kode hash untuk ini`RectangleF`struktur. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate)(SizeF) | Mengembang ini`RectangleF`dengan jumlah yang ditentukan. |
| [Inflate](../../aspose.psd/rectanglef/inflate/#inflate_1)(float, float) | Mengembang ini`RectangleF` struktur dengan jumlah yang ditentukan. |
| [Intersect](../../aspose.psd/rectanglef/intersect/)(RectangleF) | Menggantikan ini`RectangleF`struktur dengan perpotongan dirinya dan yang ditentukan`RectangleF`struktur. |
| [IntersectsWith](../../aspose.psd/rectanglef/intersectswith/)(RectangleF) | Menentukan apakah persegi panjang ini berpotongan dengan*rect* . |
| [Normalize](../../aspose.psd/rectanglef/normalize/)() | Menormalkan persegi panjang dengan menjadikan lebar dan tingginya positif, kiri lebih kecil dari kanan dan atas lebih kecil dari bawah. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset)(PointF) | Menyesuaikan lokasi persegi panjang ini dengan jumlah yang ditentukan. |
| [Offset](../../aspose.psd/rectanglef/offset/#offset_1)(float, float) | Menyesuaikan lokasi persegi panjang ini dengan jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/rectanglef/tostring/)() | Mengubah atribut ini`RectangleF` ke string yang dapat dibaca manusia. |
| [operator /](../../aspose.psd/rectanglef/op_division/) | Menerapkan operator /. |
| [operator ==](../../aspose.psd/rectanglef/op_equality/) | Menguji apakah dua`RectangleF` struktur memiliki lokasi dan ukuran yang sama. |
| [implicit operator](../../aspose.psd/rectanglef/op_implicit/) | Mengonversi yang ditentukan[`Rectangle`](../rectangle/) struktur ke a`RectangleF`struktur. |
| [operator !=](../../aspose.psd/rectanglef/op_inequality/) | Menguji apakah dua`RectangleF` struktur berbeda dalam lokasi atau ukuran. |
| [operator *](../../aspose.psd/rectanglef/op_multiply/) | Menerapkan operator *. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


