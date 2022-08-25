---
title: JpegOptions
second_title: Справочник по Aspose.PSD для .NET API
description: Параметры создания файла формата jpeg.
type: docs
weight: 4770
url: /ru/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Параметры создания файла формата jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Инициализирует новый экземпляр[`JpegOptions`](../jpegoptions) класс. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Инициализирует новый экземпляр[`JpegOptions`](../jpegoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Получает или устанавливает биты на канал для изображения JPEG без потерь. Теперь мы поддерживаем от 2 до 8 бит на канал. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | Целевой цветовой профиль CMYK для изображений CMYK jpeg. Используйте для сохранения изображений. Должен быть в паре с RGBColorProfile для правильного преобразования цвета. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype) { get; set; } | Получает или задает тип цвета для изображения jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment) { get; set; } | Получает или задает комментарий к файлу jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype) { get; set; } | Получает или задает тип сжатия. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Получает или устанавливает шрифт замены по умолчанию (шрифт, который будет использоваться для рисования текста при экспорте в растр, если существующий шрифт слоя в файле PSD не представлен в системе). Чтобы взять правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] семейства = col.Families; string defaultFontName = семейства[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata) { get; set; } | Получить или установить контейнер данных exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Получает или задает горизонтальную подвыборку для каждого компонента. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif) { get; set; } | Получает или задает jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Получает или задает границу разницы JPEG-LS для кодирования практически без потерь (параметр NEAR из спецификации JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Получает или задает режим чередования JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Получает или задает предустановленные параметры JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Получает или задает цветовую палитру. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Получает или задает значение, указывающее, следует ли смешивать красный, зеленый и синий компоненты с фоновым цветом, если присутствует альфа-канал. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality) { get; set; } | Получает или устанавливает качество изображения. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Получает или задает параметры оптимизатора удаленных рабочих столов. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit) { get; set; } | Получает или задает единицу измерения разрешения. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | Целевой цветовой профиль RGB для изображений CMYK jpeg. Используйте для сохранения изображений. Должен быть в паре с CMYKColorProfile для правильного преобразования цвета. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Получает или задает выборочный режим округления, чтобы подогнать 8-битное значение к n-битному значению.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality) { get; } | Масштабированное качество. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения в. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling) { get; set; } | Получает или задает вертикальную подвыборку для каждого компонента. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |

### Примеры

Этот пример демонстрирует использование Aspose.PSD для .Net API для преобразования изображений в формат Jpeg. Для достижения этой цели этот пример загружает существующее изображение, а затем преобразует его в формат файла Jpeg.

```csharp
[C#]

//Создает экземпляр класса изображения и инициализирует его существующим файлом через путь к файлу
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Создаем экземпляр класса PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    // Установите качество на 50%, чтобы уменьшить размер выходного изображения.
    jpegOptions.Quality = 50;

    //Установить комментарии exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    // Сохраняем изображение на диске с предоставленными настройками JpegOptions
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

В этом примере демонстрируется использование System.IO.Stream для создания нового файла изображения.

```csharp
[C#]

//Создает экземпляр PsdOptions и устанавливает его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создаем экземпляр System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Определяем исходное свойство для экземпляра PsdOptions
//Второй логический параметр определяет, удаляется ли поток после выхода из области видимости
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Создает экземпляр Image и вызывает метод Create с PsdOptions в качестве параметра для инициализации объекта Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // делаем некоторую обработку изображения
}
```

В этом примере демонстрируется использование различных классов из пространства имен SaveOptions для целей экспорта. Изображение типа Psd загружается в экземпляр Image, а затем экспортируется в несколько форматов.

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
