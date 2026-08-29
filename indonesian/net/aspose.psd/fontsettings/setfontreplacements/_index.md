---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FontSettings. Menetapkan daftar penggantian font. Jika font tidak diizinkan maka akan dicari pengganti. Font pertama dalam daftar akan digunakan pertama kali. Jika juga dibatasi, maka font berikutnya dalam daftar akan dipilih. Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan, maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diizinkan dan tersedia, maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan."
type: docs
weight: 130
url: /id/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Mengatur daftar penggantian font. Jika font tidak diizinkan, maka akan dicari pengganti. Font pertama dalam daftar akan digunakan pertama kali. Jika juga dibatasi, maka font berikutnya dalam daftar akan dipilih. Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan, maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan. Jika tidak ada font yang diizinkan dan tersedia, maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontToReplace | String | Font yang akan diganti. |
| fontNames | String[] | Nama font pengganti dalam urutan kemiripan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Panjang Font Array dan Font Differences Array harus sama |

## Contoh

Kode berikut menunjukkan kemampuan untuk secara programatik membatasi font menggunakan.

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
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

### Lihat Juga

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


