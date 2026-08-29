---
title: "Класс AiImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Ai.AiImage класс. Изображение Adobe Illustrator AI"
type: docs
weight: 1270
url: /ru/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

Изображение Adobe Illustrator (AI).

```csharp
public sealed class AiImage : Image
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AiImage](aiimage/)() | Инициализирует новый экземпляр класса `AiImage`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Получает или задает индекс активной страницы. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Получает или задает значение для цвета фона. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Получает количество бит на пиксель изображения. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.psd/image/container/) { get; } | Получает контейнер [`Image`](../../aspose.psd/image/). |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Получает раздел данных. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Получает значение формата файла. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Получает раздел завершения. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение цвет фона. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Получает заголовок. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Получает высоту изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Получает разделы слоёв. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | Количество страниц. Для изображений старого формата AI всегда равно 0. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Получает раздел настройки. |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Получает версию формата Adobe Illustrator. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Получает ширину изображения. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | Получает метаданные XMP. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Добавляет раздел слоя AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загружаем чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [`Save`](../../aspose.psd/datastreamsupporter/save/), будет получено PNG‑изображение с 8‑битным цветом на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их во второй параметр метода [`Save`](../../aspose.psd/image/save/). |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Пропорционально изменяет ширину. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [Save](../../aspose.psd/image/save/)() | Сохраняет данные изображения в базовый поток. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |

## Примеры

В следующем примере показано, как можно экспортировать файлы Adobe Illustrator в формат PDF с помощью Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

В следующем примере показано, как экспортировать файл AI в форматы PSD и PNG с помощью Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

В следующем примере демонстрируется поддержка экспорта формата Ai в форматы PSD, PNG, JPG, GIF и TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### См. также

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


