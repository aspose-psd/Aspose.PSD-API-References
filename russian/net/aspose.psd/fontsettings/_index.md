---
title: "Класс FontSettings"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FontSettings. Общие настройки шрифтов рендерера векторных форматов PSD."
type: docs
weight: 4760
url: /ru/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Общие настройки шрифтов рендерера векторных форматов PSD.

```csharp
public static class FontSettings
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Получает или задаёт имя шрифта по умолчанию. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Получает или задаёт значение, указывающее, следует ли [get alternative font]. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Очищает все замены шрифтов. |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Получает название шрифта Adobe по имени семейства шрифта. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Получает папки шрифтов по умолчанию. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Получает массив замен шрифтов по имени шрифта. |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Получает копию массива, содержащего список папок, где Aspose.Words ищет TrueType‑шрифты. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Получает наиболее подходящий заменяющий шрифт. Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт. Если доступных шрифтов нет, будет возвращён шрифт из аргумента. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Определяет, [is font allowed] [the specified font name]. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Удаляет файл кэша шрифтов. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Сбрасывает папку шрифтов и имя шрифта по умолчанию к системным настройкам. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением. Установите список разрешённых шрифтов в Null, чтобы снять ограничения. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найден заменяющий шрифт. Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка. Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов. Если нет разрешённых и доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Это сокращение к [`SetFontsFolders`](./setfontsfolders/) для установки только одного каталога шрифтов. Проверки папки шрифтов не выполняются. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты. Проверки папок шрифтов не выполняются. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder, использующие метод FontSettings.SetFontsFolder(fontsFolder), или после сброса шрифтов с помощью FontSettings.Reset(), будут учитываться при обработке PSD‑файлов. Пожалуйста, вызывайте этот метод каждый раз, когда вызываются FontSettings.SetFontsFolder(fontsFolder) или FontSettings.Reset() для PSD‑изображений. Без вызова этого метода нет гарантии, что шрифты будут обновлены. |

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


