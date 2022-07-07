---
title: SectionDividerLayer
second_title: Справочник по Aspose.PSD для .NET API
description: Разделительный слой для обозначения границ папки группы слоев.
type: docs
weight: 3300
url: /ru/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/
---
## SectionDividerLayer class

Разделительный слой для обозначения границ папки (группы слоев).

```csharp
public class SectionDividerLayer : Layer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions) { get; } | Получает параметры наложения. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey) { get; set; } | Получает или задает ключ режима наложения. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature) { get; } | Получает сигнатуру режима наложения. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom) { get; set; } | Получает или задает положение нижнего слоя. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation) { get; set; } | Получает или задает информацию о канале. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount) { get; } | Получает количество каналов слоя. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping) { get; set; } | Получает или задает отсечение слоя. 0 = базовый, 1 = не базовый. |
| [Container](../../aspose.psd/image/container) { get; } | Получает контейнер[`Image`](../../aspose.psd/image). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname) { get; set; } | Получает или задает отображаемое имя слоя. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength) { get; } | Получает длину дополнительной информации слоя в байтах. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Получает значение формата файла |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler) { get; set; } | Получает или задает заполнитель слоя. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity) { get; set; } | Получает или задает непрозрачность заливки. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags) { get; set; } | Получает или устанавливает флаги слоя. бит 0 = прозрачность защищена; бит 1 = видимый; бит 2 = устарело; бит 3 = 1 для Photoshop 5.0 и более поздних версий сообщает, содержит ли бит 4 полезную информацию; бит 4 = пиксельные данные, не относящиеся к внешнему виду документа. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha) { get; } | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height) { get; } | Получает высоту изображения. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.psd/rasterimage). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible) { get; set; } | Получает или задает значение, указывающее, виден ли слой |
| override [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup) { get; } | Получает значение, указывающее, виден ли этот экземпляр в группе (если слой не входит в группу, это означает корневую группу). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata) { get; set; } | Получает или задает данные диапазонов смешивания слоев. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime) { get; set; } | Получает или задает дату и время создания слоя. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock) { get; set; } | Получает или устанавливает блокировку слоя. Обратите внимание, что если флаг LayerFlags.TransparencyProtected установлен, он будет перезаписан флагом блокировки слоя. Чтобы вернуть флаг LayerFlags.TransparencyProtected, необходимо применить параметр слоя layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata) { get; set; } | Получает или задает данные маски слоя. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions) { get; } | Получает параметры слоя. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left) { get; set; } | Получает или задает положение левого слоя. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length) { get; } | Получает общую длину слоя в байтах. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name) { get; set; } | Получает или задает имя слоя. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity) { get; set; } | Получает или задает непрозрачность слоя. 0 = прозрачный, 255 = непрозрачный. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения предварительно умножаться. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Получает или задает пользовательский преобразователь цвета |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Получает или задает резервный индекс для использования, когда индекс палитры выходит за пределы |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Получает или задает преобразователь индексированных цветов |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Получает необработанный размер строки в байтах. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources) { get; set; } | Получает или задает ресурсы слоя. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right) { get; set; } | Получает или задает правильное положение слоя. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight) { get; set; } | Получает или устанавливает выделение цветом декоративного листа в списке слоев |
| [Size](../../aspose.psd/image/size) { get; } | Получает размер изображения. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top) { get; set; } | Получает или задает позицию верхнего слоя. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда доступна загрузка необработанных данных. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution) { get; set; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого[`RasterImage`](../../aspose.psd/rasterimage). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width) { get; } | Получает ширину изображения. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask)(LayerMaskData) | Добавляет маску к текущему слою. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness)(int) | Настройка яркости изображения. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast)(float) | Контраст изображения |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float) | Гамма-коррекция изображения. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma)(float, float, float) | Гамма-коррекция изображения. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley)(double, int) | Бинаризация изображения с использованием алгоритма адаптивной пороговой обработки Брэдли с использованием интегральной пороговой обработки изображения |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed)(byte) | Бинаризация изображения с заданным порогом |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu)() | Бинаризация изображения с порогом Оцу |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| override [Crop](../../aspose.psd/rastercachedimage/crop)(Rectangle) | Обрезка изображения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Обрезать изображение со сдвигами. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Выполняет сглаживание текущего изображения. |
| override [Dither](../../aspose.psd/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Выполняет сглаживание текущего изображения. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage)(Point, RasterImage) | Рисует изображение на слое. |
| virtual [Filter](../../aspose.psd/rasterimage/filter)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Получает 32-битный пиксель изображения ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Получает массив 32-битных пикселей ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с помощью частичной загрузки пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичной загрузки пикселей. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode)() | Возвращает хэш-код для этого экземпляра. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Получает дату и время последнего изменения образа ресурса. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../../aspose.psd/datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../../aspose.psd/image/save)метод в качестве второго параметра. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Получает пиксель изображения. |
| [GetRelatedLayerGroup](../../aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup)() | Получает[`LayerGroup`](../layergroup)связанный с этим[`SectionDividerLayer`](../sectiondividerlayer)instance. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Получает угол наклона. Этот метод применим к отсканированным текстовым документам, для определения угла перекоса при сканировании. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale)() | Преобразование изображения в его представление в градациях серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Загружает 32-битные пиксели ARGB. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Загружает 64-битные пиксели ARGB. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Загружает 32-битные ARGB-пиксели частично пачками. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Загружает пиксели частично пачками. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| virtual [MergeLayerTo](../../aspose.psd.fileformats.psd.layers/layer/mergelayerto)(Layer) | Слияние слоя с указанным |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)и[`Rotate`](../../aspose.psd/rasterimage/rotate)методы. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам, чтобы избавиться от перекоса сканирования. Этот метод использует[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle)и[`Rotate`](../../aspose.psd/rasterimage/rotate)методы. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения гладких краев. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа-канала для сохранения гладких краев. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание:если вы используете его на изображениях без прозрачности, все цвета будут заменены одним. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа-канала для сохранения гладких краев. Примечание:если вы используете его на изображениях без прозрачности, все цвета будут заменены одним. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Изменяет размер изображения. По умолчанию используетсяLeftTopToLeftTop. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | Пропорционально изменяет размер высоты. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | Пропорционально изменяет ширину. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate)(float) | Повернуть изображение вокруг центра. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate)(float, bool, Color) | Повернуть изображение вокруг центра. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.psd/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Сохраняет данные объекта в указанном месте файла. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Сохраняет 32-битные пиксели ARGB. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Сохраняет пиксели. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Устанавливает 32-битный пиксель изображения ARGB для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Устанавливает разрешение для этого[`RasterImage`](../../aspose.psd/rasterimage). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy)() | Создает поверхностную копию текущего слоя. Пожалуйста, &lt;см. href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /&gt; для объяснения. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Преобразует растровое изображение в растровое. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

### Примеры

Следующий код демонстрирует слои SectionDividerLayer и как получить связанную с ним LayerGroup.

```csharp
[C#]

// Следующий код демонстрирует слои SectionDividerLayer и как получить связанную с ним LayerGroup.

// Иерархия слоев
// [0]: '</Группа слоев>' SectionDividerLayer для группы 1
// [1]: 'Слой 1' Обычный слой
// [2]: '</Группа слоев>' SectionDividerLayer для группы 2
// [3]: '</Группа слоев>' SectionDividerLayer для группы 3
// [4]: 'Группа 3' Групповой слой
// [5]: 'Группа 2' Групповой слой
// [6]: 'Группа 1' Групповой Слой

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Создание иерархии слоев
    // Добавляем LayerGroup «Группа 1»
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Добавляем обычный слой
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Добавляем LayerGroup «Группа 2»
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Добавляем LayerGroup «Группа 3»
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Получает SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // используя метод SectionDividerLayer.GetRelatedLayerGroup(), получает связанный экземпляр LayerGroup.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // та самая LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // та самая LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // та самая LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // «Группа 1» содержит 5 слоев
}
```

### Смотрите также

* class [Layer](../layer)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
