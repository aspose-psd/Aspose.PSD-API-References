---
title: "Класс GridAndGuidesResouce"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce класс. Представляет ресурс сетки и направляющих."
type: docs
weight: 4200
url: /ru/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

Представляет ресурс сетки и направляющих.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Получает или задает горизонтальный цикл сетки. По умолчанию 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Получает или задает вертикальный цикл сетки. По умолчанию 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Получает количество блоков ресурса направляющих. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Получает или задает направляющие. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Получает или задает версию заголовка. Это значение должно всегда быть 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
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


