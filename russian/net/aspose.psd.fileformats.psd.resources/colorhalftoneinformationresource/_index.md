---
title: "Класс ColorHalftoneInformationResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.ColorHalftoneInformationResource класс. Ресурс полутоновой печати"
type: docs
weight: 4130
url: /ru/net/aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/
---
{{< psd/tize >}}
## ColorHalftoneInformationResource class

Ресурс Halftoning

```csharp
public sealed class ColorHalftoneInformationResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ColorHalftoneInformationResource](colorhalftoneinformationresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [HalftoneData](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/halftonedata/) { get; set; } | Получает или задает данные полутоновой печати. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/colorhalftoneinformationresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
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


