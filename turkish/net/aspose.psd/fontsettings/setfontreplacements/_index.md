---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD for .NET API Referansı
description: FontSettings yöntem. Yazı tipi değiştirme listesini ayarlar. Yazı tipine izin verilmiyorsa yenisi bulunacaktır. Listedeki ilk yazı tipi önce kullanılacaktır. O da kısıtlanırsa listedeki bir sonraki yazı tipi seçilir. Yazı tipinde değişiklik yoksa veya tüm değişikliklere izin verilmezse izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. İzin verilen ve kullanılabilir yazı tipi yoksa kitaplık izin verilmese bile sistem varsayılan yazı tipini kullanmayı deneyin.
type: docs
weight: 110
url: /tr/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Yazı tipi değiştirme listesini ayarlar. Yazı tipine izin verilmiyorsa, yenisi bulunacaktır. Listedeki ilk yazı tipi önce kullanılacaktır. O da kısıtlanırsa, listedeki bir sonraki yazı tipi seçilir. Yazı tipinde değişiklik yoksa veya tüm değişikliklere izin verilmezse, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılır. İzin verilen ve kullanılabilir yazı tipi yoksa, kitaplık izin verilmese bile sistem varsayılan yazı tipini kullanmayı deneyin.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontToReplace | String | Değiştirilecek yazı tipi. |
| fontNames | String[] | Benzerlik sırasına göre yedek yazı tipi adları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Yazı Tipi Dizisinin Uzunluğu ve Yazı Tipi Farkları Dizisi eşit olmalıdır |

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


