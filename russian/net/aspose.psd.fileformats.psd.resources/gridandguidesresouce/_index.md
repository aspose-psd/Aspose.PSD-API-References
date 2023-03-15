---
title: Class GridAndGuidesResouce
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce сорт. Представляет сетку и направляет ресурс.
type: docs
weight: 3730
url: /ru/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
## GridAndGuidesResouce class

Представляет сетку и направляет ресурс.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Получает или задает цикл горизонтальной сетки. По умолчанию 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Получает или задает цикл вертикальной сетки. По умолчанию 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Получает количество блоков ресурсов руководства. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Получает или устанавливает направляющие. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Получает или задает версию заголовка. Это значение всегда должно быть 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Получает минимальную требуемую версию psd. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* сборка [Aspose.PSD](../../)


