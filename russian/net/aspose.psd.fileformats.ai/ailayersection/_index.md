---
title: AiLayerSection
second_title: Справочник по Aspose.PSD для .NET API
description: Раздел слоя формата AI
type: docs
weight: 1270
url: /ru/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Раздел слоя формата AI

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue) { get; set; } | Получает или задает компонент синего цвета. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber) { get; set; } | Получает или задает номер цвета. -1 — это пользовательское значение цвета из свойств Red, Green, Blue. Указывает настройку цвета слоя. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue) { get; set; } | Получает или задает значение затемнения в процентах. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое, до указанного процента. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green) { get; set; } | Получает или задает компонент зеленого цвета. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed) { get; set; } | Получает или задает значение, указывающее, затенен ли этот слой. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked) { get; set; } | Получает или задает значение, указывающее, заблокирован ли этот слой. Запрещает внесение изменений в элемент. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview) { get; set; } | Получает или задает значение, указывающее, является ли этот слой предварительным. Отображает иллюстрацию, содержащуюся в слое, в цвете, а не в виде контуров. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted) { get; set; } | Получает или задает значение, указывающее, печатается ли этот слой. Делает иллюстрацию, содержащуюся в слое, печатаемой, если true. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown) { get; set; } | Получает или задает значение, указывающее, отображается ли этот слой. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate) { get; set; } | Получает или задает значение, указывающее, является ли этот слой слоем шаблона. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name) { get; set; } | Получает или задает имя слоя. Задает имя элемента, которое отображается на панели «Слои». |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages) { get; } | Получает растровые изображения. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red) { get; set; } | Получает или задает компонент красного цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage)(AiRasterImageSection) | Добавляет растровое изображение. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata)() | Получает строковые данные. |

### Примеры

В следующем коде показано, как загрузить настройки растровых изображений в файлы формата AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Смотрите также

* class [AiDataSection](../aidatasection)
* пространство имен [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
