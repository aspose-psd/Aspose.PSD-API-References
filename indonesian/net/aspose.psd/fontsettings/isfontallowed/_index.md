---
title: FontSettings.IsFontAllowed
second_title: Aspose.PSD untuk Referensi .NET API
description: FontSettings metode. Menentukan apakah font diperbolehkan nama font yang ditentukan.
type: docs
weight: 80
url: /id/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

Menentukan apakah [font diperbolehkan] [nama font yang ditentukan].

```csharp
public static bool IsFontAllowed(string fontName)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Nama fontnya. |

### Nilai Pengembalian

`BENAR` jika [apakah font diperbolehkan] [nama font yang ditentukan]; jika tidak,`PALSU` .

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


