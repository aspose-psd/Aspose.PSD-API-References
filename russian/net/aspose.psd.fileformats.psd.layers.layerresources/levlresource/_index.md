---
title: LevlResource
second_title: Справочник по Aspose.PSD для .NET API
description: Класс LevlResource. Ресурс корректирующего слоя экспозиции
type: docs
weight: 2580
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Класс LevlResource. Ресурс корректирующего слоя экспозиции

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LevlResource](levlresource#constructor)() | Инициализирует новый экземпляр класса[`LevlResource`](../levlresource). |
| [LevlResource](levlresource#constructor_1)(byte[]) | Инициализирует новый экземпляр класса[`LevlResource`](../levlresource). Поддерживается в цветовых режимах GrayScale, Duotone, RGB, CMYK, Lab 2 байта - Версия (=2) 29 * 10 байтов - Наборы уровней записи с 5 короткими целыми числами 4 байта - заголовок Lvls (начинается с индекса 292) 2 байта - версия (=3) 2 байта - количество общая запись уровня 10 * (Общее количество - 29) Нулевое окончание ресурса Lvls должно быть свернуто и для четырех |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion) { get; } | Получает версию в формате psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Получает подпись. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version) { get; } | Получает версию. По умолчанию 2 |

## Методы

| Имя | Описание |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel)(int) | Получает канал. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | ВозвращаетString, представляющий этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey) | Клавиша информации о типе инструмента. |

### Смотрите также

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
