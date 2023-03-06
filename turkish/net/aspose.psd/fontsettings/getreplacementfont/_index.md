---
title: FontSettings.GetReplacementFont
second_title: Aspose.PSD for .NET API Referansı
description: FontSettings yöntem. En uygun değiştirme yazı tipini alır. Tüm değişikliklere izin verilmezse izin verilen ve kullanılabilir ilk yazı tipi döndürülür. Kullanılabilir yazı tipi yoksa argüman den yazı tipi döndürülür
type: docs
weight: 70
url: /tr/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

En uygun değiştirme yazı tipini alır. Tüm değişikliklere izin verilmezse, izin verilen ve kullanılabilir ilk yazı tipi döndürülür. Kullanılabilir yazı tipi yoksa, argüman 'den yazı tipi döndürülür

```csharp
public static string GetReplacementFont(string fontName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Yazı tipinin adı. |

### Geri dönüş değeri

Değiştirilen yazı tipinin adı

### Örnekler

Aşağıdaki kod, kullanarak yazı tiplerini programlı olarak sınırlama yeteneğini gösterir.

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

### Ayrıca bakınız

* class [FontSettings](../)
* ad alanı [Aspose.PSD](../../fontsettings/)
* toplantı [Aspose.PSD](../../../)


