---
title: VectorImage
second_title: Справочник по Aspose.PSD для .NET API
description: Векторное изображение является базовым классом для всех типов векторных изображений.
type: docs
weight: 5600
url: /ru/net/aspose.psd/vectorimage/
---
## VectorImage class

Векторное изображение является базовым классом для всех типов векторных изображений.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Получает или задает значение, указывающее, следует ли автоматически настраивать палитру. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Получает или задает значение цвета фона. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | Получает количество бит изображения на пиксель. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Получает границы изображения. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Получает или устанавливает подсказку о размере буфера, которая определяет максимально допустимый размер для всех внутренних буферов. |
| [Container](../../aspose.psd/image/container) { get; } | Получает контейнер[`Image`](../image). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Получает поток данных объекта. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Получает значение формата файла |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение фоновый цвет. |
| override [Height](../../aspose.psd/vectorimage/height) { get; } | Получает высоту изображения. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf) { get; } | Получает высоту объекта в дюймах. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Получает или устанавливает монитор прерываний. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | Получает значение, указывающее, кэшируются ли в данный момент данные объекта и чтение данных не требуется. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [Size](../../aspose.psd/image/size) { get; } | Получает размер изображения. |
| [SizeF](../../aspose.psd/vectorimage/sizef) { get; } | Получает размер объекта в дюймах. |
| override [Width](../../aspose.psd/vectorimage/width) { get; } | Получает ширину изображения. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf) { get; } | Получает ширину объекта в дюймах. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | Кэширует данные и гарантирует, что дополнительная загрузка данных не будет выполняться из базового[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Определяет, можно ли сохранить изображение в указанный формат файла, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Получает параметры по умолчанию. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Получает параметры на основе исходных настроек файла. Это может быть полезно для сохранения битовой глубины и других параметров исходного изображения без изменений. Например, если мы загрузим черно-белое изображение PNG с 1 битом на пиксель, а затем сохраним его с помощью [`Save`](../datastreamsupporter/save)будет создано выходное изображение PNG с 8 битами на пиксель. Чтобы избежать этого и сохранить изображение PNG с 1 битом на пиксель, используйте этот метод, чтобы получить соответствующие параметры сохранения и передать их в[`Save`](../image/save)метод в качестве второго параметра. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Изменяет размер изображения. По умолчанию используетсяLeftTopToLeftTop. |
| abstract [Resize](../../aspose.psd/image/resize)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| abstract [Resize](../../aspose.psd/image/resize)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ImageResizeSettings) | Пропорционально изменяет размер высоты. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int, ResizeType) | Пропорционально изменяет размер высоты. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int, ResizeType) | Пропорционально изменяет ширину. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | Вращает, переворачивает или поворачивает и переворачивает изображение. |
| [Save](../../aspose.psd/image/save)() | Сохраняет данные изображения в основной поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Сохраняет данные объекта в указанном месте файла. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Сохраняет данные объекта в указанном месте файла. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном формате файла в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанном месте файла в указанном формате файла в соответствии с параметрами сохранения. |
| abstract [SetPalette](../../aspose.psd/image/setpalette)(IColorPalette, bool) | Устанавливает палитру изображения. |

### Смотрите также

* class [Image](../image)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
