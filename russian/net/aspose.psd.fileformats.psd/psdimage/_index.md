---
title: PsdImage
second_title: Справочник по Aspose.PSD для .NET API
description: Определяет класс PsdImage предоставляющий возможность загружать редактировать сохранять файлы PSD а также обновлять свойства добавлять водяные знаки выполнять графические операции или преобразовать один формат файла в другой. Aspose.PSD поддерживает импорт в виде слоя и экспорт в следующие форматы Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb а также экспорт в Pdf с выбираемый текст
type: docs
weight: 3480
url: /ru/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Определяет класс PsdImage, предоставляющий возможность загружать, редактировать, сохранять файлы PSD, а также обновлять свойства, добавлять водяные знаки, выполнять графические операции или преобразовать один формат файла в другой. Aspose.PSD поддерживает импорт в виде слоя и экспорт в следующие форматы: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, а также экспорт в Pdf с выбираемый текст

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdImage](psdimage#constructor)(RasterImage) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)из существующего растрового изображения (не psd изображения) с цветовым режимом RGB с 4 каналами 8 бит/канал и без сжатия. |
| [PsdImage](psdimage#constructor_4)(Stream) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)по указанному пути из растрового изображения (не psd изображение в потоке). Используется для инициализации psd изображения с параметрами по умолчанию - Цветовой режим - rgb, 4 канала, 8 бит на канал, Сжатие - Raw. |
| [PsdImage](psdimage#constructor_6)(string) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)по указанному пути из растрового изображения (не psd изображение в пути). Используется для инициализации psd изображения с параметрами по умолчанию - Цветовой режим - rgb, 4 канала, 8 бит на канал, Сжатие - Raw. |
| [PsdImage](psdimage#constructor_2)(int, int) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)с указанными шириной и высотой. Используется для инициализации пустого изображения psd. |
| [PsdImage](psdimage#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)из существующего растрового изображения (не psd изображения) с параметрами конструктора. |
| [PsdImage](psdimage#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)по указанному пути из растрового изображения (не psd изображение в потоке) с параметрами конструктора. |
| [PsdImage](psdimage#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)по указанному пути из растрового изображения (не psd изображение в пути) с параметрами конструктора. |
| [PsdImage](psdimage#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса[`PsdImage`](../psdimage)с указанными шириной, высотой, палитрой, цветом режим, количество каналов и разрядность каналов, а также заданные параметры режима сжатия. Используется для инициализации пустого изображения psd. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer) { get; set; } | Получает или задает активный слой. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel) { get; } | Получает биты на канал. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount) { get; } | Получает количество каналов PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile) { get; set; } | Получает или задает цветовой профиль CMYK для изображений CMYK PSD. Должен быть в паре с RgbColorProfile для правильного преобразования цвета. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode) { get; set; } | Получает или задает цветовой режим. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression) { get; } | Получает метод сжатия. |
| [Container](../../aspose.psd/image/container) { get; } | Получает контейнер[`Image`](../../aspose.psd/image). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat) { get; } | Получает значение формата файла |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle) { get; set; } | Получает или задает глобальный угол. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo) { get; } | Получает информацию о глобальной маске слоя. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources) { get; set; } | Получает или задает ресурсы глобального слоя. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile) { get; set; } | Получает или задает цветовой профиль GRAY (монохромный) для PSD-изображений в градациях серого. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha) { get; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.psd/rasterimage). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata) { get; set; } | Получает или задает значение, указывающее, содержит ли первый альфа-канал данные о прозрачности для объединенного результата при указании данных слоев. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height) { get; } | Получает высоту изображения. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`PsdImage`](../psdimage). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Получает непрозрачность этого изображения. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources) { get; set; } | Получает или задает ресурсы изображения PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten) { get; } | Получает значение, указывающее, сведено ли psd-изображение. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers) { get; set; } | Получает или задает слои PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager) { get; } | Получает диспетчер связанных слоев. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения предварительно умножаться. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Получает или задает пользовательский преобразователь цвета |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Получает или задает резервный индекс для использования, когда индекс палитры выходит за пределы |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Получает или задает преобразователь индексированных цветов |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Получает необработанный размер строки в байтах. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile) { get; set; } | Получает или задает цветовой профиль RGB для изображений CMYK PSD. Должен быть в паре с CmykColorProfile для правильного преобразования цвета. |
| [Size](../../aspose.psd/image/size) { get; } | Получает размер изображения. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider) { get; } | Получает поставщика смарт-объекта. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда доступна загрузка необработанных данных. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version) { get; set; } | Получает или задает версию. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution) { get; set; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого[`PsdImage`](../psdimage). |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width) { get; } | Получает ширину изображения. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer)() | Добавляет черно-белый корректирующий слой. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer)(int, int) | Добавляет корректирующий слой яркости/контрастности. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer)() | Добавляет корректирующий слой микшера каналов с параметрами по умолчанию |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer)() | Добавляет корректирующий слой цветового баланса. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer)() | Добавляет корректирующий слой Кривые. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer)(float, float, float) | Добавляет корректирующий слой экспозиции. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer)() | Добавляет корректирующий слой оттенка/насыщенности. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer)() | Добавляет инвертированный корректирующий слой. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer)(Layer) | Добавляет слой. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup)(string, int, bool) | Добавляет группу слоев. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer)() | Добавляет корректирующий слой «Уровни». |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer)(Color) | Добавляет слой PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer)() | Добавляет новый обычный слой. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer)(string, Rectangle) | Добавляет новый текстовый слой. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer)() | Добавляет корректирующий слой Vibrance. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness)(int) | Настройка яркости изображения. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast)(float) | Контраст изображения |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma_1)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley_1)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu)() | Бинаризация изображения с порогом Оцу |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert)(PsdOptions) | Преобразует этот формат изображения в указанный в опциях. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop#crop)(Rectangle) | Обрезка изображения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage)() | Сглаживает все слои. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Получает 32-битный пиксель изображения ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Получает массив 32-битных пикселей ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с помощью частичной загрузки пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичной загрузки пикселей. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Получает дату и время последнего изменения образа ресурса. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../../aspose.psd/datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../../aspose.psd/image/save)метод в качестве второго параметра. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Получает пиксель изображения. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Получает угол наклона. Этот метод применим к отсканированным текстовым документам, для определения угла перекоса при сканировании. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale)() | Преобразование изображения в его представление в градациях серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Загружает 32-битные пиксели ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Загружает 64-битные пиксели ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Загружает 32-битные ARGB-пиксели частично пачками. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Загружает пиксели частично пачками. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers)(Layer, Layer) | Объединяет слои. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)и[`Rotate`](../../aspose.psd/rasterimage/rotate)методы. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)и[`Rotate`](../../aspose.psd/rasterimage/rotate)методы. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения гладких краев. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor#replacecolor_1)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения гладких краев. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание:если вы используете его на изображениях без прозрачности, все цвета будут заменены одним. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание:если вы используете его на изображениях без прозрачности, все цвета будут заменены одним. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Изменяет размер изображения. По умолчанию используетсяLeftTopToLeftTop. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Пропорционально изменяет размер высоты. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет размер высоты. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Пропорционально изменяет размер высоты. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Пропорционально изменяет ширину. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Пропорционально изменяет ширину. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate_1)(float, bool, Color) | Повернуть изображение вокруг центра. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.psd/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Сохраняет данные объекта в указанном месте файла. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Сохраняет 32-битные пиксели ARGB. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Сохраняет пиксели. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Устанавливает 32-битный пиксель изображения ARGB для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Устанавливает разрешение для этого[`RasterImage`](../../aspose.psd/rasterimage). |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Преобразует растровое изображение в растровое. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion) | Версия PSD по умолчанию. |

### Примеры

Следующий код демонстрирует возможность поворота изображения на заданное значение угла.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Вращение всего изображения
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Вращение слоя
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Смотрите также

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
