---
title: Class LayerMaskData
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData сорт. Определяет базовый класс LayerMaskData который содержит информацию о данных маски слоя в файле PSD. Может помочь программно модифицировать файлы Adobe Photoshop и автоматизировать редактирование формата PSD. Если слой имеет только растровую маску ImageData содержит растр байты данных маски. Если слой имеет только векторную маску ImageData содержит байты растеризованных кэшированных данных векторной маски. Если слой имеет как слой так и векторную маску ImageData содержит растровую маску и растеризованную векторную маску вместе. ImageDataдлина в байтах должна быть равна Ширина  ВысотаMaskRectangle properties. Обратите внимание что простого удаления/добавления/обновления LayerMaskData недостаточно для корректного сохранения  так как каналы не обновляются хотя это может обеспечить правильный рендеринг. AddLayerMask для этого следует использовать метод.
type: docs
weight: 2240
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD. Может помочь программно модифицировать файлы Adobe® Photoshop® и автоматизировать редактирование формата PSD. Если слой имеет только растровую маску, ImageData содержит растр байты данных маски. Если слой имеет только векторную маску, ImageData содержит байты растеризованных (кэшированных) данных векторной маски. Если слой имеет как слой, так и векторную маску, ImageData содержит растровую маску и растеризованную векторную маску вместе. [`ImageData`](./imagedata/)длина в байтах должна быть равна Ширина * Высота[`MaskRectangle`](./maskrectangle/) properties. Обратите внимание, что простого удаления/добавления/обновления LayerMaskData недостаточно для корректного сохранения , так как каналы не обновляются; хотя это может обеспечить правильный рендеринг. [`AddLayerMask`](../layer/addlayermask/) для этого следует использовать метод.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Получает или задает правильное положение маски слоя. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Получает или задает положение маски верхнего слоя. |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* сборка [Aspose.PSD](../../)


