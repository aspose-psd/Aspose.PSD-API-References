---
title: Enum StringFormatFlags
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.StringFormatFlags enum. Menentukan informasi tampilan dan tata letak untuk string teks.
type: docs
weight: 5680
url: /id/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Menentukan informasi tampilan dan tata letak untuk string teks.

```csharp
[Flags]
public enum StringFormatFlags
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Teks ditampilkan dari kanan ke kiri. |
| DirectionVertical | `2` | Teks diratakan secara vertikal. |
| FitBlackBox | `4` | Bagian dari karakter diperbolehkan untuk menjorok persegi panjang tata letak string. Secara default, karakter direposisi untuk menghindari overhang. |
| DisplayFormatControl | `20` | Karakter kontrol seperti tanda kiri-ke-kanan ditampilkan dalam keluaran dengan mesin terbang yang representatif. |
| NoFontFallback | `400` | Fallback ke font alternatif untuk karakter yang tidak didukung dalam font yang diminta dinonaktifkan. Setiap karakter yang hilang ditampilkan dengan font yang hilang, biasanya kotak terbuka. |
| MeasureTrailingSpaces | `800` | Termasuk spasi tambahan di akhir setiap baris. Secara default, persegi panjang batas yang dikembalikan oleh metode MeasureString mengecualikan ruang di akhir setiap baris. Setel tanda ini untuk menyertakan ruang tersebut dalam pengukuran. |
| NoWrap | `1000` | Pembungkusan teks antar baris saat pemformatan dalam persegi panjang dinonaktifkan. Bendera ini tersirat saat sebuah titik dilewatkan alih-alih persegi panjang, atau saat persegi panjang yang ditentukan memiliki panjang garis nol. |
| LineLimit | `2000` | Hanya seluruh garis yang ditata dalam persegi panjang pemformatan. Secara default, tata letak berlanjut hingga akhir teks, atau hingga tidak ada lagi garis yang terlihat sebagai hasil pemotongan, mana saja yang lebih dulu. Perhatikan bahwa pengaturan default memungkinkan baris terakhir dikaburkan sebagian oleh persegi panjang pemformatan yang bukan kelipatan penuh dari tinggi garis. Untuk memastikan bahwa hanya seluruh garis yang terlihat, tentukan nilai ini dan berhati-hatilah untuk memberikan format persegi panjang setidaknya setinggi tinggi satu baris. |
| NoClip | `4000` | Bagian mesin terbang yang menjorok, dan teks yang dibuka bungkusnya yang berada di luar persegi panjang pemformatan diizinkan untuk ditampilkan. Secara default, semua teks dan bagian glyph yang berada di luar persegi panjang pemformatan akan dipotong. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


