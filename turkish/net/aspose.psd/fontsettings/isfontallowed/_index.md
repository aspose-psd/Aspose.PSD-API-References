---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FontSettings yöntemi. Belirtilen yazı tipi adının izinli olup olmadığını belirler"
type: docs
weight: 90
url: /tr/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

Belirtilen yazı tipi adının [is font allowed] olup olmadığını belirler.

```csharp
public static bool IsFontAllowed(string fontName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | Yazı tipinin adı. |

### Dönüş Değeri

`true` eğer [is font allowed] [belirtilen yazı tipi adı]; aksi takdirde `false`.

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


