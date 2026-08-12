---
title: "Класс MixrResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. Класс MixrResource. Ресурс слоя коррекции микшера каналов"
type: docs
weight: 3160
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Класс MixrResource. Ресурс слоя коррекции Channel Mixer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Инициализирует новый экземпляр класса `MixrResource`. Спецификация формата PSD содержит следующее описание: 2 Версия (= 1) 2 Монохром 20 Цвет RGB или CMYK плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `MixrResource`. Спецификация формата PSD содержит следующее описание: 2 Версия (= 1) 2 Монохром 20 Цвет RGB или CMYK плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Получает или задает значение, указывающее, является ли этот `MixrResource` монохромным. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Получает или задает версию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Получает необработанные данные информации канала |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Задает информацию канала. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


