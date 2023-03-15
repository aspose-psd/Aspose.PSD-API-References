---
title: Class XmpResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.XmpResource сорт. Представляет ресурс метаданных XMP.
type: docs
weight: 3990
url: /ru/net/aspose.psd.fileformats.psd.resources/xmpresource/
---
## XmpResource class

Представляет ресурс метаданных XMP.

```csharp
public sealed class XmpResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpResource](xmpresource/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/xmpresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/xmpresource/minimalversion/) { get; } | Получает минимальную требуемую версию psd. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |
| [XmpData](../../aspose.psd.fileformats.psd.resources/xmpresource/xmpdata/) { get; set; } | Получить или установить контейнер данных XMP |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* сборка [Aspose.PSD](../../)


