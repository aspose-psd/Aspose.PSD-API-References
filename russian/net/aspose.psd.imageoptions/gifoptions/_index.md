---
title: "Класс GifOptions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageOptions.GifOptions класс. Параметры создания формата файла gif"
type: docs
weight: 5300
url: /ru/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

Параметры создания файлового формата GIF.

```csharp
public class GifOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Инициализирует новый экземпляр класса `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Инициализирует новый экземпляр класса `GifOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Получает или задает индекс фонового цвета GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Получает или задает разрешение цвета GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Получает или задает значение, указывающее, имеет ли GIF трейлер. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | True, если изображение должно быть чересстрочным. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Получает или задает значение, указывающее, отсортированы ли записи палитры. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Получает или задает максимальное допустимое различие пикселей. Если значение больше нуля, будет использоваться сжатие с потерями. Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 — очень лёгкое сжатие, 200 — сильное. Оно работает лучше всего, когда вводится небольшая потеря, и из‑за ограничений алгоритма сжатия очень высокие уровни потери не дают значительного выигрыша. Диапазон допустимых значений: [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Получает или задает соотношение сторон пикселя GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Получает или задает настройки разрешения. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры растеризации векторов. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

## Примеры

В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для экспорта. Изображение типа Psd загружается в экземпляр Image, а затем экспортируется в несколько форматов.

```csharp
[C#]

//Загрузите существующее изображение в экземпляр класса Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Экспорт в файловый формат BMP с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Экспорт в файловый формат JPEG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Экспорт в файловый формат JPEG 2000 с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Экспорт в файловый формат PNG с использованием параметров по умолчанию
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Экспорт в файловый формат TIFF с использованием параметров по умолчанию
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### См. также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


