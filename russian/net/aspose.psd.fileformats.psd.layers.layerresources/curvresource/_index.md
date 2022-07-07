---
title: CurvResource
second_title: Справочник по Aspose.PSD для .NET API
description: Класс CurvResource. Ресурс корректирующего слоя кривых 1 байт - 0 если используются кривые 1 если используются пиксели на карте если 0 то 2 байта - короткие. По умолчанию 1 4 байта - инт. Используется только последний байт за битом. Первый бит для 1 канала Четвертый бит для 4 канала например 2 байта - количество коротких точек 4 байта  количество точек - точек кривой 2 короткопервая позиция  вторая высота 4 байта - слово Crv 2 байта - короткое по умолчанию 4 для кривых 4 байта - инт. По умолчанию 1 4 байта - количество точек 4 байта  количество точек - точки кривой 2 короткиепервая позиция вторая высота 0-4 байта - Ведущий нужно сложить на четыре если 1 то 2 байта - короткий. По умолчанию 1 4 байта - инт. Используется только последний байт. Один канал в одном бите. Первый бит для 1 канала Четвертый бит для 4 канала например 256  количество измененных каналов - упорядоченные значения канала в диапазоне 0 - 255 4 байта - слово  Crv 2 байта - короткий. По умолчанию 3 для пикселей на карте 4 байта - int Количество каналов 2  256 байт - короткая 2 для индекса канала 256 упорядоченных значений канала в диапазоне 0 - 255
type: docs
weight: 2340
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Класс CurvResource. Ресурс корректирующего слоя кривых 1 байт - 0 если используются кривые, 1 если используются пиксели на карте если 0 то: 2 байта - короткие. По умолчанию 1 4 байта - инт. Используется только последний байт за битом. Первый бит для 1 канала, Четвертый бит для 4 канала например 2 байта - количество коротких точек 4 байта * количество точек - точек кривой 2 коротко:первая позиция , вторая высота 4 байта - слово "Crv" 2 байта - короткое по умолчанию 4 для кривых 4 байта - инт. По умолчанию 1 4 байта - количество точек 4 байта * количество точек - точки кривой 2 короткие:первая позиция, вторая высота 0-4 байта - Ведущий нужно сложить на четыре если 1 то: 2 байта - короткий. По умолчанию 1 4 байта - инт. Используется только последний байт. Один канал в одном бите. Первый бит для 1 канала, Четвертый бит для 4 канала например 256 * количество измененных каналов - упорядоченные значения канала в диапазоне 0 - 255 4 байта - слово " Crv" 2 байта - короткий. По умолчанию 3 для пикселей на карте 4 байта - int Количество каналов (2 + 256) байт - короткая 2 для индекса канала, 256 упорядоченных значений канала в диапазоне 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CurvResource](curvresource#constructor)(byte[]) | Инициализирует новый экземпляр класса[`CurvResource`](../curvresource). |
| [CurvResource](curvresource#constructor_1)(int) | Инициализирует новый экземпляр класса[`CurvResource`](../curvresource). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely) { get; set; } | Получает или задает значение, указывающее, является ли этот экземпляр хранимыми данными дискретными. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion) { get; } | Получает версию в формате psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager)() | Получает активного менеджера. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata)(int) | Получает данные канала. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager)() | Получает менеджер кривых. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey) | Клавиша информации о типе инструмента. |

### Смотрите также

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
