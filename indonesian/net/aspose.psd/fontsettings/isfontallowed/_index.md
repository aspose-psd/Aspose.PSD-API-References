---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FontSettings. Menentukan apakah font diizinkan untuk nama font yang ditentukan"
type: docs
weight: 90
url: /id/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

Menentukan apakah [is font allowed] [nama font yang ditentukan].

```csharp
public static bool IsFontAllowed(string fontName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Nama font. |

### Nilai Kembalian

`true` jika [is font allowed] [the specified font name]; selainnya, `false`.

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


