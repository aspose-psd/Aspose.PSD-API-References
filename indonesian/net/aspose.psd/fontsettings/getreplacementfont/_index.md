---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FontSettings. Mendapatkan font pengganti yang paling cocok. Jika semua pengganti tidak diizinkan maka akan dikembalikan font pertama yang diizinkan dan tersedia. Jika tidak ada font yang tersedia maka akan dikembalikan font dari argumen"
type: docs
weight: 80
url: /id/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Mendapatkan font pengganti yang paling cocok. Jika semua pengganti tidak diizinkan, maka akan mengembalikan font pertama yang diizinkan dan tersedia. Jika tidak ada font yang tersedia, maka akan mengembalikan font dari argumen.

```csharp
public static string GetReplacementFont(string fontName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Nama font. |

### Nilai Kembalian

Nama font yang diganti

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


