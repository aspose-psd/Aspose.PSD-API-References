---
title: Class FontSettings
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FontSettings kelas. Pengaturan font penyaji format vektor PSD umum.
type: docs
weight: 4290
url: /id/net/aspose.psd/fontsettings/
---
## FontSettings class

Pengaturan font penyaji format vektor PSD umum.

```csharp
public static class FontSettings
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Mendapat atau menyetel nama default font. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Menghapus semua penggantian font |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Mendapatkan nama font adobe dengan nama keluarga font. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Mendapat folder font default. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Mendapatkan larik penggantian font dengan nama font |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Mendapat salinan larik yang berisi daftar folder tempat Aspose.Words mencari font TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Mendapatkan font pengganti yang paling sesuai. Jika semua penggantian tidak diperbolehkan maka akan dikembalikan font pertama yang diizinkan dan tersedia. Jika tidak ada font yang tersedia maka akan dikembalikan font dari argument |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Menentukan apakah [font diperbolehkan] [nama font yang ditentukan]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Mereset folder font dan nama font default ke default sistem. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Membatasi penggunaan font berdasarkan daftar font. Silakan periksa nama font asli sebelum restriksi Setel daftar font yang diizinkan ke Null untuk menghapus restriksi |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Mengatur daftar penggantian font. Jika font tidak diperbolehkan maka akan dicari penggantinya. Font pertama dalam daftar akan digunakan terlebih dahulu. Jika dibatasi juga, maka akan dipilih font berikutnya dari daftar. Jika font belum diganti atau semua penggantian tidak diperbolehkan maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diperbolehkan dan tersedia maka perpustakaan akan coba gunakan font default sistem meskipun tidak diizinkan. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Ini adalah jalan pintas ke[`SetFontsFolders`](./setfontsfolders/) untuk setting hanya satu font directory. Tidak ada pengecekan yang dilakukan pada folder fonts. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Menetapkan folder tempat font TrueType dimuat dan menghapus semua font yang dimuat. Tidak ada pemeriksaan yang dilakukan pada folder font. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Memperbarui cache font untuk file PSD yang berisi lapisan teks. Metode ini menjamin bahwa font dari folder fontsFolder menggunakan metode FontSettings.SetFontsFolder(fontsFolder) atau setelah mengatur ulang font menggunakan FontSettings.Reset() akan dipertimbangkan saat memproses file PSD. Harap gunakan metode ini setiap kali FontSettings.SetFontsFolder(fontsFolder) atau FontSettings.Reset() memanggil gambar PSD. Tanpa memanggil Metode ini, tidak ada jaminan bahwa font akan diperbarui. |

### Lihat juga

* ruang nama [Aspose.PSD](../../aspose.psd/)
* perakitan [Aspose.PSD](../../)


