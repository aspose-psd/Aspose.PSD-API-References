---
title: Class LayerMaskDataShort
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort сорт. Определяет класс LayerMaskDataShort который содержит информацию о данных маски в файле PSD layer  когда слой имеет только растровую или векторную маску но не обе одновременно. В противном случаеLayerMaskDataFull используется. Если слой имеет только растровую маску ImageData содержит байты данных растровой маски. Если слой имеет только векторную маску ImageData содержит байты растрированных кэшированных данных векторной маски. ImageDataдлина в байтах должна быть равна Ширина  ВысотаMaskRectangle свойства.
type: docs
weight: 2260
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в файле PSD layer , когда слой имеет только растровую или векторную маску, но не обе одновременно. В противном случае[`LayerMaskDataFull`](../layermaskdatafull/) используется. Если слой имеет только растровую маску, ImageData содержит байты данных растровой маски. Если слой имеет только векторную маску, ImageData содержит байты растрированных (кэшированных) данных векторной маски. [`ImageData`](../layermaskdata/imagedata/)длина в байтах должна быть равна Ширина * Высота[`MaskRectangle`](../layermaskdata/maskrectangle/) свойства.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Получает или задает позицию маски нижнего слоя. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Получает размер данных маски слоя-маски. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Получает или задает цвет по умолчанию. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Получает или устанавливает флаги маски слоя. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Получает или задает данные маски слоя (или комбинированной/конечной маски, если есть векторная маска) в файле PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Получает или задает положение маски левого слоя. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Получает или устанавливает маску[`Rectangle`](../../aspose.psd/rectangle/)маски слоя в файле PSD. Он принимает левые, правые, верхние и нижние свойства и создает[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Получает или задает отступ маски слоя. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Получает или задает правильное положение маски слоя. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Получает или задает положение маски верхнего слоя. |

### Смотрите также

* class [LayerMaskData](../layermaskdata/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* сборка [Aspose.PSD](../../)


