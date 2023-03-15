---
title: Class PrintScaleResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.PrintScaleResource сорт. Ресурс шкалы печати
type: docs
weight: 3840
url: /ru/net/aspose.psd.fileformats.psd.resources/printscaleresource/
---
## PrintScaleResource class

Ресурс шкалы печати

```csharp
public sealed class PrintScaleResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PrintScaleResource](printscaleresource/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/printscaleresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/printscaleresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [Scale](../../aspose.psd.fileformats.psd.resources/printscaleresource/scale/) { get; set; } | Получает или задает масштаб. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |
| [Style](../../aspose.psd.fileformats.psd.resources/printscaleresource/style/) { get; set; } | Получает или задает стиль. |
| [XLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/xlocation/) { get; set; } | Получает или задает местоположение x. |
| [YLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/ylocation/) { get; set; } | Получает или задает местоположение y. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* сборка [Aspose.PSD](../../)


