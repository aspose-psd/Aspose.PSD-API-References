---
title: "Класс LayerMaskDataFull"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое файла PSD, когда слой имеет как растровую, так и векторную маски. В противном случае используется LayerMaskDataShort. ImageData содержит комбинированные данные растровой маски и растровой векторной маски. Длина байтов ImageData должна быть равна MaskRectangle.Width  MaskRectangle.Height свойств"
type: docs
weight: 2450
url: /ru/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое файла PSD, когда слой имеет как растровую, так и векторную маски. В противном случае используется [`LayerMaskDataShort`](../layermaskdatashort/). ImageData содержит комбинированные данные растровой маски и растровой векторной маски. Длина байтов ImageData должна быть равна MaskRectangle.Width * MaskRectangle.Height свойств.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Получает или задает цвет фона. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Получает или задает позицию нижней части маски слоя. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Получает размер данных маски слоя. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Получает или задает цвет по умолчанию. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Получает или задает позицию нижней части охватывающей растровой маски в слое изображения PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Получает или задает позицию левой части охватывающей растровой маски в слое файла PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Получает или задает позицию правой части охватывающей растровой маски в слое файла PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Получает или задает позицию верхней части охватывающей растровой маски в слое изображения PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Получает или задает флаги маски слоя. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Получает или задает данные маски слоя (или комбинированную / окончательную маску, если есть векторная маска) в файле PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Получает или задает позицию левой части маски слоя. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Получает или задает маску [`Rectangle`](../../aspose.psd/rectangle/) маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает [`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Получает или задает флаги маски слоя, используемые для пользовательской / растровой маски. Для векторной маски используется свойство Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Получает или задает позицию правой части маски слоя. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Получает или задает позицию верхней части маски слоя. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. (В свойстве MaskData находится растровая векторная маска). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Получает или задает прямоугольник пользовательской маски (охватывающий) в слое изображения PSD.. |

### См. также

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


