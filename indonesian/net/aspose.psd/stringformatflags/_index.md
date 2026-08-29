---
title: "Enum StringFormatFlags"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.StringFormatFlags. Menentukan informasi tampilan dan tata letak untuk string teks"
type: docs
weight: 6180
url: /id/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Menentukan informasi tampilan dan tata letak untuk string teks.

```csharp
[Flags]
public enum StringFormatFlags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Teks ditampilkan dari kanan ke kiri. |
| DirectionVertical | `2` | Teks disejajarkan secara vertikal. |
| FitBlackBox | `4` | Bagian-bagian karakter diizinkan melampaui persegi panjang tata letak string. Secara default, karakter diposisikan ulang untuk menghindari melampaui. |
| DisplayFormatControl | `20` | Karakter kontrol seperti tanda kiri-ke-kanan ditampilkan dalam output dengan glif representatif. |
| NoFontFallback | `400` | Penurunan ke font alternatif untuk karakter yang tidak didukung dalam font yang diminta dinonaktifkan. Setiap karakter yang hilang ditampilkan dengan glif font yang hilang, biasanya berupa kotak terbuka. |
| MeasureTrailingSpaces | `800` | Menyertakan spasi trailing di akhir setiap baris. Secara default, persegi panjang batas yang dikembalikan oleh metode MeasureString mengecualikan spasi di akhir setiap baris. Atur flag ini untuk menyertakan spasi tersebut dalam pengukuran. |
| NoWrap | `1000` | Pembungkus teks antar baris saat memformat dalam persegi panjang dinonaktifkan. Flag ini diasumsikan ketika sebuah titik diberikan alih-alih persegi panjang, atau ketika persegi panjang yang ditentukan memiliki panjang baris nol. |
| LineLimit | `2000` | Hanya baris lengkap yang ditempatkan dalam persegi panjang pemformatan. Secara default, tata letak berlanjut hingga akhir teks, atau hingga tidak ada lagi baris yang terlihat akibat pemotongan, mana yang lebih dulu terjadi. Perhatikan bahwa pengaturan default memungkinkan baris terakhir sebagian tertutup oleh persegi panjang pemformatan yang bukan kelipatan penuh dari tinggi baris. Untuk memastikan hanya baris penuh yang terlihat, tentukan nilai ini dan hati-hati menyediakan persegi panjang pemformatan setidaknya setinggi satu baris. |
| NoClip | `4000` | Bagian glyph yang melampaui, dan teks yang tidak dibungkus yang mencapai di luar persegi panjang pemformatan diizinkan untuk ditampilkan. Secara default semua teks dan bagian glyph yang mencapai di luar persegi panjang pemformatan dipotong. |
| ExactAlignment | `8000` | Penjajaran yang tepat, padding yang benar GDI+ |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


