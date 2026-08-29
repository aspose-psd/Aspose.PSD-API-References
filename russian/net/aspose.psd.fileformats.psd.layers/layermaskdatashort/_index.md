---
title: "Класс LayerMaskDataShort"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort class. Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в слое PSD‑файла, когда слой имеет только растровую или векторную маску, но не обе сразу. В противном случае используется LayerMaskDataFull. Если слой имеет только растровую маску, ImageData содержит байты данных растровой маски. Если слой имеет только векторную маску, ImageData содержит байты кэшированных растеризованных данных векторной маски. Длина байтов ImageData должна быть равна Width * Height свойств MaskRectangle."
type: docs
weight: 2460
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в слое PSD‑файла, когда слой имеет только растровую или векторную маску, но не обе сразу. В противном случае используется [`LayerMaskDataFull`](../layermaskdatafull/). Если слой имеет только растровую маску, ImageData содержит байты данных растровой маски. Если слой имеет только векторную маску, ImageData содержит байты растеризованных (кэшированных) данных векторной маски. Длина байтов [`ImageData`](../layermaskdata/imagedata/) должна быть равна Width * Height свойств [`MaskRectangle`](../layermaskdata/maskrectangle/).

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Инициализирует новый экземпляр класса `LayerMaskDataShort`. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Получает или задает отступ маски слоя. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Получает или задает позицию правой части маски слоя. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Получает или задает позицию верхней части маски слоя. |

### См. также

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


