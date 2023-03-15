---
title: Struct Point
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Point struct. Mewakili pasangan terurut bilangan bulat koordinat x dan y yang mendefinisikan sebuah titik dalam bidang dua dimensi.
type: docs
weight: 5260
url: /id/net/aspose.psd/point/
---
## Point structure

Mewakili pasangan terurut bilangan bulat koordinat x dan y yang mendefinisikan sebuah titik dalam bidang dua dimensi.

```csharp
public struct Point
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Point](point/#constructor_1)(int) | Menginisialisasi instance baru dari`Point` struktur menggunakan koordinat yang ditentukan oleh nilai integer. |
| [Point](point/#constructor)(Size) | Menginisialisasi instance baru dari`Point` struktur dari[`Size`](../size/)struktur. |
| [Point](point/#constructor_2)(int, int) | Menginisialisasi instance baru dari`Point` struktur dengan koordinat yang ditentukan. |

## Properti

| Nama | Keterangan |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Mendapat instance baru dari`Point` struktur yang dimiliki[`X`](./x/) Dan[`Y`](./y/) nilai disetel ke nol. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Mendapat nilai yang menunjukkan apakah ini`Point` kosong. |
| [X](../../aspose.psd/point/x/) { get; set; } | Mendapat atau menetapkan koordinat x dari ini`Point` . |
| [Y](../../aspose.psd/point/y/) { get; set; } | Mendapat atau menetapkan koordinat y dari ini`Point` . |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Menambahkan yang ditentukan[`Size`](../size/) ke yang ditentukan`Point` . |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Mengonversi yang ditentukan[`PointF`](../pointf/) ke a`Point` dengan membulatkan nilai dari[`PointF`](../pointf/) ke nilai integer berikutnya yang lebih tinggi. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Mengonversi yang ditentukan[`PointF`](../pointf/) ke a`Point` objek dengan membulatkan`Point` nilai ke bilangan bulat terdekat. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Mengembalikan hasil pengurangan yang ditentukan[`Size`](../size/) dari yang ditentukan`Point` . |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Mengonversi yang ditentukan[`PointF`](../pointf/) ke a`Point` dengan memotong nilai-nilai dari`Point` . |
| override [Equals](../../aspose.psd/point/equals/)(object) | Menentukan apakah ini`Point` berisi koordinat yang sama seperti yang ditentukanObject . |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Mengembalikan kode hash untuk ini`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Menerjemahkan ini`Point` oleh yang ditentukan`Point` . |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Menerjemahkan ini`Point`dengan jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/point/tostring/)() | Mengubah ini`Point` ke string yang dapat dibaca manusia. |
| [operator +](../../aspose.psd/point/op_addition/) | Menerjemahkan a`Point` oleh yang diberikan[`Size`](../size/) . |
| [operator ==](../../aspose.psd/point/op_equality/) | Membandingkan dua`Point` objek. Hasilnya menentukan apakah nilai-nilai dari[`X`](./x/) Dan[`Y`](./y/) sifat keduanya`Point` objek sama. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Mengonversi yang ditentukan`Point` struktur ke a[`Size`](../size/)struktur. |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Mengonversi yang ditentukan`Point` struktur ke[`PointF`](../pointf/)struktur. |
| [operator !=](../../aspose.psd/point/op_inequality/) | Membandingkan dua`Point` objek. Hasilnya menentukan apakah nilai-nilai dari[`X`](./x/) atau[`Y`](./y/) sifat keduanya`Point` objek tidak sama. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Menerjemahkan a`Point` oleh negatif dari yang diberikan[`Size`](../size/) . |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


