---
title: "Класс PhflResourceVersion3"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 класс. Класс PhflResource. Ресурс слоя коррекции экспозиции 2 Версия   3  или   2  12 4 байта каждый для цвета XYZТолько в версии 3 10 2 байта цветового пространства, за которым следуют 4  2 байта цветового компонентаТолько в версии 2 4 Плотность 1 Сохранить яркость"
type: docs
weight: 3260
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

Класс PhflResource. Ресурс слоя коррекции Exposure. Версия 2 ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следуют 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость

```csharp
public class PhflResourceVersion3 : PhflResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | Инициализирует новый экземпляр класса `PhflResourceVersion3`. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `PhflResourceVersion3`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | Получает цветовое пространство. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | Получает или задаёт цвет X. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Получает или задаёт цвет Y. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Получает или задаёт цвет Z. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Получает или задает плотность. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Получает или задает значение, указывающее, следует ли [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | Получает версию. По умолчанию 2 или 3. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | Получает цвет. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | Задает цвет RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


