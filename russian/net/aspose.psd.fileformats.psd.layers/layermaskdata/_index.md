---
title: "Класс LayerMaskData"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD. Он может помочь программно изменять файлы Adobe Photoshop и автоматизировать редактирование формата PSD. Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски. Если у слоя есть только векторная маска, ImageData содержит байты кэшированных данных растровой векторной маски. Если у слоя есть как растровая, так и векторная маски, ImageData содержит комбинированные данные растровой маски и растровой векторной маски. Длина байтов ImageData должна быть равна Width  Height свойств MaskRectangle. Обратите внимание, что простое удаление / добавление / обновление LayerMaskData недостаточно для корректного сохранения, поскольку каналы не обновляются, хотя это может обеспечить правильный рендеринг. Для этого следует использовать метод AddLayerMask."
type: docs
weight: 2440
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD. Он может помочь программно изменять файлы Adobe® Photoshop® и автоматизировать редактирование формата PSD. Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски. Если у слоя есть только векторная маска, ImageData содержит байты растровых (кэшированных) данных векторной маски. Если у слоя есть как растровая, так и векторная маски, ImageData содержит комбинированные данные растровой маски и растровой векторной маски. Длина байтов [`ImageData`](./imagedata/) должна быть равна Width * Height свойств [`MaskRectangle`](./maskrectangle/). Обратите внимание, что простое удаление / добавление / обновление LayerMaskData недостаточно для корректного сохранения, поскольку каналы не обновляются; хотя это может обеспечить правильный рендеринг. Для этого следует использовать метод [`AddLayerMask`](../layer/addlayermask/).

```csharp
public abstract class LayerMaskData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Получает или задает позицию нижней части маски слоя. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Получает размер данных маски слоя. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Получает или задает цвет по умолчанию. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Получает или задает флаги маски слоя. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Получает или задает данные маски слоя (или комбинированную / окончательную маску, если есть векторная маска) в файле PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Получает или задает позицию левой части маски слоя. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Получает или задает маску [`Rectangle`](../../aspose.psd/rectangle/) маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает [`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Получает или задает позицию правой части маски слоя. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Получает или задает позицию верхней части маски слоя. |

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


