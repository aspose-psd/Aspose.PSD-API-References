---
title: Image
second_title: Справочник по Aspose.PSD для .NET API
description: Изображение является базовым классом для всех типов изображений.
type: docs
weight: 4520
url: /ru/net/aspose.psd/image/
---
## Image class

Изображение является базовым классом для всех типов изображений.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Получает или задает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.psd/image/container) { get; } | Получает[`Image`](../image) контейнер. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| abstract [Height](../../aspose.psd/image/height) { get; } | Получает высоту изображения. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные объекта и чтение данных не требуется. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [Size](../../aspose.psd/image/size) { get; } | Получает размер изображения. |
| abstract [Width](../../aspose.psd/image/width) { get; } | Получает ширину изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.psd/image/create)(ImageOptionsBase, int, int) | Создает новый образ, используя указанные параметры создания. |
| static [Load](../../aspose.psd/image/load#load)(Stream) | Загружает новое изображение из указанного потока. |
| static [Load](../../aspose.psd/image/load#load_2)(string) | Загружает новое изображение из указанного файла. |
| static [Load](../../aspose.psd/image/load#load_1)(Stream, LoadOptions) | Загружает новое изображение из указанного потока. |
| static [Load](../../aspose.psd/image/load#load_3)(string, LoadOptions) | Загружает новое изображение из указанного файла. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанном формате файла, представленном переданными параметрами сохранения. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Получает параметры, основанные на настройках исходного файла. Это может быть полезно для сохранения без изменений битовой глубины и других параметров исходного изображения. Например, если мы загружаем черно-белое изображение PNG с 1 битом на пиксель, а затем сохраните его, используя the [`Save`](../datastreamsupporter/save) будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их [`Save`](./save)метод в качестве второго параметра. |
| [Resize](../../aspose.psd/image/resize#resize)(int, int) | Изменяет размер изображения. По умолчаниюLeftTopToLeftTopиспользуется. |
| abstract [Resize](../../aspose.psd/image/resize#resize_1)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| abstract [Resize](../../aspose.psd/image/resize#resize_2)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally)(int) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Изменяет размер высоты пропорционально. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Изменяет размер высоты пропорционально. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally)(int) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Изменяет ширину пропорционально. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Изменяет ширину пропорционально. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.psd/image/save#save)() | Сохраняет данные изображения в базовый поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Сохраняет данные объекта в указанном месте файла. |
| [Save](../../aspose.psd/image/save#save_2)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.psd/image/save#save_5)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| abstract [SetPalette](../../aspose.psd/image/setpalette)(IColorPalette, bool) | Задает палитру изображения. |
| static [CanLoad](../../aspose.psd/image/canload#canload)(Stream) | Определяет, можно ли загрузить изображение из указанного потока. |
| static [CanLoad](../../aspose.psd/image/canload#canload_2)(string) | Определяет, можно ли загрузить изображение из указанного пути к файлу. |
| static [CanLoad](../../aspose.psd/image/canload#canload_1)(Stream, LoadOptions) | Определяет, может ли изображение быть загружено из указанного потока и, возможно, с использованием указанного*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload#canload_3)(string, LoadOptions) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat)(Stream) | Получает формат файла. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat_1)(string) | Получает формат файла. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Получает прямоугольник, соответствующий текущему изображению. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Получает прямоугольник, соответствующий текущему изображению. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight)(int, int, int) | Получает пропорциональную высоту. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth)(int, int, int) | Получает пропорциональную ширину. |

### Примеры

В этом примере создается новый файл изображения в некотором месте на диске, как указано в свойстве Source экземпляра PsdOptions. Несколько свойств экземпляра PsdOptions задаются перед созданием фактического образа. Особенно свойство Source, которое в данном случае относится к фактическому местоположению на диске.

```csharp
[C#]

//Создаем экземпляр PsdOptions и устанавливаем его различные свойства
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра PsdOptions
//Второй логический параметр определяет, является ли создаваемый файл временным или нет
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Создаем экземпляр Image и инициализируем его экземпляром PsdOptions, вызвав метод Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // делаем некоторую обработку изображения

    // сохранить все изменения
    image.Save();
}
```

### Смотрите также

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
