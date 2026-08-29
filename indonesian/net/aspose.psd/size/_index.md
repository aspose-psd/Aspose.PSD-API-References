---
title: "Struktur Size"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struktur Aspose.PSD.Size. Mewakili ukuran"
type: docs
weight: 6050
url: /id/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

Mewakili ukuran.

```csharp
public struct Size
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Size](size/#constructor)(Point) | Menginisialisasi instance baru dari struktur `Size` dari [`Point`](../point/) yang ditentukan. |
| [Size](size/#constructor_1)(int, int) | Menginisialisasi instance baru dari struktur `Size` dari dimensi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | Mendapatkan instance baru dari struktur `Size` yang memiliki nilai [`Width`](./width/) dan [`Height`](./height/) diatur ke nol. |
| [Height](../../aspose.psd/size/height/) { get; set; } | Mendapatkan atau mengatur komponen vertikal dari `Size` ini. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Size` ini memiliki lebar dan tinggi 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | Mendapatkan atau mengatur komponen horizontal dari `Size` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | Menambahkan lebar dan tinggi dari satu struktur `Size` ke lebar dan tinggi struktur `Size` lainnya. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | Mengonversi struktur [`SizeF`](../sizef/) yang ditentukan menjadi struktur `Size` dengan membulatkan nilai-nilai struktur `Size` ke nilai integer berikutnya yang lebih tinggi. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | Mengonversi struktur [`SizeF`](../sizef/) yang ditentukan menjadi struktur `Size` dengan membulatkan nilai-nilai struktur [`SizeF`](../sizef/) ke nilai integer terdekat. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | Mengurangi lebar dan tinggi dari satu struktur `Size` dari lebar dan tinggi struktur `Size` lainnya. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | Mengonversi struktur [`SizeF`](../sizef/) yang ditentukan menjadi struktur `Size` dengan memotong nilai-nilai struktur [`SizeF`](../sizef/) ke nilai integer berikutnya yang lebih rendah. |
| override [Equals](../../aspose.psd/size/equals/)(object) | Menguji apakah objek yang ditentukan adalah `Size` dengan dimensi yang sama dengan `Size` ini. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | Mengembalikan kode hash untuk struktur `Size` ini. |
| override [ToString](../../aspose.psd/size/tostring/)() | Membuat string yang dapat dibaca manusia yang mewakili `Size` ini. |
| [operator +](../../aspose.psd/size/op_addition/) | Menambahkan lebar dan tinggi dari satu struktur `Size` ke lebar dan tinggi struktur `Size` lainnya. |
| [operator ==](../../aspose.psd/size/op_equality/) | Menguji apakah dua struktur `Size` sama. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | Mengonversi `Size` yang ditentukan menjadi [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | Mengonversi `Size` yang ditentukan menjadi [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | Menguji apakah dua struktur `Size` berbeda. |
| [operator -](../../aspose.psd/size/op_subtraction/) | Mengurangi lebar dan tinggi dari satu struktur `Size` dari lebar dan tinggi struktur `Size` lainnya. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


