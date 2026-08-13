---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FontSettings yöntemi. Yazı tipi değiştirme listesini ayarlar. Yazı tipi izin verilmiyorsa bir yedek bulunur. Listede ilk yazı tipi ilk olarak kullanılır. Eğer o da kısıtlıysa listeden bir sonraki yazı tipi seçilir. Yazı tipinin değiştiricileri yoksa ya da tüm değiştiriciler izin verilmiyorsa, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. Eğer izin verilen ve kullanılabilir yazı tipi yoksa, kütüphane sistem varsayılan yazı tipini kullanmaya çalışır, hatta izin verilmemiş olsa bile."
type: docs
weight: 130
url: /tr/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Yazı tipi yedekleme listesini ayarlar. Yazı tipi izin verilmiyorsa bir yedek bulunur. Listedeki ilk yazı tipi ilk olarak kullanılır. Eğer o da kısıtlanmışsa, listedeki bir sonraki yazı tipi seçilir. Yazı tipinin yedekleri yoksa veya tüm yedekler izin verilmiyorsa, izinli yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. Eğer izinli ve mevcut yazı tipi yoksa, kütüphane izinli olmasa bile sistem varsayılan yazı tipini kullanmaya çalışır.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontToReplace | String | Değiştirilecek yazı tipi. |
| fontNames | String[] | Benzerliğe göre sıralanmış yedek yazı tipi adları. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Yazı tipi Dizisi ve Yazı Tipi Farkları Dizisinin uzunluğu eşit olmalıdır. |

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


