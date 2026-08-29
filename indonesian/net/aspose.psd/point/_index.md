---
title: "Struct Point"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Struct Aspose.PSD.Point. Mewakili pasangan terurut dari x dan y integer yang mendefinisikan sebuah titik dalam bidang dua dimensi"
type: docs
weight: 5760
url: /id/net/aspose.psd/point/
---
{{< psd/tize >}}
## Point structure

Mewakili pasangan terurut koordinat x dan y integer yang mendefinisikan titik pada bidang dua dimensi.

```csharp
public struct Point
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Point](point/#constructor_1)(int) | Menginisialisasi instance baru dari struktur `Point` menggunakan koordinat yang ditentukan oleh nilai integer. |
| [Point](point/#constructor)(Size) | Menginisialisasi instance baru dari struktur `Point` dari struktur [`Size`](../size/). |
| [Point](point/#constructor_2)(int, int) | Menginisialisasi instance baru dari struktur `Point` dengan koordinat yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../aspose.psd/point/empty/) { get; } | Mendapatkan instance baru dari struktur `Point` yang memiliki nilai [`X`](./x/) dan [`Y`](./y/) diatur ke nol. |
| [IsEmpty](../../aspose.psd/point/isempty/) { get; } | Mendapatkan nilai yang menunjukkan apakah `Point` ini kosong. |
| [X](../../aspose.psd/point/x/) { get; set; } | Mendapatkan atau mengatur koordinat x dari `Point` ini. |
| [Y](../../aspose.psd/point/y/) { get; set; } | Mendapatkan atau mengatur koordinat y dari `Point` ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Add](../../aspose.psd/point/add/)(Point, Size) | Menambahkan [`Size`](../size/) yang ditentukan ke `Point` yang ditentukan. |
| static [Ceiling](../../aspose.psd/point/ceiling/)(PointF) | Mengonversi [`PointF`](../pointf/) yang ditentukan menjadi `Point` dengan membulatkan nilai [`PointF`](../pointf/) ke nilai integer berikutnya yang lebih tinggi. |
| static [Round](../../aspose.psd/point/round/)(PointF) | Mengonversi [`PointF`](../pointf/) yang ditentukan menjadi objek `Point` dengan membulatkan nilai `Point` ke integer terdekat. |
| static [Subtract](../../aspose.psd/point/subtract/)(Point, Size) | Mengembalikan hasil pengurangan [`Size`](../size/) yang ditentukan dari `Point` yang ditentukan. |
| static [Truncate](../../aspose.psd/point/truncate/)(PointF) | Mengonversi [`PointF`](../pointf/) yang ditentukan menjadi `Point` dengan memotong nilai `Point`. |
| override [Equals](../../aspose.psd/point/equals/)(object) | Menentukan apakah `Point` ini berisi koordinat yang sama dengan Objek yang ditentukan. |
| override [GetHashCode](../../aspose.psd/point/gethashcode/)() | Mengembalikan kode hash untuk `Point` ini. |
| [Offset](../../aspose.psd/point/offset/#offset)(Point) | Menerjemahkan `Point` ini dengan `Point` yang ditentukan. |
| [Offset](../../aspose.psd/point/offset/#offset_1)(int, int) | Menerjemahkan `Point` ini dengan jumlah yang ditentukan. |
| override [ToString](../../aspose.psd/point/tostring/)() | Mengonversi `Point` ini menjadi string yang dapat dibaca manusia. |
| [operator +](../../aspose.psd/point/op_addition/) | Menerjemahkan `Point` dengan [`Size`](../size/) yang diberikan. |
| [operator ==](../../aspose.psd/point/op_equality/) | Membandingkan dua objek `Point`. Hasil menentukan apakah nilai properti [`X`](./x/) dan [`Y`](./y/) dari dua objek `Point` sama. |
| [explicit operator](../../aspose.psd/point/op_explicit/) | Mengonversi struktur `Point` yang ditentukan menjadi struktur [`Size`](../size/). |
| [implicit operator](../../aspose.psd/point/op_implicit/) | Mengonversi struktur `Point` yang ditentukan menjadi struktur [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/point/op_inequality/) | Membandingkan dua objek `Point`. Hasil menentukan apakah nilai properti [`X`](./x/) atau [`Y`](./y/) dari dua objek `Point` tidak sama. |
| [operator -](../../aspose.psd/point/op_subtraction/) | Menerjemahkan sebuah `Point` dengan nilai negatif dari sebuah [`Size`](../size/) yang diberikan. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


