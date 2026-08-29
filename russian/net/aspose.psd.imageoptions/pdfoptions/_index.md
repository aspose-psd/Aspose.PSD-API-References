---
title: "Класс PdfOptions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageOptions.PdfOptions class. Параметры PDF"
type: docs
weight: 5360
url: /ru/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

Параметры PDF.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Получает или задает размер страницы. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | Основные параметры PDF |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Получает или задает метаданные документа. |
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

## Примеры

В следующем примере показано, как можно экспортировать файлы Adobe Illustrator в формат PDF с помощью Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

В следующем примере показано, что AsposePSD поддерживает экспорт файлов PSB в формат PSD.

```csharp
[C#]

// Поддержка сохранения PSB в PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Следующий код сохраняет PsdImage в документ PDF с выделяемым текстом.

```csharp
[C#]

// Сохранение PSD в PDF не обеспечивает выделяемый текст
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

В следующем примере показана поддержка экспорта PsdImage в формат PDF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### См. также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


