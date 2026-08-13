---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FontSettings yöntemi. En uygun yedek yazı tipini alır. Tüm yedekler izin verilmiyorsa, ilk izin verilen ve kullanılabilir yazı tipi döndürülür. Kullanılabilir yazı tipi yoksa, argümandan gelen yazı tipi döndürülür."
type: docs
weight: 80
url: /tr/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

En uygun yedek yazı tipini alır. Tüm yedekler izin verilmiyorsa, ilk izin verilen ve mevcut yazı tipi döndürülür. Eğer mevcut yazı tipi yoksa, argümandan gelen yazı tipi döndürülür.

```csharp
public static string GetReplacementFont(string fontName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | Yazı tipinin adı. |

### Dönüş Değeri

Değiştirilen yazı tipinin adı.

## Örnekler

Aşağıdaki kod, programlı olarak yazı tiplerini sınırlama yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


