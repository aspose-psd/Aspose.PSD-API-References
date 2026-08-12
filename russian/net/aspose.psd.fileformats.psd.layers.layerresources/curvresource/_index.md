---
title: "Класс CurvResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource класс. Класс CurvResource. Ресурс слоя регулировки кривых 1 байт 0 если используются кривые 1 если используются пиксели на карте, если 0 то 2 байта short. По умолчанию 1. 4 байта int. Используется только последний байт битом. Первый бит — для 1 канала, четвертый бит — для 4 каналов, например 2 байта short количество точек. 4 байта количество точек кривой. 2 short первая позиция, вторая высота. 4 байта word Crv. 2 байта short по умолчанию 4 для Curves. 4 байта int. По умолчанию 1. 4 байта количество точек. 4 байта количество точек кривой. 2 short первая позиция, вторая высота. 04 байта Ведущее выравнивание до четырёх, если 1 то 2 байта short. По умолчанию 1. 4 байта int. Используется только последний байт. Один канал в одном бите. Первый бит — для 1 канала, четвертый бит — для 4 каналов, например 256 количество изменённых каналов упорядоченные значения канала в диапазоне 0‑255. 4 байта word Crv. 2 байта short по умолчанию 3 для пикселей на карте. 4 байта int количество каналов 2 256 байт short 2 для индекса канала 256 упорядоченные значения канала в диапазоне 0‑255."
type: docs
weight: 2660
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Класс CurvResource. Ресурс слоя коррекции кривых. 1 байт — 0, если используются кривые, 1, если используется карта пикселей; если 0, то: 2 байта — short. По умолчанию 1. 4 байта — int. Используется только последний байт по биту. Первый бит — для 1 канала, четвёртый бит — для 4 каналов, например 2 байта — short количество точек. 4 байта * количество точек — точки кривой. 2 short: первая позиция, вторая высота. 4 байта — слово "Crv ". 2 байта — short, по умолчанию 4 для кривых. 4 байта — int, по умолчанию 1. 4 байта — количество точек. 4 байта * количество точек — точки кривой. 2 short: первая позиция, вторая высота. 0‑4 байта — ведущие для четырёх, если 1, то: 2 байта — short, по умолчанию 1. 4 байта — int, используется только последний байт. Один канал в одном бите. Первый бит — для 1 канала, четвёртый бит — для 4 каналов, например 256 * количество изменённых каналов — упорядоченные значения канала в диапазоне 0‑255. 4 байта — слово "Crv ". 2 байта — short, по умолчанию 3 для карты пикселей. 4 байта — int количество каналов (2 + 256) байт — short 2 для индекса канала, 256 — упорядоченные значения канала в диапазоне 0‑255.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Инициализирует новый экземпляр класса `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Инициализирует новый экземпляр класса `CurvResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Получает или задает значение, указывающее, хранится ли данный экземпляр дискретно. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Получает активный менеджер. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Получает данные канала. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Получает менеджер кривой. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


