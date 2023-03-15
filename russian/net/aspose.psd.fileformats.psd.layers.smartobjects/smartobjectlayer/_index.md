---
title: Class SmartObjectLayer
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.SmartObjects.SmartObjectLayer сорт. Определяет класс SmartObjectLayer который содержит встроенный в файл PSD или связанный смартобъект во внешнем файле. С помощью смартобъектов вы можете выполнять неразрушающие преобразования. Вы можете масштабировать вращать наклонять искажать преобразовывать перспективу или деформировать слой без потери исходных данных изображения или качества поскольку преобразования не влияют на исходные данные. Работайте с векторными данными такими как векторные рисунки из Illustrator которые в противном случае будет растеризован. Выполнить неразрушающую фильтрацию. Фильтры применяемые к смартобъектам можно редактировать в любое время. Редактируйте один смартобъект и автоматически обновляйте все его связанные экземпляры. Применяйте маску слоя связанную или не связанную со слоем смартобъекта. Пробуйте различные дизайны с низким изображениязаполнители разрешения которые вы позже замените окончательными версиями. В Adobe Photoshop вы можете встроить содержимое изображения в документ PSD. Дополнительная информация здесьhttps//helpx.adobe.com/photoshop/using/createsmartobjects.html Слой со встроенным смартобъектом содержит размещенные PlLd и ресурсы SoLd со свойствами смартобъекта. Ресурс PlLd может быть один для версий PSD старше 10. Эти ресурсы содержат UniqueId LiFdDataSource в глобальном Lnk2Resource со встроенным имя_файла и другие параметры включая встроенное содержимое файла в исходном формате в виде массива байтов.
type: docs
weight: 3490
url: /ru/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

Определяет класс SmartObjectLayer, который содержит встроенный в файл PSD или связанный смарт-объект во внешнем файле. С помощью смарт-объектов вы можете: выполнять неразрушающие преобразования. Вы можете масштабировать, вращать, наклонять, искажать, преобразовывать перспективу или деформировать слой без потери исходных данных изображения или качества, поскольку преобразования не влияют на исходные данные. Работайте с векторными данными, такими как векторные рисунки из Illustrator, которые в противном случае будет растеризован. Выполнить неразрушающую фильтрацию. Фильтры, применяемые к смарт-объектам, можно редактировать в любое время. Редактируйте один смарт-объект и автоматически обновляйте все его связанные экземпляры. Применяйте маску слоя, связанную или не связанную со слоем смарт-объекта. Пробуйте различные дизайны с низким изображения-заполнители разрешения, которые вы позже замените окончательными версиями. В Adobe� Photoshop� вы можете встроить содержимое изображения в документ PSD. Дополнительная информация здесь:[https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) Слой со встроенным смарт-объектом содержит размещенные (PlLd) и ресурсы SoLd со свойствами смарт-объекта. Ресурс PlLd может быть один для версий PSD старше 10. Эти ресурсы содержат UniqueId LiFdDataSource в глобальном Lnk2Resource со встроенным имя_файла и другие параметры, включая встроенное содержимое файла в исходном формате в виде массива байтов.

