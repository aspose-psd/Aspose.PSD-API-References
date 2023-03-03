---
title: Class MixrResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource сорт. Класс MixrResource. Ресурс настройки микшера каналов Layer
type: docs
weight: 2820
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Класс MixrResource. Ресурс настройки микшера каналов Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Инициализирует новый экземпляр`MixrResource` class. Спецификация формата PSD содержит следующее описание: 2 Версия (= 1) 2 Monochrome 20 цветов RGB или CMYK плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр`MixrResource` class. Спецификация формата PSD содержит следующее описание: 2 Версия (= 1) 2 Monochrome 20 цветов RGB или CMYK плюс константа для настроек микшера. 4 * 2 байта цвета с 2 байтами константы. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Получает или задает значение, указывающее, является ли это`MixrResource` монохромный. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Получает версию psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Получает подпись. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Получает или задает версию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Получает сырые данные информации о канале |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Устанавливает информацию о канале. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Информационный ключ типа инструмента. |

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


