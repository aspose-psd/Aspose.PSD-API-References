---
title: "Класс BritResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource класс. Класс BritResource. Ресурс слоя регулировки яркости/контрастности."
type: docs
weight: 2600
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Класс BritResource. Ресурс слоя коррекции яркости/контраста.

```csharp
public class BritResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BritResource](britresource/#constructor)() | Инициализирует новый экземпляр класса `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `BritResource`. Спецификация формата PSD содержит следующее описание: 2 Brightness 2 Contrast 2 Mean value for brightness and contrast 1 только Lab color. Он не используется в современных PSD (CS5 и выше), где присутствует CgEd. CgEd хранит информационные свойства. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Инициализирует новый экземпляр класса `BritResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Получает или задает яркость. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Получает или задает контраст. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Получает или задает значение, указывающее, является ли [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Получает или задает среднее значение яркости и контраста. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


