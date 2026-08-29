---
title: "Класс VersionInfoResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.VersionInfoResource класс. Ресурс информации о версии"
type: docs
weight: 4430
url: /ru/net/aspose.psd.fileformats.psd.resources/versioninforesource/
---
{{< psd/tize >}}
## VersionInfoResource class

Ресурс информации о версии

```csharp
public sealed class VersionInfoResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VersionInfoResource](versioninforesource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/versioninforesource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [FileVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/fileversion/) { get; set; } | Получает или задает версию файла. |
| [HasRealMergedData](../../aspose.psd.fileformats.psd.resources/versioninforesource/hasrealmergeddata/) { get; set; } | Получает или задает значение, указывающее, содержит ли этот экземпляр реальные объединённые данные. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/versioninforesource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [ReaderName](../../aspose.psd.fileformats.psd.resources/versioninforesource/readername/) { get; set; } | Получает или задает имя считывателя. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |
| [Version](../../aspose.psd.fileformats.psd.resources/versioninforesource/version/) { get; set; } | Получает или задает версию. |
| [WriterName](../../aspose.psd.fileformats.psd.resources/versioninforesource/writername/) { get; set; } | Получает или задает имя записывающего. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурса. |

### См. также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


