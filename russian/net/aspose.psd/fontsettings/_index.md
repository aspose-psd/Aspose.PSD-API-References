---
title: Class FontSettings
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FontSettings сорт. Общие настройки шрифта средства визуализации векторных форматов PSD.
type: docs
weight: 4290
url: /ru/net/aspose.psd/fontsettings/
---
## FontSettings class

Общие настройки шрифта средства визуализации векторных форматов PSD.

```csharp
public static class FontSettings
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Получает или задает имя шрифта по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Очищает все замены шрифтов |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Получает имя шрифта Adobe по имени семейства шрифтов. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Получает папки со шрифтами по умолчанию. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Получает массив замен шрифта по имени шрифта |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Получает копию массива, содержащего список папок, в которых Aspose.Words ищет шрифты TrueType. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Получает наиболее подходящий шрифт для замены. Если все замены не разрешены, будет возвращен первый разрешенный и доступный шрифт. Если доступных шрифтов нет, будет возвращен шрифт из arguments |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Определяет, [разрешен ли шрифт] [указанное имя шрифта]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Сбрасывает папку шрифтов и имя шрифта по умолчанию на системное значение по умолчанию. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Ограничивает использование шрифта списком шрифтов. Перед ограничением проверьте имена реальных шрифтов. Установите для списка разрешенных шрифтов значение Null, чтобы удалить ограничения . |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Устанавливает список замены шрифтов. Если шрифт не разрешен, то будет найдена замена. Первым будет использоваться первый шрифт в списке. Если он тоже ограничен, то будет выбран следующий шрифт из списка. Если шрифт не имеет замен или все замены не разрешены, то будет использоваться первый разрешенный шрифт из списка разрешенных шрифтов. Если нет разрешенных и доступных шрифтов, то библиотека будет попробуйте использовать системный шрифт по умолчанию, даже если это не разрешено. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Это ярлык для[`SetFontsFolders`](./setfontsfolders/) для установки только одного каталога шрифтов. В папке шрифтов не выполняются проверки. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Задает папки, из которых загружаются шрифты TrueType, и очищает все загруженные шрифты. Проверка папок шрифтов не выполняется. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Обновляет кэш шрифтов для файлов PSD, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder с помощью метода FontSettings.SetFontsFolder(fontsFolder) или шрифты после сброса с помощью FontSettings.Reset() будут учитываться при обработке файлов PSD. Используйте этот метод каждый раз, когда FontSettings.SetFontsFolder(fontsFolder) или FontSettings.Reset() вызывается для изображений PSD. Без вызова этого метода нет гарантии, что шрифты будут обновлены. |

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


