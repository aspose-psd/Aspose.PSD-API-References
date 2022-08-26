---
title: Aspose.PSD
second_title: Справочник по Aspose.PSD для .NET API
description: Пространство имен является ядром для вложенных пространств имен и самых основных объектов используемых для обработки Aspose.PSD.
type: docs
weight: 10
url: /ru/net/aspose.psd/
---
Пространство имен является ядром для вложенных пространств имен и самых основных объектов, используемых для обработки Aspose.PSD.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AggregateException](./aggregateexception) | Объединяет несколько исключений. |
| [Blend](./blend) | Определяет шаблон наложения. Этот класс не может быть унаследован. |
| [Brush](./brush) | Базовый класс кисти. |
| [BuildVersionInfo](./buildversioninfo) | Содержит информацию о текущей версии сборки. |
| [Cache](./cache) | Содержит настройки кеша. |
| [CmykColorHelper](./cmykcolorhelper) | Вспомогательные методы для работы с цветом CMYK, представленным в виде 32-разрядного целого числа со знаком.[`CmykColor`](../aspose.psd/cmykcolor)struct. Он более легкий, потому что цвет CMYK представлен как Int32, а не как структура с внутренними полями. Пожалуйста, предпочтите использовать статические методы этого класса, когда это возможно, вместо deprecated [`CmykColor`](../aspose.psd/cmykcolor) структура. |
| [ColorBlend](./colorblend) | Определяет массивы цветов и позиций, используемых для интерполяции смешения цветов в многоцветном градиенте. Этот класс не может быть унаследован. |
| [ColorMap](./colormap) | Определяет карту для преобразования цветов. Несколько методов[`ImageAttributes`](../aspose.psd/imageattributes) класс настраивает цвета изображения с помощью таблицы переназначения цветов, которая представляет собой массив[`ColorMap`](../aspose.psd/colormap) структуры. Не передается по наследству. |
| [ColorMatrix](./colormatrix) | Определяет матрицу 5 x 5, содержащую координаты пространства RGBA. Несколько методов[`ImageAttributes`](../aspose.psd/imageattributes) Класс корректирует цвета изображения с помощью цветовой матрицы. Этот класс не может быть унаследован. |
| [ColorPalette](./colorpalette) | Определяет массив цветов, составляющих цветовую палитру. Цвета являются 32-битными цветами ARGB. Не передается по наследству. |
| [ColorPaletteHelper](./colorpalettehelper) | Вспомогательный класс для управления цветовыми палитрами. |
| [ColorTranslator](./colortranslator) | Преобразует цвета в структуры GDI+ Color и обратно. Этот класс не может быть унаследован. |
| [CompositeException](./compositeexception) | Составное исключение |
| [CustomLineCap](./customlinecap) | Инкапсулирует определяемый пользователем заголовок строки. |
| [DataStreamSupporter](./datastreamsupporter) | Контейнер потока данных. |
| [DisposableObject](./disposableobject) | Представляет одноразовый объект. |
| [Figure](./figure) | Фигура. Контейнер для фигур. |
| [FileStreamContainer](./filestreamcontainer) | Помощник для обработки файлового потока. |
| [Font](./font) | Определяет определенный формат текста, включая начертание шрифта, размер и атрибуты стиля. Этот класс не может быть унаследован. |
| [FontSettings](./fontsettings) | Общие настройки шрифта средства визуализации векторных форматов PSD. |
| [Graphics](./graphics) | Представляет графику в соответствии с графическим движком, используемым в текущей сборке. |
| [GraphicsPath](./graphicspath) | Представляет набор соединенных линий и кривых. Этот класс не может быть унаследован. |
| [Image](./image) | Изображение является базовым классом для всех типов изображений. |
| [ImageAttributes](./imageattributes) | Ан[`ImageAttributes`](../aspose.psd/imageattributes) Объект содержит информацию о том, как цвета растрового изображения и метафайла манипулируются во время рендеринга. Ан[`ImageAttributes`](../aspose.psd/imageattributes) Объект поддерживает несколько настроек настройки цвета, включая матрицы настройки цвета, матрицы настройки оттенков серого, значения гамма-коррекции, таблицы карты цветов и пороговые значения цвета. Во время рендеринга цвета можно корректировать, затемнять, осветлять и удалять. Чтобы применить такие манипуляции, инициализируйте[`ImageAttributes`](../aspose.psd/imageattributes)объект и пройти путь этого[`ImageAttributes`](../aspose.psd/imageattributes) объекта (вместе с путем[`Image`](../aspose.psd/image) ) в метод DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry) | Представляет реестр создателей образов. |
| [ImageExportersRegistry](./imageexportersregistry) | Представляет реестр экспортеров образов. |
| [ImageLoadersRegistry](./imageloadersregistry) | Представляет реестр загрузчиков образов. |
| [ImageOptionsBase](./imageoptionsbase) | Базовые параметры образа. |
| [ImageResizeSettings](./imageresizesettings) | Настройки изменения размера изображения class |
| [IntRange](./intrange) | Класс для представления последовательности элементов |
| [License](./license) | Предоставляет методы лицензирования компонента. |
| [LoadOptions](./loadoptions) | Представляет параметры загрузки. |
| [Matrix](./matrix) | Заменяет матрицу GDI+. |
| [Metered](./metered) | Предоставляет методы для установки измеренного ключа. |
| [NonGenericDictionary](./nongenericdictionary) | Представляет не универсальный словарь. |
| [NonGenericList](./nongenericlist) | Необщий список объектов |
| [ObjectWithBounds](./objectwithbounds) | Объект с границами. |
| [OpenTypeFontsCache](./opentypefontscache) | Кэш для шрифтов OpenType, установленных в системе. |
| [Pen](./pen) | Определяет объект, используемый для рисования линий, кривых и фигур. |
| [PixelDataFormat](./pixeldataformat) | Формат данных пикселей. Это неизменяемый объект. |
| [PixelsData](./pixelsdata) | Класс для хранения данных пикселей изображения и их границ. |
| [ProgressEventHandler](./progresseventhandler) | Функция обработчика событий Progress reference |
| [RasterCachedImage](./rastercachedimage) | Представляет растровое изображение, поддерживающее операции с растровой графикой. Это изображение кэширует пиксельные данные, когда это необходимо. |
| [RasterImage](./rasterimage) | Представляет растровое изображение, поддерживающее операции с растровой графикой. |
| [RawDataSettings](./rawdatasettings) | Настройки необработанных данных |
| [Region](./region) | Описывает внутреннюю часть графической фигуры, состоящей из прямоугольников и путей. Этот класс не может быть унаследован. |
| [ResolutionSetting](./resolutionsetting) | Настройка разрешения для параметров сохранения изображения. |
| [Shape](./shape) | Форма. Непрерывный набор точек, соединенных по определенному правилу. |
| [ShapeSegment](./shapesegment) | Представляет сегмент формы. Сегмент — это линия или кривая, соединяющая две точки. |
| [Source](./source) | Источник используется для хранения всей необходимой информации для канала объекта. |
| [SplitStreamContainer](./splitstreamcontainer) | Представляет контейнер разделенного потока, который содержит поток и предоставляет подпрограммы обработки потока. |
| [StreamContainer](./streamcontainer) | Представляет контейнер потока, который содержит поток и предоставляет подпрограммы обработки потока. |
| [StringFormat](./stringformat) | Инкапсулирует информацию о макете текста (например, выравнивание, ориентацию и позиции табуляции), манипуляции с отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть унаследован. |
| [TransparencySupporter](./transparencysupporter) | Объект, поддерживающий прозрачность. |
| [VectorImage](./vectorimage) | Векторное изображение является базовым классом для всех типов векторных изображений. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | Расширенный буферный процессор. |
| [IBufferProcessor](./ibufferprocessor) | Буферный процессор. |
| [IColorConverter](./icolorconverter) | Преобразователь цвета. |
| [IColorPalette](./icolorpalette) | Интерфейс цветовой палитры. |
| [IImageCreator](./iimagecreator) | Создатель изображения. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor) | Дескриптор создателя изображения, определяющий свойства создателя. Дескриптор создателя используется для преодоления необходимости содержать каждый экземпляр создателя изображения в памяти и проблем с многопоточностью. |
| [IImageDescriptor](./iimagedescriptor) | Дескриптор изображения. Содержит базовые свойства и методы для всех остальных типов дескрипторов изображений. |
| [IImageExporter](./iimageexporter) | Экспортер изображений. Может экспортировать данные из внутреннего формата Aspose.PSD в указанный формат данных. |
| [IImageExporterDescriptor](./iimageexporterdescriptor) | Представляет дескриптор экспортера изображений. Дескриптор экспортера используется для преодоления необходимости содержать каждый экспортер instance в памяти и проблем с многопоточностью. |
| [IImageLoader](./iimageloader) | Загрузчик изображений. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor) | Дескриптор загрузчика изображения, определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления необходимости содержать каждый экземпляр загрузчика изображений в памяти и проблем многопоточности. |
| [IIndexedColorConverter](./iindexedcolorconverter) | Преобразователь цвета для индексированных форматов изображений. |
| [IKeyedObject](./ikeyedobject) | Представляет интерфейс для объектов с ключами. |
| [IObjectWithBounds](./iobjectwithbounds) | Представляет объект с границами. |
| [IOrderedShape](./iorderedshape) | Представляет упорядоченную форму. Упорядоченная форма представляет собой непрерывный набор точек, имеющих начальную и конечную точки. Непрерывный набор точек, соединенных по определенному правилу. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Соответствует частично загруженным 32-битным пикселям ARGB. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | 64-битный загрузчик пикселей ARGB. |
| [IPartialPixelLoader](./ipartialpixelloader) | Соответствует частично загруженным пикселям. |
| [IPartialRawDataLoader](./ipartialrawdataloader) | Частичный загрузчик данных. |
| [IPsdColorPalette](./ipsdcolorpalette) | Цветовая палитра pasd |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | 32-битный загрузчик пикселей растрового изображения ARGB. |
| [IRasterImagePixelLoader](./irasterimagepixelloader) | Пиксельный загрузчик растрового изображения. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader) | Загрузчик необработанных данных растрового изображения. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [CacheType](./cachetype) | Указывает тип кэша для использования. |
| [CharacterSet](./characterset) | Представляет используемый набор символов. |
| [ColorAdjustType](./coloradjusttype) | Указывает, какие объекты используют информацию о настройке цвета. |
| [ColorChannelFlag](./colorchannelflag) | Определяет отдельные каналы в цветовом пространстве CMYK (голубой, пурпурный, желтый, черный). Это перечисление используется методами SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod) | Метод сравнения цветов для настройки на ближайший сосед |
| [ColorMatrixFlag](./colormatrixflag) | Определяет типы изображений и цветов, на которые будут влиять настройки цвета и оттенков серого[`ImageAttributes`](../aspose.psd/imageattributes) . |
| [ColorQuantizationMethod](./colorquantizationmethod) | Методы квантования цветов |
| [CompositingQuality](./compositingquality) | Указывает уровень качества для использования во время композитинга. |
| [DashCap](./dashcap) | Определяет тип графической формы для использования на обоих концах каждого тире в пунктирной линии. |
| [DashStyle](./dashstyle) | Определяет стиль пунктирных линий, нарисованных с помощью[`Pen`](../aspose.psd/pen) объект. |
| [DataRecoveryMode](./datarecoverymode) | Режим восстановления данных. |
| [DitheringMethod](./ditheringmethod) | Метод дизеринга. |
| [DitheringMethods](./ditheringmethods) | Методы сглаживания, используемые для управления преобразованием цвета. |
| [FileFormat](./fileformat) | Один из поддерживаемых форматов файлов PSD. |
| [FillMode](./fillmode) | Указывает, как заполняется внутренняя часть замкнутого контура. |
| [FontStyle](./fontstyle) | Определяет информацию о стиле, применяемую к тексту. |
| [GraphicsUnit](./graphicsunit) | Определяет единицу измерения данных. |
| [HatchStyle](./hatchstyle) | Определяет различные шаблоны, доступные для[`HatchBrush`](../aspose.psd.brushes/hatchbrush) объекты. |
| [HotkeyPrefix](./hotkeyprefix) | Указывает тип отображения префиксов горячих клавиш, относящихся к тексту. |
| [ImageFilterType](./imagefiltertype) | Используемые фильтры изображений |
| [InterpolationMode](./interpolationmode) | [`InterpolationMode`](../aspose.psd/interpolationmode) перечисление указывает алгоритм, который используется при масштабировании или повороте изображений. |
| [KnownColor](./knowncolor) | Определяет известные системные цвета. |
| [LineCap](./linecap) | Определяет доступные стили заглавных букв, с которыми[`Pen`](../aspose.psd/pen) объект может заканчиваться строкой. |
| [LineJoin](./linejoin) | Указывает, как соединить последовательные сегменты линии или кривой в фигуре (подконтуре), содержащейся в[`GraphicsPath`](../aspose.psd/graphicspath) объект. |
| [MatrixOrder](./matrixorder) | Указывает порядок операций преобразования матрицы. |
| [PdfComplianceVersion](./pdfcomplianceversion) | Указывает уровень соответствия PDF для выходного файла. |
| [PenAlignment](./penalignment) | Определяет выравнивание[`Pen`](../aspose.psd/pen) объекта относительно теоретической линии нулевой ширины. |
| [PenType](./pentype) | Определяет тип заливки[`Pen`](../aspose.psd/pen) объект использует для заполнения строк. |
| [PixelFormat](./pixelformat) | Фактическое значение формата данных пикселей. |
| [ResizeType](./resizetype) | Определяет тип изменения размера. |
| [ResolutionUnit](./resolutionunit) | Единица разрешения enum. |
| [RotateFlipType](./rotatefliptype) | Определяет степень поворота изображения и ось, используемую для отражения изображения. |
| [SeekOrigin](./seekorigin) | Предоставляет поля, представляющие опорные точки в[`StreamContainer`](../aspose.psd/streamcontainer) для поиска. |
| [SmoothingMode](./smoothingmode) | Указывает, применяется ли сглаживание (сглаживание) к линиям и кривым, а также к краям заполненных областей. |
| [StringAlignment](./stringalignment) | Определяет выравнивание текстовой строки относительно прямоугольника макета. |
| [StringDigitSubstitute](./stringdigitsubstitute) | Перечисление указывает, как заменять цифры в строке в соответствии с региональными настройками или языком пользователя. |
| [StringFormatFlags](./stringformatflags) | Указывает информацию об отображении и макете для текстовых строк. |
| [StringTrimming](./stringtrimming) | Указывает, как обрезать символы из строки, которая не полностью вписывается в форму макета. |
| [TextRenderingHint](./textrenderinghint) | Определяет качество рендеринга текста. |
| [WarpMode](./warpmode) | Указывает тип применяемого преобразования деформации. |
| [WrapMode](./wrapmode) | Указывает, как текстура или градиент укладываются мозаикой, когда они меньше, чем заполняемая область. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
