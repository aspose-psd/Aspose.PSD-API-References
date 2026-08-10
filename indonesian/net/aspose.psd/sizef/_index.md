---
title: "Struktur SizeF"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struktur Aspose.PSD.SizeF. Menyimpan sepasang angka floating point yang biasanya merupakan lebar dan tinggi sebuah persegi panjang."
type: docs
weight: 6060
url: /id/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

Menyimpan pasangan terurut dari angka floating-point, biasanya lebar dan tinggi sebuah persegi panjang.

```csharp
public struct SizeF
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | Menginisialisasi instance baru dari struktur `SizeF` dari [`PointF`](../pointf/) yang ditentukan. |
| [SizeF](sizef/#constructor_1)(SizeF) | Menginisialisasi instance baru dari struktur `SizeF` dari `SizeF` yang ditentukan. |
| [SizeF](sizef/#constructor_2)(float, float) | Menginisialisasi sebuah instance baru dari struktur `SizeF` dari dimensi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | Mendapatkan sebuah instance baru dari struktur `SizeF` yang memiliki nilai [`Width`](./width/) dan [`Height`](./height/) disetel ke nol. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | Mendapatkan atau mengatur komponen vertikal dari `SizeF` ini. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah `SizeF` ini memiliki lebar dan tinggi nol. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | Mendapatkan atau mengatur komponen horizontal dari `SizeF` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | Menambahkan lebar dan tinggi dari satu struktur `SizeF` ke lebar dan tinggi struktur `SizeF` lainnya. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | Mengurangi lebar dan tinggi dari satu struktur `SizeF` dari lebar dan tinggi struktur `SizeF` lainnya. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | Menguji apakah objek yang ditentukan adalah `SizeF` dengan dimensi yang sama dengan `SizeF` ini. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | Mengembalikan kode hash untuk struktur [`Size`](../size/) ini. |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | Mengonversi `SizeF` menjadi [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | Mengonversi `SizeF` menjadi struktur [`Size`](../size/) dengan nilai ukuran yang dipotong. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | Membuat string yang dapat dibaca manusia yang merepresentasikan `SizeF` ini. |
| [operator +](../../aspose.psd/sizef/op_addition/) | Menambahkan lebar dan tinggi dari satu struktur `SizeF` ke lebar dan tinggi struktur `SizeF` lainnya. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | Menguji apakah dua struktur `SizeF` sama. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | Mengonversi `SizeF` yang ditentukan menjadi [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | Menguji apakah dua struktur `SizeF` berbeda. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | Mengurangi lebar dan tinggi dari satu struktur `SizeF` dari lebar dan tinggi struktur `SizeF` lainnya. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


