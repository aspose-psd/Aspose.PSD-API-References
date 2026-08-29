---
title: "Класс Image"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Image. Изображение является базовым классом для всех типов изображений."
type: docs
weight: 5060
url: /ru/net/aspose.psd/image/
---
{{< psd/tize >}}
## Image class

Изображение является базовым классом для всех типов изображений.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически корректировать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Получает или задает значение для цвета фона. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Получает количество бит на пиксель изображения. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.psd/image/container/) { get; } | Получает контейнер `Image`. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение цвет фона. |
| abstract [Height](../../aspose.psd/image/height/) { get; } | Получает высоту изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| abstract [Width](../../aspose.psd/image/width/) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.psd/image/create/)(ImageOptionsBase, int, int) | Создаёт новое изображение, используя указанные параметры создания. |
| static [Load](../../aspose.psd/image/load/#load)(Stream) | Загружает новое изображение из указанного потока. |
| static [Load](../../aspose.psd/image/load/#load_2)(string) | Загружает новое изображение из указанного файла. |
| static [Load](../../aspose.psd/image/load/#load_1)(Stream, LoadOptions) | Загружает новое изображение из указанного потока. |
| static [Load](../../aspose.psd/image/load/#load_3)(string, LoadOptions) | Загружает новое изображение из указанного файла. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его с помощью метода [`Save`](../datastreamsupporter/save/), будет получено PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [`Save`](./save/) в качестве второго параметра. |
| [Resize](../../aspose.psd/image/resize/#resize)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| abstract [Resize](../../aspose.psd/image/resize/#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally)(int) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Пропорционально изменяет ширину. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [Save](../../aspose.psd/image/save/#save)() | Сохраняет данные изображения в базовый поток. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.psd/image/save/#save_2)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/image/save/#save_5)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |
| static [CanLoad](../../aspose.psd/image/canload/#canload)(Stream) | Определяет, может ли изображение быть загружено из указанного потока. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_2)(string) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_1)(Stream, LoadOptions) | Определяет, может ли изображение быть загружено из указанного потока и, при желании, с использованием указанных *loadOptions*. |
| static [CanLoad](../../aspose.psd/image/canload/#canload_3)(string, LoadOptions) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при желании, с использованием указанных параметров открытия. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat)(Stream) | Получает формат файла. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat/#getfileformat_1)(string) | Получает формат файла. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | Получает прямоугольник, который вписывается в текущее изображение. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | Получает прямоугольник, который вписывается в текущее изображение. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight/)(int, int, int) | Получает пропорциональную высоту. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth/)(int, int, int) | Получает пропорциональную ширину. |

## Примеры

В этом примере создаётся новый файл Image в указанном месте диска, определённом свойством Source экземпляра PsdOptions. Перед созданием фактического изображения задаются несколько свойств экземпляра PsdOptions, особенно свойство Source, которое в данном случае указывает реальное расположение на диске.

```csharp
[C#]

//Создайте экземпляр PsdOptions и задайте его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра PsdOptions
//Второй логический параметр определяет, является ли создаваемый файл временным
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Создайте экземпляр Image и инициализируйте его экземпляром PsdOptions, вызвав метод Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //выполнить некоторую обработку изображения

    // сохранить все изменения
    image.Save();
}
```

### См. также

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


