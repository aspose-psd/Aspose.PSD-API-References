---
title: CaptionDigestResource
second_title: Справочник по Aspose.PSD для .NET API
description: Ресурс CaptionDigest
type: docs
weight: 3550
url: /ru/net/aspose.psd.fileformats.psd.resources/captiondigestresource/
---
## CaptionDigestResource class

Ресурс CaptionDigest

```csharp
public sealed class CaptionDigestResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CaptionDigestResource](captiondigestresource)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/captiondigestresource/datasize) { get; } | Получает размер данных ресурса в байтах. |
| [Digest](../../aspose.psd.fileformats.psd.resources/captiondigestresource/digest) { get; set; } | Получает или задает дайджест. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/captiondigestresource/minimalversion) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы размер был четным (нулевое имя состоит из двух байтов, равных 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature) { get; } | Получает подпись ресурса. Должно быть всегда «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size) { get; } | Получает размер блока ресурса в байтах, включая его данные. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
