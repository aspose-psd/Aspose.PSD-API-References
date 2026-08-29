---
title: "Класс LayerGroupInformationResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.LayerGroupInformationResource класс. Ресурс информации о группе слоёв"
type: docs
weight: 4250
url: /ru/net/aspose.psd.fileformats.psd.resources/layergroupinformationresource/
---
{{< psd/tize >}}
## LayerGroupInformationResource class

Ресурс информации о группе слоёв

```csharp
public sealed class LayerGroupInformationResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LayerGroupInformationResource](layergroupinformationresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [Groups](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/groups/) { get; set; } | Получает или задает группы. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/layergroupinformationresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
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


