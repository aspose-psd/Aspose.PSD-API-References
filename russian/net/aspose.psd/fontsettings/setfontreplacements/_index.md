---
title: "FontSettings.SetFontReplacements"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод FontSettings. Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найден заменитель. Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка. Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов. Если нет ни разрешённых, ни доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён"
type: docs
weight: 130
url: /ru/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найден заменяющий шрифт. Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка. Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов. Если нет разрешённых и доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontToReplace | String | Шрифт для замены. |
| fontNames | String[] | Имена заменяющих шрифтов в порядке схожести. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Длина массивов Font Array и Font Differences Array должна быть одинаковой |

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


