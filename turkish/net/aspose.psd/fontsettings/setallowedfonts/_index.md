---
title: FontSettings.SetAllowedFonts
second_title: Aspose.PSD for .NET API Referansı
description: FontSettings yöntem. Yazı tipi kullanımını yazı tipi listesine göre kısıtlar. Lütfenstrictrions öğesini kaldırmak içinstrict İzin Verilen yazı tipi listesini Null olarak ayarlamadan önce gerçek yazı tipi adlarını kontrol edin.
type: docs
weight: 100
url: /tr/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

Yazı tipi kullanımını yazı tipi listesine göre kısıtlar. Lütfen,strictrions öğesini kaldırmak için,strict İzin Verilen yazı tipi listesini Null olarak ayarlamadan önce gerçek yazı tipi adlarını kontrol edin.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontList | String[] | Yazı tipi listesi. |

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


