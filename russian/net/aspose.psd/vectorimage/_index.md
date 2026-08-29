---
title: "Класс VectorImage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.VectorImage. Векторное изображение является базовым классом для всех типов векторных изображений"
type: docs
weight: 6220
url: /ru/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

Векторное изображение является базовым классом для всех типов векторных изображений.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
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
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Получает или задает значение, указывающее, имеет ли изображение цвет фона. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Получает высоту изображения. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Получает высоту объекта в дюймах. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Получает или задает монитор прерываний. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| [Size](../../aspose.psd/image/size/) { get; } | Получает размер изображения. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Получает размер объекта в дюймах. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Получает значение, указывающее, используется ли палитра изображения. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Получает ширину изображения. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Получает ширину объекта в дюймах. |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Кэширует данные и гарантирует, что дополнительная загрузка данных из базового [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) не будет выполнена. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Определяет, может ли изображение быть сохранено в указанный файловый формат, представленный переданными параметрами сохранения. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Получает параметры по умолчанию. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод [`Save`](../datastreamsupporter/save/), будет получено выходное PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [`Save`](../image/save/) в качестве второго параметра. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Изменяет размер изображения. Используется значение по умолчанию NearestNeighbourResample. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Изменяет размер изображения. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Изменяет размер изображения. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет высоту. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Пропорционально изменяет высоту. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Пропорционально изменяет ширину. Используется значение по умолчанию NearestNeighbourResample. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Пропорционально изменяет ширину. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Пропорционально изменяет ширину. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| [Save](../../aspose.psd/image/save/)() | Сохраняет данные изображения в базовый поток. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Сохраняет данные объекта в указанный поток. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Сохраняет данные объекта в указанное расположение файла. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Сохраняет данные объекта в указанное расположение файла. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Устанавливает палитру изображения. |

### См. также

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


