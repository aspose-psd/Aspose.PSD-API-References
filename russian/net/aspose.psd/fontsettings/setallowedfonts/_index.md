---
title: "FontSettings.SetAllowedFonts"
second_title: "Справочник API Aspose.PSD для .NET"
description: "FontSettings метод. Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением. Set Allowed font list to Null, чтобы снять ограничения."
type: docs
weight: 120
url: /ru/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением. Установите список разрешённых шрифтов в Null, чтобы снять ограничения.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontList | String[] | Список шрифтов. |

## Примеры

Следующий код демонстрирует возможность программно ограничивать шрифты.

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

### См. также

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


