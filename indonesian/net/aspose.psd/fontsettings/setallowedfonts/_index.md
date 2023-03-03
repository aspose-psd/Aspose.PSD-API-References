---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD untuk Referensi .NET API
description: FontSettings metode. Membatasi penggunaan font berdasarkan daftar font. Silakan periksa nama font asli sebelum restriksi Setel daftar font yang diizinkan ke Null untuk menghapus restriksi
type: docs
weight: 100
url: /id/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Membatasi penggunaan font berdasarkan daftar font. Silakan periksa nama font asli sebelum restriksi Setel daftar font yang diizinkan ke Null untuk menghapus restriksi

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontList | String[] | Daftar font. |

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


