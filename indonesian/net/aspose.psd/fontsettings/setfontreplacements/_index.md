---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD untuk Referensi .NET API
description: FontSettings metode. Mengatur daftar penggantian font. Jika font tidak diperbolehkan maka akan dicari penggantinya. Font pertama dalam daftar akan digunakan terlebih dahulu. Jika dibatasi juga maka akan dipilih font berikutnya dari daftar. Jika font belum diganti atau semua penggantian tidak diperbolehkan maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diperbolehkan dan tersedia maka perpustakaan akan coba gunakan font default sistem meskipun tidak diizinkan.
type: docs
weight: 110
url: /id/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Mengatur daftar penggantian font. Jika font tidak diperbolehkan maka akan dicari penggantinya. Font pertama dalam daftar akan digunakan terlebih dahulu. Jika dibatasi juga, maka akan dipilih font berikutnya dari daftar. Jika font belum diganti atau semua penggantian tidak diperbolehkan maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diperbolehkan dan tersedia maka perpustakaan akan coba gunakan font default sistem meskipun tidak diizinkan.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontToReplace | String | Font yang akan diganti. |
| fontNames | String[] | Nama font pengganti dalam urutan kesamaan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Panjang Array Font dan Array Perbedaan Font harus sama |

### Contoh

Kode berikut menunjukkan kemampuan untuk membatasi penggunaan font secara terprogram.

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### Lihat juga

* class [FontSettings](../)
* ruang nama [Aspose.PSD](../../fontsettings/)
* perakitan [Aspose.PSD](../../../)


