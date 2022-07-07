---
title: GifOptions
second_title: Справочник по Aspose.PSD для .NET API
description: Параметры создания файла формата gif.
type: docs
weight: 4690
url: /ru/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Параметры создания файла формата gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Инициализирует новый экземпляр класса[`GifOptions`](../gifoptions). |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Инициализирует новый экземпляр класса[`GifOptions`](../gifoptions). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Получает или задает индекс цвета фона GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution) { get; set; } | Получает или задает цветовое разрешение GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Получает или задает замещающий шрифт по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если существующий шрифт слоя в PSD-файле не представлен в системе). Чтобы взять правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] семейства = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer) { get; set; } | Получает или задает значение, указывающее, есть ли у GIF трейлер. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced) { get; set; } | True, если изображение должно быть чересстрочным. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted) { get; set; } | Получает или задает значение, указывающее, сортируются ли элементы палитры. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff) { get; set; } | Получает или задает максимально допустимую разницу в пикселях. Если больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень легкое сжатие, 200 — тяжелое. Это работает лучше всего, когда вводятся лишь небольшие потери, а из-за ограничений алгоритма сжатия очень высокие уровни потерь не дадут такого большого выигрыша. Диапазон допустимых значений:[0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Получает или задает соотношение сторон пикселя GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

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
