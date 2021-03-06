---
title: BritResource
second_title: Справочник по Aspose.PSD для .NET API
description: Класс BritResource. Ресурс слоя регулировки яркости/контрастности
type: docs
weight: 2280
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

Класс BritResource. Ресурс слоя регулировки яркости/контрастности

```csharp
public class BritResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BritResource](britresource#constructor)() | Инициализирует новый экземпляр класса[`BritResource`](../britresource). |
| [BritResource](britresource#constructor_1)(byte[]) | Инициализирует новый экземпляр класса[`BritResource`](../britresource). Спецификация формата PSD содержит следующее описание: 2 Яркость 2 Контрастность 2 Среднее значение яркости и контрастности 1 Только лабораторный цвет Он не используется в современных PSD (CS5 и выше), где есть CgEd. CgEd хранит информационные свойства |
| [BritResource](britresource#constructor_2)(short, short, short, bool) | Инициализирует новый экземпляр класса[`BritResource`](../britresource). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness) { get; set; } | Получает или устанавливает яркость. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast) { get; set; } | Получает или устанавливает контрастность. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key) { get; } | Получает ключ ресурса слоя. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor) { get; set; } | Получает или задает значение, указывающее, является ли [лабораторный цвет]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length) { get; } | Получает длину ресурса слоя в байтах. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast) { get; set; } | Получает или задает среднее значение яркости и контрастности. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion) { get; } | Получает версию в формате psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey) | Клавиша информации о типе инструмента. |

### Смотрите также

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
