---
title: TiffOptions
second_title: Справочник по Aspose.PSD для .NET API
description: Параметры формата файла tiff. Обратите внимание что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты поэтому нет необходимости указывать их напрямую. Обратите внимание что многие параметры возвращают значение по умолчанию но это не означает что этот параметр устанавливается явно как значение тега. Чтобы проверить наличие тега используйте свойство Tags или соответствующий метод IsTagPresent.
type: docs
weight: 4820
url: /ru/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Параметры формата файла tiff. Обратите внимание, что теги ширины и высоты будут перезаписаны при создании изображения параметрами ширины и высоты, поэтому нет необходимости указывать их напрямую. Обратите внимание, что многие параметры возвращают значение по умолчанию, но это не означает, что этот параметр устанавливается явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Инициализирует новый экземпляр класса[`TiffOptions`](../tiffoptions). |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Инициализирует новый экземпляр класса[`TiffOptions`](../tiffoptions). По умолчанию используется соглашение с прямым порядком байтов. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Инициализирует новый экземпляр класса[`TiffOptions`](../tiffoptions). |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Инициализирует новый экземпляр класса[`TiffOptions`](../tiffoptions). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage) { get; set; } | Получает или задает параметр хранения альфа-канала. Параметры, отличные отUnspecified , используются, когда имеется более 3[`SamplesPerPixel`](./samplesperpixel)определено. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist) { get; set; } | Получает или устанавливает исполнителя. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel) { get; } | Получает биты на пиксель. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample) { get; set; } | Получает или устанавливает биты на выборку. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder) { get; set; } | Получает или задает значение, указывающее порядок байтов в TIFF. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap) { get; set; } | Получает или задает карту цветов. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality) { get; set; } | Получает или задает качество сжатого изображения. Используется со сжатием Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression) { get; set; } | Получает или задает сжатие. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright) { get; set; } | Получает или устанавливает авторские права. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime) { get; set; } | Получает или задает дату и время. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Получает или задает замещающий шрифт по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если существующий шрифт слоя в PSD-файле не представлен в системе). Чтобы взять правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] семейства = col.Families; string defaultFontName = family[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname) { get; set; } | Получает или задает имя документа. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd) { get; } | Получает или устанавливает указатель на EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options) { get; set; } | Получает или задает параметры факса t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard) { get; set; } | Получает или задает стандарт файла TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder) { get; set; } | Получает или задает порядок заполнения байтовых битов. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Получает или задает значение, указывающее, является ли [полный кадр]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints) { get; set; } | Получает или задает полутоновые подсказки. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile) { get; set; } | Получает или задает поток профиля Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription) { get; set; } | Получает или задает описание изображения. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength) { get; set; } | Получает или задает длину изображения. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth) { get; set; } | Получает или задает ширину изображения. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames) { get; set; } | Получает или задает имена чернил. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Получает значение, указывающее, присутствуют ли дополнительные выборки. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled) { get; } | Получает значение, указывающее, является ли изображение мозаичным. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid) { get; } | Получает значение, указывающее, правильно ли настроен[`TiffOptions`](../tiffoptions). Используйте метод Validate, чтобы найти причину сбоя. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Получает или задает максимальное значение выборки. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Получает или задает минимальное значение выборки. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Многостраничные параметры |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation) { get; set; } | Получает или задает ориентацию. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename) { get; set; } | Получает или задает имя страницы. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber) { get; set; } | Получает или задает тег номера страницы. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette) { get; set; } | Получает или задает цветовую палитру. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric) { get; set; } | Получает или задает фотометрический параметр. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Получает или задает плоскую конфигурацию. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor) { get; set; } | Получает или задает предиктор для сжатия LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты предварительно умножаться. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Получает или задает обработчик события выполнения. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Получает или задает параметры разрешения. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit) { get; set; } | Получает или задает единицу разрешения. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Получает или задает количество строк в полосе. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat) { get; set; } | Получает или задает образец формата. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel) { get; } | Получает выборки на пиксель. Чтобы изменить значение этого свойства, используйте средство установки свойства[`BitsPerSample`](./bitspersample). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Получает или задает производителя сканера. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel) { get; set; } | Получает или задает модель сканера. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Получает или задает максимальное значение выборки. Значение имеет тип поля, который лучше всего соответствует образцу данных (тип Byte, Short или Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Получает или задает минимальное значение выборки. Значение имеет тип поля, который лучше всего соответствует образцу данных (тип Byte, Short или Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype) { get; set; } | Получает или задает тип программного обеспечения. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Получает или задает источник для создания изображения. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Получает или задает счетчик байтов полосы. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets) { get; set; } | Получает или задает смещения полосы. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype) { get; set; } | Получает или задает общее указание на тип данных, содержащихся в этом подфайле. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags) { get; set; } | Получает или задает теги. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter) { get; set; } | Получает или задает целевой принтер. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding) { get; set; } | Получает или задает пороговое значение. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Получает или задает количество байтов плитки. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength) { get; set; } | Получает или устанавливает длину тайла. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets) { get; set; } | Получает или задает смещения плитки. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth) { get; set; } | Получает или устанавливает ширину плитки. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages) { get; } | Получает общее количество страниц. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount) { get; } | Получает число действительных тегов. Это не общее количество тегов, а количество тегов, которые могут быть сохранены. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Получает или задает параметры векторной растеризации. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata) { get; set; } | Получает или задает контейнер метаданных XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor) { get; set; } | Получает или устанавливает автора изображения, используемого проводником Windows. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment) { get; set; } | Получает или задает комментарий к изображению, используемый проводником Windows. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords) { get; set; } | Получает или задает изображение темы, используемое проводником Windows. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition) { get; set; } | Получает или задает позицию x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject) { get; set; } | Получает или задает информацию об изображении, используемом проводником Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle) { get; set; } | Получает или задает информацию об изображении, используемом проводником Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution) { get; set; } | Получает или задает разрешение x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Получает или задает YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Получает или задает коэффициенты подвыборки для фотометрического YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition) { get; set; } | Получает или задает позицию y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution) { get; set; } | Получает или задает разрешение по оси y. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag)(TiffDataType) | Добавляет новый тег. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Добавляет теги. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Клонирует этот экземпляр. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Получает экземпляр тега по типу. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent)(TiffTags) | Определяет, присутствует ли тег в опциях или нет. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag)(TiffTags) | Удаляет тег. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate)() | Проверяет, имеют ли параметры допустимую комбинацию тегов |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Получает количество допустимых тегов. |

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

В этих примерах классы GraphicsPath и Graphics используются для создания фигур на поверхности изображения и управления ими. Пример создает новое изображение и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности. Наконец, изображение экспортируется в формат файла Tiff.

```csharp
[C#]

//Создаем экземпляр изображения 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Создаем и инициализируем экземпляр класса Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Очистить графическую поверхность
    graphics.Clear(Color.Wheat);

    //Создаем экземпляр класса GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Создаем экземпляр класса Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    // Добавляем фигуры к объекту Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigure(figure);

    // Нарисовать путь с помощью объекта Pen черного цвета
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Создаем экземпляр TiffOptions и устанавливаем его различные свойства
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // сохранить все изменения.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Смотрите также

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* пространство имен [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
