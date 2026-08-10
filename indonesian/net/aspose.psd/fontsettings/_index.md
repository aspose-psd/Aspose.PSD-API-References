---
title: "Class FontSettings"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FontSettings. Pengaturan font untuk renderer format vektor PSD umum"
type: docs
weight: 4760
url: /id/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Pengaturan font perender format vektor PSD umum.

```csharp
public static class FontSettings
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Mendapatkan atau mengatur nama default font. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font]. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Menghapus semua penggantian font |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Mendapatkan nama font Adobe berdasarkan nama keluarga font. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Mendapatkan folder font default. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Mendapatkan array penggantian font berdasarkan nama font |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Mendapatkan salinan array yang berisi daftar folder tempat Aspose.Words mencari font TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Mendapatkan font pengganti yang paling cocok. Jika semua pengganti tidak diizinkan, maka akan mengembalikan font pertama yang diizinkan dan tersedia. Jika tidak ada font yang tersedia, maka akan mengembalikan font dari argumen. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Menentukan apakah [is font allowed] [nama font yang ditentukan]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Menghapus file cache font. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Mengatur ulang folder font dan nama font default ke nilai default sistem. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Membatasi penggunaan font dengan daftar font. Harap periksa nama font yang sebenarnya sebelum pembatasan. Atur daftar font yang diizinkan ke Null untuk menghapus pembatasan. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Mengatur daftar penggantian font. Jika font tidak diizinkan, maka akan dicari pengganti. Font pertama dalam daftar akan digunakan pertama kali. Jika juga dibatasi, maka font berikutnya dalam daftar akan dipilih. Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan, maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diizinkan dan tersedia, maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Ini adalah pintasan ke [`SetFontsFolders`](./setfontsfolders/) untuk mengatur hanya satu direktori font. Tidak ada pemeriksaan yang dilakukan pada folder font. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Mengatur folder tempat font TrueType dimuat dan menghapus semua font yang dimuat. Tidak ada pemeriksaan yang dilakukan pada folder font. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Memperbarui cache font untuk file PSD yang berisi lapisan teks. Metode ini menjamin bahwa font dari folder fontsFolder yang menggunakan metode FontSettings.SetFontsFolder(fontsFolder) atau setelah mereset font menggunakan FontSettings.Reset() akan dipertimbangkan saat memproses file PSD. Harap gunakan metode ini setiap kali FontSettings.SetFontsFolder(fontsFolder) atau FontSettings.Reset() dipanggil untuk gambar PSD. Tanpa memanggil Metode ini tidak ada jaminan bahwa font akan diperbarui. |

### Lihat Juga

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


