---
title: "Класс ResolutionInfoResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource класс. Ресурс информации о разрешении"
type: docs
weight: 4350
url: /ru/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
{{< psd/tize >}}
## ResolutionInfoResource class

Ресурс информации о разрешении

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | Горизонтальное DPI. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Получает или задает единицу отображения высоты. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Единицы отображения для горизонтального разрешения. Это влияет только на пользовательский интерфейс; разрешение по‑прежнему хранится в файле PSD в виде пикселей/дюйм. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | Вертикальное DPI. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Единицы отображения для вертикального разрешения. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Получает или задает единицу отображения ширины. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурса. |

### См. также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


