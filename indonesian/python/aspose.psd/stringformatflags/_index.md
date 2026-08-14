---
title: "Enumerasi StringFormatFlags"
type: docs
weight: 6300
url: /id/python-net/aspose.psd/stringformatflags/
---

Menentukan informasi tampilan dan tata letak untuk string teks.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nama anggota** | **Deskripsi** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Teks ditampilkan dari kanan ke kiri. |
| DIRECTION_VERTICAL | Teks diatur secara vertikal. |
| DISPLAY_FORMAT_CONTROL | Karakter kontrol seperti tanda kiri-ke-kanan ditampilkan dalam output dengan glif representatif. |
| EXACT_ALIGNMENT | Penyelarasan yang tepat, padding yang benar GDI+ |
| FIT_BLACK_BOX | Bagian-bagian karakter diizinkan menjorok keluar dari persegi tata letak string. Secara default, karakter diposisikan ulang untuk menghindari penjorokan. |
| LINE_LIMIT | Hanya baris lengkap yang ditata dalam persegi format. Secara default tata letak berlanjut hingga akhir teks, atau hingga tidak ada lagi baris yang terlihat akibat pemotongan, mana yang lebih dulu terjadi.<br/>            Perhatikan bahwa pengaturan default memungkinkan baris terakhir sebagian tertutup oleh persegi format yang bukan kelipatan penuh tinggi baris. Untuk memastikan hanya baris lengkap yang terlihat,<br/>            tentukan nilai ini dan pastikan menyediakan persegi format setidaknya setinggi tinggi satu baris. |
| MEASURE_TRAILING_SPACES | Menyertakan spasi di akhir setiap baris. Secara default persegi batas yang dikembalikan oleh metode MeasureString tidak menyertakan spasi di akhir setiap baris. Atur flag ini untuk menyertakan spasi tersebut dalam pengukuran. |
| NO_CLIP | Bagian glif yang menjorok keluar, dan teks yang tidak terbungkus yang mencapai luar persegi format diizinkan untuk ditampilkan. Secara default semua teks dan bagian glif yang mencapai luar persegi format dipotong. |
| NO_FONT_FALLBACK | Fallback ke font alternatif untuk karakter yang tidak didukung dalam font yang diminta dinonaktifkan. Karakter yang hilang ditampilkan dengan glif font yang hilang, biasanya berupa kotak terbuka. |
| NO_WRAP | Pembungkus teks antar baris saat memformat dalam sebuah persegi dinonaktifkan. Flag ini diasumsikan ketika sebuah titik diberikan alih-alih persegi, atau ketika persegi yang ditentukan memiliki panjang baris nol. |
