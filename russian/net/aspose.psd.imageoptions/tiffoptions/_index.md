---
title: "Класс TiffOptions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.ImageOptions.TiffOptions. Параметры формата файлов tiff. Обратите внимание, что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты, поэтому нет необходимости указывать их напрямую. Также обратите внимание, что многие параметры возвращают значение по умолчанию, но это не означает, что параметр установлен явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent."
type: docs
weight: 5430
url: /ru/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Параметры формата файла tiff. Обратите внимание, что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты, поэтому нет необходимости указывать их напрямую. Также обратите внимание, что многие параметры возвращают значение по умолчанию, но это не означает, что параметр установлен явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Инициализирует новый экземпляр класса `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Инициализирует новый экземпляр класса `TiffOptions`. По умолчанию используется порядок байтов little endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Инициализирует новый экземпляр класса `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Инициализирует новый экземпляр класса `TiffOptions`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Получает или задает параметр хранения альфа-канала. Параметры, отличные от Unspecified, используются, когда определено более 3 [`SamplesPerPixel`](./samplesperpixel/). |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Получает или задает автора. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Возвращает количество бит на пиксель. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Получает или задает количество бит на образец. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Получает или задает значение, указывающее порядок байтов tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Получает или задает карту цветов. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Получает или задает качество сжатого изображения. Используется с сжатием Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Получает или задает степень сжатия. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Получает или задает авторские права. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Получает или задает дату и время. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Получает или задает предельный размер выделения памяти по умолчанию. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Получает или задает имя документа. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Получает или задает указатель на EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Получает или задает параметры fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Получает или задает стандарт файла TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Получает или задает порядок заполнения битов байта. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Получает или задает значение, указывающее, является ли [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Получает или задает подсказки полутонов. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Получает или задает поток профиля Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Получает или задает описание изображения. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Получает или задает длину изображения. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Получает или задает ширину изображения. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Получает или задает названия чернил. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Получает значение, указывающее, присутствуют ли дополнительные образцы. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Получает значение, указывающее, является ли изображение тайловым. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Получает значение, указывающее, правильно ли настроены `TiffOptions`. Используйте метод Validate, чтобы найти причину сбоя. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Получает или задает максимальное значение образца. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Получает или задает минимальное значение образца. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Параметры многопостраничности |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Получает или задает ориентацию. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Получает или задает имя страницы. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Получает или задает тег номера страницы. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Получает или задает цветовую палитру. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Получает или задает фотометрический параметр. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Получает или задает планарную конфигурацию. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Получает или задает предсказатель для сжатия LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Получает или задает настройки разрешения. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Получает или задает единицу измерения разрешения. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Получает или задает количество строк на полосу. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Получает или задает формат образца. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Получает количество образцов на пиксель. Чтобы изменить значение этого свойства, используйте сеттер свойства [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Получает или задает производителя сканера. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Получает или задает модель сканера. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Получает или задает тип программного обеспечения. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Получает или задает источник для создания изображения. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Получает или задает количество байтов в полосе. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Получает или задает смещения полос. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Получает или задает общее указание типа данных, содержащихся в этом подпфайле. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Получает или задает теги. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Получает или задает целевой принтер. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Получает или задает пороговое значение. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Получает или задает количество байтов в плитке. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Получает или задает длину плитки. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Получает или задает смещения плитки. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Получает или задает ширину плитки. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Получает общее количество страниц. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Получает количество действительных тегов. Это не общее количество тегов, а число тегов, которые могут быть сохранены. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Получает или задает параметры растеризации векторов. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Получает или задает контейнер метаданных XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Получает или задает автора изображения, который используется в Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Получает или задает комментарий к изображению, который используется в Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Получает или задает тему изображения, которая используется в Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Получает или задает позицию по оси X. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Получает или задает информацию об изображении, используемую Проводником Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Получает или задает информацию об изображении, используемую Проводником Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Получает или задает разрешение по оси X. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Получает или задает коэффициенты YCbCr. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Получает или задает позицию по оси Y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Получает или задает разрешение по оси Y. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Добавляет новый тег. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Добавляет теги. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Получает экземпляр тега по типу. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Определяет, присутствует ли тег в параметрах или нет. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Удаляет тег. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Проверяет, имеет ли набор параметров допустимую комбинацию тегов. |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Возвращает количество допустимых тегов. |

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

В этом примере используется класс GraphicsPath и класс Graphics для создания и манипулирования фигурами на поверхности изображения. Пример создает новое изображение и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отрисовки путей на поверхности. В конце изображение экспортируется в формат файла Tiff.

```csharp
[C#]

//Создайте экземпляр Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создайте и инициализируйте экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить поверхность Graphics
    graphics.Clear(Color.Wheat);

    //Создайте экземпляр класса GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Создайте экземпляр класса Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Добавьте фигуры в объект Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Добавьте объект Figure в GraphicsPath
    graphicspath.AddFigure(figure);

    //Нарисуйте путь объектом Pen цвета чёрный
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Создайте экземпляр TiffOptions и задайте его различные свойства
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Сохраните все изменения.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### См. также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