```csharp
public class SmartObjectLayer : Layer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Получает количество бит изображения на пиксель. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Получает параметры наложения. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Получает или задает ключ режима наложения. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Получает сигнатуру режима наложения. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Получает или задает позицию нижнего слоя. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Получает или устанавливает информацию о канале. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Получает количество каналов слоя. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Получает или задает отсечение слоя. 0 = базовый, 1 = не базовый. |
| [Container](../../aspose.psd/image/container/) { get; } | Получает[`Image`](../../aspose.psd/image/) контейнер. |
| [Contents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/) { get; set; } | Получает или задает содержимое слоя смарт-объекта. Содержимое встроенного смарт-объекта представляет собой встроенный файл необработанного изображения:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) и его свойства. Содержимое связанного смарт-объекта — это необработанное содержимое связанного файла изображения, если оно доступно, и его свойства:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Мы не поддерживаем загрузку из графической библиотеки Adobe� Photoshop� � при[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) верно. Для обычных файлов ссылок сначала используется[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) искать файл относительно пути к исходному изображениюSourceImagePath , если нет в наличии смотрим[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , если нет то ищем файл ссылки в той же директории где наш образ:SourceImagePath . |
| [ContentsBounds](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentsbounds/) { get; set; } | Получает или задает границы содержимого смарт-объекта. |
| [ContentsSource](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contentssource/) { get; set; } | Получает или задает источник содержимого смарт-объекта. |
| [ContentType](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contenttype/) { get; } | Получает тип содержимого слоя смарт-объекта. Содержимое встроенного смарт-объекта представляет собой встроенный файл необработанного изображения:[`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) . Содержимое связанного смарт-объекта — это необработанное содержимое связанного файла изображения, если оно доступно:[`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) . Мы не поддерживаем загрузку из графической библиотеки Adobe� Photoshop� � при[`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) верно. Для обычных файлов ссылок сначала используется[`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) искать файл относительно пути к исходному изображениюSourceImagePath , если нет в наличии смотрим[`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/) , если нет то ищем файл ссылки в той же директории где наш образ:SourceImagePath . |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Получает или задает отображаемое имя слоя. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Получает длину дополнительной информации слоя в байтах. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Получает значение формата файла |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Получает или задает заполнитель слоя. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Получает или задает непрозрачность заливки. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Получает или устанавливает флаги слоя. бит 0 = защита от прозрачности; бит 1 = видимый; бит 2 = устаревший; бит 3 = 1 для Photoshop 5.0 и более поздних версий, сообщает, содержит ли бит 4 полезную информацию; бит 4 = пиксельные данные, не относящиеся к внешнему виду документа. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Получает значение, указывающее, есть ли у этого экземпляра альфа. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Получает высоту изображения. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Получает или задает значение, указывающее, виден ли слой |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Получает значение, указывающее, виден ли этот экземпляр в группе (если слой не входит в группу, это означает корневую группу). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Получает или задает данные диапазонов смешивания слоев. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Получает или задает дату и время создания слоя. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Получает или устанавливает блокировку слоя. Обратите внимание, что если флаг LayerFlags.TransparencyProtected установлен, он будет перезаписан флагом блокировки слоя. |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Получает или задает данные маски слоя. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Получает параметры слоя. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Получает или задает положение левого слоя. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Получает общую длину слоя в байтах. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Получает или задает имя слоя. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Получает или задает непрозрачность слоя. 0 = прозрачный, 255 = непрозрачный. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения предварительно умножаться. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Получает или задает пользовательский конвертер цветов |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Получает или задает резервный индекс для использования, когда индекс палитры выходит за пределы |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Получает или задает преобразователь индексированных цветов |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Получает исходный размер строки в байтах. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Получает или задает ресурсы слоя. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Получает или устанавливает правильное положение слоя. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Получает или задает выделение цвета декоративного листа в списке слоев |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| [SmartFilters](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartfilters/) { get; } | Получает интеллектуальные фильтры. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/smartobjectprovider/) { get; } | Получает поставщика смарт-объекта. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Получает или задает положение верхнего слоя. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда доступна загрузка необработанных данных. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Получает или задает разрешение по вертикали в пикселях на дюйм этого[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Получает ширину изображения. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Добавляет маску к текущему слою. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Настройка яркости изображения. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Изображение контрастное |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегрального порогового значения изображения |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Бинаризация изображения с пороговым значением Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| [ConvertToLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/converttolinked/)(string) | Преобразует этот встроенный смарт-объект в связанный смарт-объект. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Обрезка изображения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Рисует изображение на слое. |
| [DuplicateLayer](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/)() | Создает новый слой смарт-объекта, копируя этот. Обратите внимание, что для встроенных смарт-объектов встроенное изображение является общим. Если вы хотите скопировать встроенное изображение, используйте[`NewSmartObjectViaCopy`](./newsmartobjectviacopy/) метод. |
| [EmbedLinked](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/embedlinked/)() | Встраивает связанный смарт-объект в этот слой. |
| [ExportContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/)(string) | Экспортирует встроенное или связанное содержимое в файл. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Получает изображение 32-битного пикселя ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Получает массив 32-битных пикселей ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с помощью частичной загрузки пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичной загрузки пикселей. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Возвращает хэш-код для этого экземпляра. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Получает дату и время последнего изменения образа ресурса. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры, основанные на настройках исходного файла. Это может быть полезно для сохранения без изменений битовой глубины и других параметров исходного изображения. Например, если мы загружаем черно-белое изображение PNG с 1 битом на пиксель, а затем сохраните его, используя the [`Save`](../../aspose.psd/datastreamsupporter/save/) будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их [`Save`](../../aspose.psd/image/save/)метод в качестве второго параметра. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Получает пиксель изображения. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Получает угол наклона. Этот метод применим к отсканированным текстовым документам для определения угла наклона при сканировании. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Преобразование изображения в его представление в градациях серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Загружает 32-битные пиксели ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Загружает 64-битные пиксели ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/)(LoadOptions) | Получает содержимое встроенного или связанного изображения слоя смарт-объекта. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Загружает 32-битные пиксели ARGB частично по пакетам. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Загружает пиксели частично пачками. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto/)(Layer) | Объединяет слой с указанным layer |
| [NewSmartObjectViaCopy](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/newsmartobjectviacopy/)() | Создает новый слой смарт-объекта, копируя этот слой. Воспроизводит функцию «Слой -&gt; Смарт-объекты -&gt; Новый смарт-объект через копирование» Adobe Photoshop. также копируется. Если вы хотите поделиться встроенным изображением, используйте[`DuplicateLayer`](./duplicatelayer/) метод. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) и[`Rotate`](../../aspose.psd/rasterimage/rotate/) методы. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) и[`Rotate`](../../aspose.psd/rasterimage/rotate/) методы. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [RelinkToFile](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/relinktofile/)(string) | Повторно связывает связанный смарт-объект с новым файлом. После этого нет необходимости вызывать метод UpdateModifiedContent. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения сглаженных краев. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents)(Image) | Заменяет содержимое смарт-объекта, встроенное в слой смарт-объекта. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_2)(string) | Заменяет содержимое файлом. После этого нет необходимости вызывать метод UpdateModifiedContent. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_1)(Image, ResolutionSetting) | Заменяет содержимое смарт-объекта, встроенное в слой смарт-объекта. |
| [ReplaceContents](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/replacecontents/#replacecontents_3)(string, ResolutionSetting) | Заменяет содержимое файлом. После этого нет необходимости вызывать метод UpdateModifiedContent. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание: если вы используете его на изображениях без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. По умолчаниюLeftTopToLeftTopиспользуется. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Изменяет размер высоты пропорционально. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Изменяет ширину пропорционально. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Повернуть изображение вокруг центра. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.psd/image/save/)() | Сохраняет данные изображения в базовый поток. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанном месте файла. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Сохраняет 32-битные пиксели ARGB. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Сохраняет пиксели. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Устанавливает 32-битный пиксель изображения ARGB для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Задает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Устанавливает разрешение для этого[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Создает поверхностную копию текущего слоя. Пожалуйста[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) для объяснения. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Преобразует растровое изображение в растровое. |
| [UpdateModifiedContent](../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/updatemodifiedcontent/)() | Обновляет кэш изображения слоя смарт-объекта с измененным содержимым. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

### Примеры

Следующий код демонстрирует поддержку встроенных смарт-объектов.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// В этом примере показано, как изменить слой смарт-объекта в PSD-файле и экспортировать/обновить исходное встроенное содержимое смарт-объекта.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Давайте экспортируем встроенное изображение смарт-объекта из слоя смарт-объекта PSD
        smartObjectLayer.ExportContents(exportPath);

        // Проверяем, правильно ли сохранено исходное изображение
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Давайте инвертируем исходное изображение смарт-объекта
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Давайте заменим встроенное изображение смарт-объекта в слое PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Проверяем, корректно ли сохранено обновленное изображение
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Смотрите также

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider/)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects/)
* сборка [Aspose.PSD](../../)


