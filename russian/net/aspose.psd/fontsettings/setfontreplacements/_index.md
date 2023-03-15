---
title: FontSettings.SetFontReplacements
second_title: Справочник по Aspose.PSD для .NET API
description: FontSettings метод. Устанавливает список замены шрифтов. Если шрифт не разрешен то будет найдена замена. Первым будет использоваться первый шрифт в списке. Если он тоже ограничен то будет выбран следующий шрифт из списка. Если шрифт не имеет замен или все замены не разрешены то будет использоваться первый разрешенный шрифт из списка разрешенных шрифтов. Если нет разрешенных и доступных шрифтов то библиотека будет попробуйте использовать системный шрифт по умолчанию даже если это не разрешено.
type: docs
weight: 110
url: /ru/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Устанавливает список замены шрифтов. Если шрифт не разрешен, то будет найдена замена. Первым будет использоваться первый шрифт в списке. Если он тоже ограничен, то будет выбран следующий шрифт из списка. Если шрифт не имеет замен или все замены не разрешены, то будет использоваться первый разрешенный шрифт из списка разрешенных шрифтов. Если нет разрешенных и доступных шрифтов, то библиотека будет попробуйте использовать системный шрифт по умолчанию, даже если это не разрешено.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontToReplace | String | Шрифт для замены. |
| fontNames | String[] | Замена названий шрифтов в порядке сходства. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Длина массива шрифтов и массива различий шрифтов должны быть равны |

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


