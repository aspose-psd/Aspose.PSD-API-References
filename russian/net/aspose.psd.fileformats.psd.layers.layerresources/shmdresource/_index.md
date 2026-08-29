---
title: "Класс ShmdResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource класс. Класс ShmdResource. Настройки метаданных"
type: docs
weight: 3330
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

Класс ShmdResource. Настройки метаданных

```csharp
public class ShmdResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | Инициализирует новый экземпляр класса `ShmdResource`. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `ShmdResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | Получает или задает время создания слоя. Если время создания слоя не указано, возвращает новый DateTime(0) |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | Получает подресурсы ресурса shmd. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | Сохраняет указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | Длина заголовка подресурса |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


