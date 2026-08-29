---
title: "Класс PsdImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.PsdImage класс. Определяет класс PsdImage, который предоставляет возможность загружать, редактировать и сохранять PSD‑файлы, а также обновлять свойства, добавлять водяные знаки, выполнять графические операции или конвертировать один формат файла в другой. Aspose.PSD поддерживает импорт в виде слоя и экспорт в следующие форматы: Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb, а также экспорт в Pdf с выделяемым текстом."
type: docs
weight: 4050
url: /ru/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Определяет класс PsdImage, который предоставляет возможность загружать, редактировать и сохранять файлы PSD, а также обновлять свойства, добавлять водяные знаки, выполнять графические операции или конвертировать один формат файла в другой. Aspose.PSD поддерживает импорт в виде слоя и экспорт в следующие форматы: PNG, JPEG, JPEG2000, GIF, BMP, TIFF, PSD, PSB, а также экспорт в PDF с выделяемым текстом.

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Инициализирует новый экземпляр класса `PsdImage` из существующего растрового изображения (не PSD‑изображения) с режимом цвета RGB, 4 каналами, 8 бит/канал и без сжатия. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Инициализирует новый экземпляр класса `PsdImage` из указанного пути к растровому изображению (не PSD‑изображению в потоке). Используется для инициализации PSD‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Инициализирует новый экземпляр класса `PsdImage` из указанного пути к растровому изображению (не PSD‑изображению в пути). Используется для инициализации PSD‑изображения с параметрами по умолчанию — режим цвета — rgb, 4 канала, 8 бит на канал, сжатие — Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Инициализирует новый экземпляр класса `PsdImage` с указанными шириной и высотой. Используется для создания пустого PSD‑изображения. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса `PsdImage` из существующего растрового изображения (не PSD‑изображения) с параметрами конструктора. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса `PsdImage` из указанного пути к растровому изображению (не PSD‑изображению в потоке) с параметрами конструктора. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса `PsdImage` из указанного пути к растровому изображению (не PSD‑изображению в пути) с параметрами конструктора. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Инициализирует новый экземпляр класса `PsdImage` с указанными шириной, высотой, палитрой, режимом цвета, количеством каналов и разрядностью каналов, а также параметрами режима сжатия. Используется для создания пустого PSD‑изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Получает или задает активный слой. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Получает или задает значение для цвета фона. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Получает количество бит на канал. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Получает количество бит на пиксель изображения. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Получает количество каналов PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Получает или задает CMYK‑цветовой профиль для CMYK‑PSD‑изображений. Должен использоваться вместе с RgbColorProfile для корректного преобразования цветов. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Получает или задает режим цвета. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Получает метод сжатия. |
| [Container](../../aspose.psd/image/container/) { get; } | Получает контейнер [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Получает значение формата файла |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Получает или задает глобальный угол. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Получает информацию о глобальной маске слоя. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Получает или задает глобальные ресурсы слоя. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Получает или задает GRAY (монохромный) цветовой профиль для градационных PSD‑изображений. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение цвет фона. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Получает или задает значение, указывающее, содержит ли первый альфа‑канал данные прозрачности для объединённого результата при указании данных слоёв. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Получает высоту изображения. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Получает или задает горизонтальное разрешение этого `PsdImage` в пикселях на дюйм. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Получает непрозрачность этого изображения. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Получает или задает ресурсы PSD‑изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Получает значение, указывающее, является ли PSD‑изображение сплющенным. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Получает или задает слои PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Получает менеджер связанных слоёв. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Получает или задает пользовательский конвертер цветов |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Получает или задает конвертер индексированных цветов. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Получает размер необработанной строки в байтах. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Получает или задает профиль RGB для изображений PSD в формате CMYK. Должен использоваться вместе с CmykColorProfile для корректного преобразования цветов. |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Получает поставщика интеллектуальных объектов. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Получает [`Timeline`](./timeline/) этого `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Получает или задает версию. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Получает или задает вертикальное разрешение в пикселях на дюйм этого `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Получает ширину изображения. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Добавляет слой коррекции черно‑белого. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Добавляет слой коррекции яркости/контраста. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Добавляет слой коррекции микшера каналов с параметрами по умолчанию |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Добавляет слой коррекции цветового баланса. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Добавляет слой коррекции кривых. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Добавляет слой коррекции экспозиции. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Добавляет слой коррекции градиентной карты. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Добавляет слой коррекции тона/насыщенности. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Добавляет слой инверсии. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Добавляет слой. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Добавляет группу слоёв. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Добавляет слой коррекции уровней. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Добавляет слой фотофильтра. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Добавляет слой коррекции постеризации. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Добавляет новый обычный слой. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Добавляет слой коррекции избирательных цветов. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Добавить пустой слой Shape. Без путей. Их следует добавить в слой Shape перед сохранением. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Добавляет новый слой Text. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Добавляет слой коррекции порога. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Добавляет слой коррекции яркости. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Регулировка яркости изображения. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Контрастирование изображения. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Гамма‑коррекция изображения. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Гамма‑коррекция изображения. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Бинаризация изображения с предопределённым порогом |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Бинаризация изображения с порогом Оцу |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Преобразует формат этого изображения в указанный в параметрах. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Обрезка изображения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Обрезать изображение со смещениями. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Выполняет дизеринг текущего изображения. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет дизеринг текущего изображения. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Сводит все слои. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Получает 32‑битный ARGB‑пиксель изображения. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Получает массив пикселей 32‑битного ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Получает дату и время последнего изменения ресурсного изображения. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загружаем чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [`Save`](../../aspose.psd/datastreamsupporter/save/), будет получено PNG‑изображение с 8‑битным цветом на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их во второй параметр метода [`Save`](../../aspose.psd/image/save/). |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Получает пиксель изображения. Предупреждение о производительности: избегайте использования этого метода для перебора всех пикселей изображения, так как это может привести к значительным проблемам с производительностью. Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Получает угол наклона. Этот метод применяется к отсканированным текстовым документам для определения угла наклона при сканировании. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Преобразование изображения в его градации серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Загружает 32‑битные ARGB‑пиксели. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Загружает 64‑битные ARGB‑пиксели. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Загружает пиксели в формате CMYK. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Частично загружает 32‑битные ARGB‑пиксели пакетами. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Частично загружает пиксели пакетами. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Объединяет слои. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от наклона сканирования. Этот метод использует методы [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) и [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от наклона сканирования. Этот метод использует методы [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) и [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Пропорционально изменяет высоту. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Пропорционально изменяет ширину. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Поворачивает изображение вокруг центра. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Поворачивает изображение вокруг центра. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [Save](../../aspose.psd/image/save/)() | Сохраняет данные изображения в базовый поток. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Сохраняет 32‑битные ARGB‑пиксели. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Сохраняет пиксели. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Сохраняет пиксели. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Устанавливает разрешение для этого `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Преобразует растровое изображение в bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | Версия PSD по умолчанию. |

## Примеры

Следующий код демонстрирует возможность вращения изображения на заданный угол.

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

### См. также

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


