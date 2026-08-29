---
title: "FontSettings.GetReplacementFont"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод FontSettings. Возвращает наиболее подходящий заменяющий шрифт. Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт. Если доступных шрифтов нет, будет возвращён шрифт из аргумента."
type: docs
weight: 80
url: /ru/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Получает наиболее подходящий заменяющий шрифт. Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт. Если доступных шрифтов нет, будет возвращён шрифт из аргумента.

```csharp
public static string GetReplacementFont(string fontName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Имя шрифта. |

### Возвращаемое значение

Имя заменённого шрифта

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


