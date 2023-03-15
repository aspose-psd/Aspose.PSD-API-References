---
title: FontSettings.GetReplacementFont
second_title: Справочник по Aspose.PSD для .NET API
description: FontSettings метод. Получает наиболее подходящий шрифт для замены. Если все замены не разрешены будет возвращен первый разрешенный и доступный шрифт. Если доступных шрифтов нет будет возвращен шрифт из arguments
type: docs
weight: 70
url: /ru/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

Получает наиболее подходящий шрифт для замены. Если все замены не разрешены, будет возвращен первый разрешенный и доступный шрифт. Если доступных шрифтов нет, будет возвращен шрифт из arguments

```csharp
public static string GetReplacementFont(string fontName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Название шрифта. |

### Возвращаемое значение

Название замененного шрифта

### Примеры

Следующий код демонстрирует возможность программного ограничения использования шрифтов.

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

### Смотрите также

* class [FontSettings](../)
* пространство имен [Aspose.PSD](../../fontsettings/)
* сборка [Aspose.PSD](../../../)


