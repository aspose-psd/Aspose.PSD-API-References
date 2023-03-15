---
title: Class ResourceBlock
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.ResourceBlock сорт. Блок ресурсов.
type: docs
weight: 3610
url: /ru/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

Блок ресурсов.

```csharp
public abstract class ResourceBlock
```

## Характеристики

| Имя | Описание |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Проверяет значения ресурсов. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | Подпись ресурса ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | Обычная подпись ресурса Photoshop. |

## Другие члены

| Имя | Описание |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | Представляет состояние блока ресурсов. |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* сборка [Aspose.PSD](../../)


