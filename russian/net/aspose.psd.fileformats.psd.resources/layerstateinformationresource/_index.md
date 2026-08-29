---
title: "Класс LayerStateInformationResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Psd.Resources.LayerStateInformationResource. Ресурс информации о состоянии слоя"
type: docs
weight: 4280
url: /ru/net/aspose.psd.fileformats.psd.resources/layerstateinformationresource/
---
{{< psd/tize >}}
## LayerStateInformationResource class

Ресурс информации о состоянии слоёв

```csharp
public sealed class LayerStateInformationResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerStateInformationResource](layerstateinformationresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| [LayerIndex](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/layerindex/) { get; set; } | Получает или задает индекс слоя. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layerstateinformationresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурса. |

### См. также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


