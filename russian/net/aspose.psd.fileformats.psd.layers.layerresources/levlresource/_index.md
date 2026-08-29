---
title: "Класс LevlResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource класс. Класс LevlResource. Ресурс слоя регулировки экспозиции."
type: docs
weight: 2950
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Класс LevlResource. Ресурс слоя коррекции экспозиции

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Инициализирует новый экземпляр класса `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `LevlResource`. Поддерживается в режимах GrayScale, Duotone, RGB, CMYK, Lab color. 2 байта — версия (=2). 29 * 10 байт — наборы записей уровней с 5 короткими целыми. 4 байта — заголовок Lvls (начинается с индекса 292). 2 байта — версия (=3). 2 байта — количество всех записей уровней. 10 * (Общее количество - 29). Нулевое окончание ресурса Lvls также должно быть выровнено по четырём. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Получает версию. По умолчанию 2. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Получает канал. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


