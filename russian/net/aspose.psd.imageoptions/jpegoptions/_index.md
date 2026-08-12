---
title: "Класс JpegOptions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageOptions.JpegOptions класс. Параметры создания формата файла jpeg"
type: docs
weight: 5330
url: /ru/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

Параметры создания формата файла jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | Инициализирует новый экземпляр класса `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | Инициализирует новый экземпляр класса `JpegOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | Получает или задает количество бит на канал для без потерь jpeg‑изображения. Сейчас поддерживается от 2 до 8 бит на канал. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | Целевой профиль цвета CMYK для CMYK jpeg‑изображений. Используется при сохранении изображений. Должен использоваться вместе с RGBColorProfile для корректного цветового преобразования. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | Получает или задает тип цвета для jpeg‑изображения. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | Получает или задает комментарий к файлу jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | Получает или задает тип сжатия. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | Получает или задает предельный размер выделения памяти по умолчанию. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | Получить или задать контейнер данных exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | Получает или задает горизонтальные субдискретизации для каждого компонента. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | Получает или задает jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | Получает или задает границу различия JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | Получает или задает режим чередования JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | Получает или задает предустановленные параметры JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | Получает или задает значение, указывающее, следует ли смешивать компоненты красного, зеленого и синего с цветом фона, если присутствует альфа-канал. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | Получает или задает качество изображения. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | Получает или задает настройки оптимизатора RD. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Получает или задает настройки разрешения. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | Получает или задает единицу измерения разрешения. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | Целевой профиль RGB‑цветов для изображений CMYK jpeg. Используется при сохранении изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | Масштабированное качество. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Получает или задает источник для создания изображения. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры растеризации векторов. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | Получает или задает вертикальное субдискретизирование для каждого компонента. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |

## Примеры

Этот пример демонстрирует использование Aspose.PSD для .Net API для преобразования изображений в формат Jpeg. Для достижения этой цели пример загружает существующее изображение, а затем конвертирует его в формат Jpeg.

```csharp
[C#]

//Создаёт экземпляр класса Image и инициализирует его существующим файлом по пути к файлу.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Создайте экземпляр класса PsdOptions.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Установите качество на 50 % для уменьшения размера выходного изображения.
    jpegOptions.Quality = 50;

    //Установите комментарии EXIF.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Сохраните изображение в указанное место на диске с заданными параметрами JpegOptions.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Этот пример демонстрирует использование System.IO.Stream для создания нового файла Image.

```csharp
[C#]

//Создаёт экземпляр PsdOptions и задаёт его различные свойства.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создайте экземпляр System.IO.Stream.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Определите свойство source для экземпляра PsdOptions.
//Второй логический параметр определяет, будет ли Stream освобождён после выхода из области видимости.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Создаёт экземпляр Image и вызывает метод Create, передавая PsdOptions в качестве параметра, для инициализации объекта Image.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //выполнить некоторую обработку изображения
}
```

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


