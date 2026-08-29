---
title: "Класс RasterCachedImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.RasterCachedImage. Представляет растровое изображение, поддерживающее операции растровой графики. Это изображение кэширует данные пикселей при необходимости"
type: docs
weight: 5810
url: /ru/net/aspose.psd/rastercachedimage/
---
{{< psd/tize >}}
## RasterCachedImage class

Представляет растровое изображение, поддерживающее операции растровой графики. Это изображение кэширует данные пикселей по требованию.

```csharp
public abstract class RasterCachedImage : RasterImage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Получает или задает значение для цвета фона. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Получает количество бит на пиксель изображения. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.psd/image/container/) { get; } | Получает контейнер [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Получает значение формата файла |
| virtual [HasAlpha](../../aspose.psd/rasterimage/hasalpha/) { get; } | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение цвет фона. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Получает высоту изображения. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [`RasterImage`](../rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные изображения. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умножены. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Получает или задает пользовательский конвертер цветов |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Получает формат необработанных данных. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Получает текущие настройки необработанных данных. Обратите внимание, что при использовании этих настроек данные загружаются без преобразования. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы. |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Получает или задает конвертер индексированных цветов. |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Получает размер необработанной строки в байтах. |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Получает прозрачный цвет изображения. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [`RasterImage`](../rasterimage/). |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Получает ширину изображения. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Регулировка яркости изображения. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Контрастирование изображения. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma)(float) | Гамма‑коррекция изображения. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/#adjustgamma_1)(float, float, float) | Гамма‑коррекция изображения. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley)(double) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/#binarizebradley_1)(double, int) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Бинаризация изображения с предопределённым порогом |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Бинаризация изображения с порогом Оцу |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/#crop)(Rectangle) | Обрезка изображения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Обрезать изображение со смещениями. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Выполняет дизеринг текущего изображения. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет дизеринг текущего изображения. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Получает 32‑битный ARGB‑пиксель изображения. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Получает массив пикселей 32‑битного ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Получает дату и время последнего изменения ресурсного изображения. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод [`Save`](../datastreamsupporter/save/), будет получено выходное PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [`Save`](../image/save/) в качестве второго параметра. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Получает пиксель изображения. Предупреждение о производительности: избегайте использования этого метода для перебора всех пикселей изображения, так как это может привести к значительным проблемам с производительностью. Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Получает угол наклона. Этот метод применяется к отсканированным текстовым документам для определения угла наклона при сканировании. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Преобразование изображения в его градации серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Загружает 32‑битные ARGB‑пиксели. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Загружает 64‑битные ARGB‑пиксели. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Загружает пиксели в формате CMYK. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`LoadCmyk32Pixels`](../rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Частично загружает 32‑битные ARGB‑пиксели пакетами. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Частично загружает пиксели пакетами. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования. Этот метод использует методы [`GetSkewAngle`](../rasterimage/getskewangle/) и [`Rotate`](../rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования. Этот метод использует методы [`GetSkewAngle`](../rasterimage/getskewangle/) и [`Rotate`](../rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Пропорционально изменяет ширину. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Поворачивает изображение вокруг центра. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/#rotate_1)(float, bool, Color) | Поворачивает изображение вокруг центра. |
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
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Сохраняет пиксели. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`SaveCmyk32Pixels`](../rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Устанавливает разрешение для этого [`RasterImage`](../rasterimage/). |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Преобразует растровое изображение в bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

## Примеры

Следующий код демонстрирует возможность обрезать изображение по заданному прямоугольнику.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Сохранить psd
    image.Save(exportPath, new PsdOptions());

    // Сохранить png
    image.Save(exportPathPng, new PngOptions());
}
```

### См. также

* class [RasterImage](../rasterimage/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


