---
title: "Kelas Blend"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Blend. Mendefinisikan pola blend. Kelas ini tidak dapat diwariskan"
type: docs
weight: 110
url: /id/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

Mendefinisikan pola pencampuran. Kelas ini tidak dapat diwariskan.

```csharp
public sealed class Blend
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Blend](blend/#constructor)() | Menginisialisasi instance baru dari kelas `Blend`. Jumlah elemen dalam array faktor dan blend akan sama dengan 1. |
| [Blend](blend/#constructor_1)(int) | Menginisialisasi instance baru dari kelas `Blend` dengan jumlah faktor dan posisi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Mendapatkan atau mengatur array faktor blend untuk gradien. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Mendapatkan atau mengatur array posisi blend untuk gradien. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Menguji apakah objek yang ditentukan adalah kelas `Blend` dan setara dengan kelas `Blend` ini. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |

## Catatan

Penggunaan umum kelas blend adalah mendefinisikan pola blend untuk kuas. Oleh karena itu properti blend harus diinisialisasi dengan hati-hati. Array null tidak diizinkan. Kuas akan melempar pengecualian yang sesuai jika array faktor blend atau posisi kosong atau panjangnya tidak sama. Jika ada dua atau lebih elemen dalam array posisi, maka elemen pertama harus 0 dan yang terakhir harus 1.

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


