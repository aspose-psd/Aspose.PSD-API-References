---
title: "Класс RasterImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.RasterImage. Представляет растровое изображение, поддерживающее операции растровой графики"
type: docs
weight: 5820
url: /ru/net/aspose.psd/rasterimage/
---
{{< psd/tize >}}
## RasterImage class

Представляет растровое изображение, поддерживающее операции растровой графики.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
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
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого `RasterImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Получает непрозрачность этого изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
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
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Получает или задает вертикальное разрешение в пикселях на дюйм для этого `RasterImage`. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Получает ширину изображения. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Получает или задает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.psd/rasterimage/adjustbrightness/)(int) | Регулировка яркости изображения. |
| virtual [AdjustContrast](../../aspose.psd/rasterimage/adjustcontrast/)(float) | Контрастирование изображения. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma)(float) | Гамма‑коррекция изображения. |
| virtual [AdjustGamma](../../aspose.psd/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | Гамма‑коррекция изображения. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley)(double) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| virtual [BinarizeBradley](../../aspose.psd/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении. |
| virtual [BinarizeFixed](../../aspose.psd/rasterimage/binarizefixed/)(byte) | Бинаризация изображения с предопределённым порогом |
| virtual [BinarizeOtsu](../../aspose.psd/rasterimage/binarizeotsu/)() | Бинаризация изображения с порогом Оцу |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop)(Rectangle) | Обрезает указанный прямоугольник. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/#crop_1)(int, int, int, int) | Обрезать изображение со смещениями. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| [Dither](../../aspose.psd/rasterimage/dither/#dither)(DitheringMethod, int) | Выполняет дизеринг текущего изображения. |
| abstract [Dither](../../aspose.psd/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Выполняет дизеринг текущего изображения. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Фильтрует указанный прямоугольник. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Получает 32‑битный ARGB‑пиксель изображения. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Получает массив пикселей 32‑битного ARGB по умолчанию. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | Получает массив необработанных данных по умолчанию. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Получает дату и время последнего изменения ресурсного изображения. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод [`Save`](../datastreamsupporter/save/), будет получено выходное PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [`Save`](../image/save/) в качестве второго параметра. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Получает пиксель изображения. Предупреждение о производительности: избегайте использования этого метода для перебора всех пикселей изображения, так как это может привести к значительным проблемам с производительностью. Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Получает угол наклона. Этот метод применяется к отсканированным текстовым документам для определения угла наклона при сканировании. |
| virtual [Grayscale](../../aspose.psd/rasterimage/grayscale/)() | Преобразование изображения в его градации серого |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Загружает 32‑битные ARGB‑пиксели. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Загружает 64‑битные ARGB‑пиксели. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Загружает пиксели в формате CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Загружает пиксели в формате CMYK. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`LoadCmyk32Pixels`](./loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Частично загружает 32‑битные ARGB‑пиксели пакетами. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Частично загружает пиксели пакетами. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Загружает пиксели. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Загружает необработанные данные. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle)() | Нормализует угол. Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования. Метод использует методы [`GetSkewAngle`](./getskewangle/) и [`Rotate`](./rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | Нормализует угол. Этот метод применим к отсканированным текстовым документам для устранения наклона сканирования. Метод использует методы [`GetSkewAngle`](./getskewangle/) и [`Rotate`](./rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Считывает всю строку сканирования по указанному индексу строки сканирования. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа‑канала, чтобы сохранить плавные края. Примечание: если использовать его для изображений без прозрачности, все цвета будут заменены одним цветом. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения с расширенными параметрами. |
| override [Resize](../../aspose.psd/rasterimage/resize/#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Пропорционально изменяет ширину. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate)(float) | Поворачивает изображение вокруг центра. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/#rotate_1)(float, bool, Color) | Поворачивает изображение вокруг центра. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [Save](../../aspose.psd/image/save/)() | Сохраняет данные изображения в базовый поток. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| override [Save](../../aspose.psd/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Сохраняет 32‑битные ARGB‑пиксели. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Сохраняет пиксели. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Сохраняет пиксели. Этот метод устарел. Пожалуйста, используйте более эффективный метод [`SaveCmyk32Pixels`](./savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Сохраняет пиксели. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Сохраняет необработанные данные. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Устанавливает пиксель изображения для указанной позиции. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Устанавливает разрешение для этого `RasterImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Преобразует растровое изображение в bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Записывает всю строку сканирования в указанный индекс строки сканирования. |

## Примеры

В этом примере показано, как загрузить информацию о пикселях в массив типа Color, изменить массив и установить его обратно в изображение. Для выполнения этих операций пример создаёт новый файл Image (в формате PSD) с использованием объекта MemoryStream.

```csharp
[C#]

//Создайте экземпляр MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Создайте экземпляр PsdOptions и задайте его различные свойства, включая свойство Source
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Создайте экземпляр Image
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Получите пиксели изображения, указав область как границу изображения
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Пройдите по Array и установите цвет альтернативного индексированного пикселя
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Установите цвет индексированного пикселя в желтый
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Установите цвет индексированного пикселя в синий
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Примените изменения пикселей к изображению
        image.SavePixels(image.Bounds, pixels);

        // Сохраните все изменения.
        image.Save();
    }

    //Запишите MemoryStream в файл
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### См. также

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


