---
title: "aspose.psd"
type: docs
weight: 10
url: /ru/python-net/aspose.psd/
---


Модуль является ядром вложенных модулей и базовыми объектами, используемыми для обработки Aspose.PSD.

## **Classes**
| **Класс** | **Описание** |
| :- | :- |
| [Blend](/psd/python-net/aspose.psd/blend/) | Определяет шаблон смешивания. Этот класс не может быть унаследован. |
| [Brush](/psd/python-net/aspose.psd/brush/) | Базовый класс кисти. |
| [BuildVersionInfo](/psd/python-net/aspose.psd/buildversioninfo/) | Содержит информацию о текущей версии сборки. |
| [Cache](/psd/python-net/aspose.psd/cache/) | Содержит настройки кэша. |
| [CmykColor](/psd/python-net/aspose.psd/cmykcolor/) | CMYK‑цвет пикселя. |
| [CmykColorHelper](/psd/python-net/aspose.psd/cmykcolorhelper/) | Вспомогательные методы для работы с CMYK‑цветом, представленным как знаковое 32‑битное целое значение.<br/>            Предоставляет аналогичный API структуре [CmykColor](/psd/python-net/aspose.psd/cmykcolor/).<br/>            Он более легковесный, потому что CMYK‑цвет представлен просто как Int32, а не как структура с внутренними полями.<br/>            По возможности предпочтительно использовать статические методы этого класса вместо устаревшей<br/>            структуры [CmykColor](/psd/python-net/aspose.psd/cmykcolor/). |
| [Color](/psd/python-net/aspose.psd/color/) | Цвет пикселя. |
| [ColorBlend](/psd/python-net/aspose.psd/colorblend/) | Определяет массивы цветов и позиций, используемые для интерполяции смешения цветов в многокрасочном градиенте. Этот класс не может быть унаследован. |
| [ColorMap](/psd/python-net/aspose.psd/colormap/) | Определяет карту для преобразования цветов. Несколько методов класса [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) корректируют цвета изображения, используя таблицу переопределения цветов, которая представляет собой массив структур [ColorMap](/psd/python-net/aspose.psd/colormap/). Не наследуемый. |
| [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) | Определяет матрицу 5 × 5, содержащую координаты пространства RGBA. Несколько методов класса [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) корректируют цвета изображения, используя цветовую матрицу. Этот класс не может быть унаследован. |
| [ColorPalette](/psd/python-net/aspose.psd/colorpalette/) | Определяет массив цветов, составляющих цветовую палитру. Цвета представлены в виде 32‑битных ARGB‑цветов. Не наследуемый. |
| [ColorPaletteHelper](/psd/python-net/aspose.psd/colorpalettehelper/) | Вспомогательный класс для работы с цветовыми палитрами. |
| [ColorTranslator](/psd/python-net/aspose.psd/colortranslator/) | Преобразует цвета в структуры GDI+ Color и из них. Этот класс не может быть унаследован. |
| [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) | Инкапсулирует пользовательскую определяемую форму конца линии. |
| [DataStreamSupporter](/psd/python-net/aspose.psd/datastreamsupporter/) | Контейнер потока данных. |
| [DisposableObject](/psd/python-net/aspose.psd/disposableobject/) | Представляет объект, подлежащий освобождению. |
| [Figure](/psd/python-net/aspose.psd/figure/) | Фигура. Контейнер для фигур. |
| [FileStreamContainer](/psd/python-net/aspose.psd/filestreamcontainer/) | Вспомогательный класс для обработки файловых потоков. |
| [Font](/psd/python-net/aspose.psd/font/) | Определяет определённый формат текста, включая семейство шрифта, размер и атрибуты стиля. Этот класс не может быть унаследован. |
| [FontSettings](/psd/python-net/aspose.psd/fontsettings/) | Общие настройки шрифтов рендерера векторных форматов PSD. |
| [Graphics](/psd/python-net/aspose.psd/graphics/) | Представляет графику в соответствии с графическим движком, используемым в текущей сборке. |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) | Представляет серию соединённых линий и кривых. Этот класс не может быть унаследован. |
| [IAdvancedBufferProcessor](/psd/python-net/aspose.psd/iadvancedbufferprocessor/) | Продвинутый процессор буфера. |
| [IBufferProcessor](/psd/python-net/aspose.psd/ibufferprocessor/) | Процессор буфера. |
| [IColorConverter](/psd/python-net/aspose.psd/icolorconverter/) | Конвертер цветов. |
| [IColorPalette](/psd/python-net/aspose.psd/icolorpalette/) | Интерфейс цветовой палитры. |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator/) | Создатель изображения. |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor/) | Дескриптор создателя изображения, определяющий свойства создателя. Дескриптор создателя используется для преодоления<br/>            необходимости содержать каждый экземпляр создателя изображения в памяти и проблем многопоточности. |
| [IImageDescriptor](/psd/python-net/aspose.psd/iimagedescriptor/) | Дескриптор изображения. Содержит базовые свойства и методы для всех остальных типов дескрипторов изображений. |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter/) | Экспортер изображения. Может экспортировать данные из внутреннего формата Aspose.PSD в указанный формат данных. |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor/) | Представляет дескриптор экспортера изображения. Дескриптор экспортера используется для преодоления необходимости содержать каждый экземпляр экспортера<br/>            в памяти и проблем многопоточности. |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader/) | Загрузчик изображения. |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor/) | Дескриптор загрузчика изображения, определяющий свойства загрузчика. Дескриптор загрузчика используется для преодоления<br/>            необходимости содержать каждый экземпляр загрузчика изображения в памяти и проблем многопоточности. |
| [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter/) | Конвертер цветов для индексированных форматов изображений. |
| [IKeyedObject](/psd/python-net/aspose.psd/ikeyedobject/) | Представляет интерфейс для объектов с ключами. |
| [IObjectWithBounds](/psd/python-net/aspose.psd/iobjectwithbounds/) | Представляет объект с границами. |
| [IOrderedShape](/psd/python-net/aspose.psd/iorderedshape/) | Представляет упорядоченную форму. Упорядоченная форма — это непрерывный набор точек, имеющих начальную и конечную точку.<br/>            Непрерывный набор точек, соединённых по определённому правилу. |
| [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader/) | Соответствует частично загруженным 32-битным пикселям ARGB. |
| [IPartialArgb64PixelLoader](/psd/python-net/aspose.psd/ipartialargb64pixelloader/) | Загрузчик 64-битных пикселей ARGB. |
| [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader/) | Соответствует частично загруженным пикселям. |
| [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader/) | Загрузчик частичных данных. |
| [IPsdColorPalette](/psd/python-net/aspose.psd/ipsdcolorpalette/) | Цветовая палитра pasd |
| [IRasterImageArgb32PixelLoader](/psd/python-net/aspose.psd/irasterimageargb32pixelloader/) | Загрузчик 32-битных пикселей ARGB растрового изображения. |
| [IRasterImagePixelLoader](/psd/python-net/aspose.psd/irasterimagepixelloader/) | Загрузчик пикселей растрового изображения. |
| [IRasterImageRawDataLoader](/psd/python-net/aspose.psd/irasterimagerawdataloader/) | Загрузчик необработанных данных растрового изображения. |
| [Image](/psd/python-net/aspose.psd/image/) | Изображение является базовым классом для всех типов изображений. |
| [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) | Объект [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) содержит информацию о том, как цвета растровых изображений и метафайлов изменяются во время рендеринга. Объект [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) поддерживает несколько настроек коррекции цвета, включая матрицы коррекции цвета, матрицы коррекции в градациях серого, значения гамма‑коррекции, таблицы сопоставления цветов и пороговые значения цвета. Во время рендеринга цвета могут быть скорректированы, затемнены, осветлены и удалены. Чтобы применить такие изменения, инициализируйте объект [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) и передайте путь к этому объекту [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) (вместе с путём к объекту [Image](/psd/python-net/aspose.psd/image/)) в метод DrawImage. |
| [ImageCreatorsRegistry](/psd/python-net/aspose.psd/imagecreatorsregistry/) | Представляет реестр создателей изображений. |
| [ImageExportersRegistry](/psd/python-net/aspose.psd/imageexportersregistry/) | Представляет реестр экспортёров изображений. |
| [ImageLoadersRegistry](/psd/python-net/aspose.psd/imageloadersregistry/) | Представляет реестр загрузчиков изображений. |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase/) | Базовые параметры изображения. |
| [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings/) | Класс настроек изменения размера изображения |
| [IntRange](/psd/python-net/aspose.psd/intrange/) | Класс для представления последовательности элементов |
| [License](/psd/python-net/aspose.psd/license/) | Предоставляет методы для лицензирования компонента. |
| [LoadOptions](/psd/python-net/aspose.psd/loadoptions/) | Представляет параметры загрузки. |
| [Matrix](/psd/python-net/aspose.psd/matrix/) | Заменяет матрицу GDI+. |
| [Metered](/psd/python-net/aspose.psd/metered/) | Предоставляет методы для установки измеряемого ключа. |
| [NonGenericDictionary](/psd/python-net/aspose.psd/nongenericdictionary/) | Представляет необобщённый словарь. |
| [NonGenericList](/psd/python-net/aspose.psd/nongenericlist/) | Необобщённый список объектов |
| [ObjectWithBounds](/psd/python-net/aspose.psd/objectwithbounds/) | Объект, имеющий границы. |
| [OpenTypeFontsCache](/psd/python-net/aspose.psd/opentypefontscache/) | Кеш для шрифтов OpenType, установленных в системе. |
| [Pen](/psd/python-net/aspose.psd/pen/) | Определяет объект, используемый для рисования линий, кривых и фигур. |
| [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat/) | Формат данных пикселей. Это неизменяемый объект. |
| [PixelsData](/psd/python-net/aspose.psd/pixelsdata/) | Класс для хранения данных пикселей изображения и его границ. |
| [PluginLicenseException](/psd/python-net/aspose.psd/pluginlicenseexception/) | Исключение для лицензии плагина |
| [Point](/psd/python-net/aspose.psd/point/) | Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости. |
| [PointF](/psd/python-net/aspose.psd/pointf/) | Представляет упорядоченную пару координат x и y с плавающей точкой, определяющих точку в двумерной плоскости. |
| [RasterCachedImage](/psd/python-net/aspose.psd/rastercachedimage/) | Представляет растровое изображение, поддерживающее операции растровой графики. Это изображение кэширует данные пикселей при необходимости. |
| [RasterImage](/psd/python-net/aspose.psd/rasterimage/) | Представляет растровое изображение, поддерживающее операции растровой графики. |
| [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings/) | Настройки необработанных данных |
| [Rectangle](/psd/python-net/aspose.psd/rectangle/) | Хранит набор из четырёх целых чисел, представляющих положение и размер прямоугольника. |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef/) | Хранит набор из четырёх чисел с плавающей точкой, представляющих положение и размер прямоугольника. |
| [Region](/psd/python-net/aspose.psd/region/) | Описывает внутреннюю часть графической формы, состоящей из прямоугольников и путей. Этот класс не может быть унаследован. |
| [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting/) | Настройка разрешения для параметров сохранения изображения. |
| [Shape](/psd/python-net/aspose.psd/shape/) | Форма. Непрерывный набор точек, соединённых по определённому правилу. |
| [ShapeSegment](/psd/python-net/aspose.psd/shapesegment/) | Представляет сегмент формы. Сегмент — это линия или кривая, соединяющая две точки. |
| [Size](/psd/python-net/aspose.psd/size/) | Представляет размер. |
| [SizeF](/psd/python-net/aspose.psd/sizef/) | Сохраняет упорядоченную пару чисел с плавающей запятой, обычно ширину и высоту прямоугольника. |
| [Source](/psd/python-net/aspose.psd/source/) | Источник используется для хранения всей соответствующей информации для объектного канала. |
| [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) | Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока. |
| [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) | Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока. |
| [StringFormat](/psd/python-net/aspose.psd/stringformat/) | Инкапсулирует информацию о размещении текста (например, выравнивание, ориентацию и табуляцию), манипуляции отображением (например, вставку многоточия и замену национальных цифр) и функции OpenType. Этот класс не может быть унаследован. |
| [TransparencySupporter](/psd/python-net/aspose.psd/transparencysupporter/) | Объект, поддерживающий прозрачность. |
| [VectorImage](/psd/python-net/aspose.psd/vectorimage/) | Векторное изображение является базовым классом для всех типов векторных изображений. |
## **Enumerations**
| **Перечисление** | **Описание** |
| :- | :- |
| [CacheType](/psd/python-net/aspose.psd/cachetype/) | Указывает тип кеша, который следует использовать. |
| [CharacterSet](/psd/python-net/aspose.psd/characterset/) | Представляет используемый набор символов. |
| [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) | Указывает, какие объекты используют информацию о коррекции цвета. |
| [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) | Указывает отдельные каналы в цветовом пространстве CMYK (циан, маджента, желтый, чёрный). Этот перечисление используется методами SetOutputChannel. |
| [ColorCompareMethod](/psd/python-net/aspose.psd/colorcomparemethod/) | Метод сравнения цветов для приведения к ближайшему соседу |
| [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) | Указывает типы изображений и цветов, которые будут затронуты настройками коррекции цвета и градаций серого объекта [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](/psd/python-net/aspose.psd/colorquantizationmethod/) | Методы квантования цветов |
| [CompositingQuality](/psd/python-net/aspose.psd/compositingquality/) | Указывает уровень качества, используемый при композитинге. |
| [DashCap](/psd/python-net/aspose.psd/dashcap/) | Указывает тип графической формы, используемой на обоих концах каждого тире в пунктирной линии. |
| [DashStyle](/psd/python-net/aspose.psd/dashstyle/) | Указывает стиль пунктирных линий, рисуемых объектом [Pen](/psd/python-net/aspose.psd/pen/). |
| [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode/) | Режим восстановления данных. |
| [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod/) | Метод дизеринга. |
| [DitheringMethods](/psd/python-net/aspose.psd/ditheringmethods/) | Методы дизеринга, используемые для управления преобразованием цвета. |
| [FileFormat](/psd/python-net/aspose.psd/fileformat/) | Один из поддерживаемых форматов файлов PSD. |
| [FillMode](/psd/python-net/aspose.psd/fillmode/) | Указывает, как заполняется внутренность замкнутого контура. |
| [FontStyle](/psd/python-net/aspose.psd/fontstyle/) | Указывает информацию о стиле, применяемую к тексту. |
| [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) | Указывает единицу измерения для заданных данных. |
| [HatchStyle](/psd/python-net/aspose.psd/hatchstyle/) | Указывает различные шаблоны, доступные для объектов [HatchBrush](/psd/python-net/aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](/psd/python-net/aspose.psd/hotkeyprefix/) | Указывает тип отображения префиксов горячих клавиш, относящихся к тексту. |
| [ImageFilterType](/psd/python-net/aspose.psd/imagefiltertype/) | Фильтры изображений для использования |
| [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) | Перечисление [InterpolationMode](/psd/python-net/aspose.psd/interpolationmode/) указывает алгоритм, используемый при масштабировании или вращении изображений. |
| [KnownColor](/psd/python-net/aspose.psd/knowncolor/) | Указывает известные системные цвета. |
| [LineCap](/psd/python-net/aspose.psd/linecap/) | Указывает доступные стили окончаний, с которыми объект [Pen](/psd/python-net/aspose.psd/pen/) может завершать линию. |
| [LineJoin](/psd/python-net/aspose.psd/linejoin/) | Указывает, как соединять последовательные отрезки линий или кривых в фигуре (подпуть), содержащейся в объекте [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |
| [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) | Указывает порядок операций преобразования матрицы. |
| [PdfComplianceVersion](/psd/python-net/aspose.psd/pdfcomplianceversion/) | Указывает уровень соответствия PDF для выходного файла. |
| [PenAlignment](/psd/python-net/aspose.psd/penalignment/) | Указывает выравнивание объекта [Pen](/psd/python-net/aspose.psd/pen/) относительно теоретической линии нулевой ширины. |
| [PenType](/psd/python-net/aspose.psd/pentype/) | Указывает тип заливки, который объект [Pen](/psd/python-net/aspose.psd/pen/) использует для заполнения линий. |
| [PixelFormat](/psd/python-net/aspose.psd/pixelformat/) | Фактическое значение формата пиксельных данных. |
| [ResizeType](/psd/python-net/aspose.psd/resizetype/) | Указывает тип изменения размера. |
| [ResolutionUnit](/psd/python-net/aspose.psd/resolutionunit/) | Перечисление единиц разрешения. |
| [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype/) | Указывает, насколько изображение вращается и ось, используемую для его отражения. |
| [SeekOrigin](/psd/python-net/aspose.psd/seekorigin/) | Предоставляет поля, представляющие контрольные точки в [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/) для перемещения. |
| [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode/) | Указывает, применяется ли сглаживание (антиалиасинг) к линиям и кривым и к краям заполненных областей. |
| [StringAlignment](/psd/python-net/aspose.psd/stringalignment/) | Указывает выравнивание текстовой строки относительно её прямоугольника размещения. |
| [StringDigitSubstitute](/psd/python-net/aspose.psd/stringdigitsubstitute/) | Перечисление указывает, как заменять цифры в строке в соответствии с локалью или языком пользователя. |
| [StringFormatFlags](/psd/python-net/aspose.psd/stringformatflags/) | Указывает информацию о отображении и размещении текстовых строк. |
| [StringTrimming](/psd/python-net/aspose.psd/stringtrimming/) | Указывает, как обрезать символы в строке, которая не полностью помещается в форму размещения. |
| [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint/) | Указывает качество рендеринга текста. |
| [WarpMode](/psd/python-net/aspose.psd/warpmode/) | Указывает тип применяемого искажения (warp) трансформации. |
| [WrapMode](/psd/python-net/aspose.psd/wrapmode/) | Указывает, как текстура или градиент заполняются плиткой, когда они меньше области заполнения. |
