---
title: Jpeg2000Options
second_title: Справочник по Aspose.PSD для .NET API
description: Параметры формата файла Jpeg2000.
type: docs
weight: 4710
url: /ru/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Параметры формата файла Jpeg2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Инициализирует новый экземпляр класса[`Jpeg2000Options`](../jpeg2000options). |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Инициализирует новый экземпляр класса[`Jpeg2000Options`](../jpeg2000options). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec) { get; set; } | Получает или задает кодек JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments) { get; set; } | Получает или задает маркеры комментариев Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios) { get; set; } | Получает или задает массив коэффициентов сжатия. Различные коэффициенты сжатия для последовательных слоев. Скорость, указанная для каждого уровня качества, является желаемым коэффициентом сжатия. Требуются убывающие коэффициенты. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Получает или задает замещающий шрифт по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если существующий шрифт слоя в PSD-файле не представлен в системе). Чтобы взять правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] семейства = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible) { get; set; } | Получает или задает значение, указывающее, следует ли использовать необратимое сжатие DWT 9-7 (true) или использовать сжатие DWT 5-3 без потерь (по умолчанию). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

Этот пример демонстрирует использование различных классов из пространства имен SaveOptions для целей экспорта. Изображение типа Psd загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

//Загружаем существующее изображение в экземпляр класса Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Экспорт в формат файла BMP, используя параметры по умолчанию
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    // Экспорт в формат файла JPEG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    // Экспорт в формат файла JPEG 2000 с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    // Экспорт в формат файла PNG с параметрами по умолчанию
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    // Экспорт в формат файла TIFF с параметрами по умолчанию
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* пространство имен [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
