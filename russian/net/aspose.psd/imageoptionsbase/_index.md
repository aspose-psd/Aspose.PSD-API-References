---
title: "Класс ImageOptionsBase"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ImageOptionsBase. Базовые параметры изображения."
type: docs
weight: 5480
url: /ru/net/aspose.psd/imageoptionsbase/
---
{{< psd/tize >}}
## ImageOptionsBase class

Базовые параметры изображения.

```csharp
public abstract class ImageOptionsBase : DisposableObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Получает или задает настройки разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры растеризации векторов. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

### См. также

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


