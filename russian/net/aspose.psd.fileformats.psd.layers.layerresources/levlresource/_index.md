---
title: Class LevlResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource сорт. Класс ЛевлРесаурце. Ресурс корректирующего слоя экспозиции
type: docs
weight: 2640
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Класс ЛевлРесаурце. Ресурс корректирующего слоя экспозиции

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Инициализирует новый экземпляр`LevlResource` класс. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр`LevlResource` class. Поддерживается в режимах GrayScale, Duotone, RGB, CMYK, Lab. 2 байта - Версия (=3) 2 байта - Счетчик общего уровня record 10 * (Общий счет - 29) Нулевой конец ресурса Lvls должен быть сложен на четыре too |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Получает версию psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Получает подпись. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Получает версию. По умолчанию 2 |

## Методы

| Имя | Описание |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Получает канал. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Информационный ключ типа инструмента. |

### Смотрите также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


