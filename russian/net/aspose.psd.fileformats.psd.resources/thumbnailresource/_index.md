---
title: Class ThumbnailResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource сорт. Блок ресурсов эскизов.
type: docs
weight: 3910
url: /ru/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
## ThumbnailResource class

Блок ресурсов эскизов.

```csharp
public class ThumbnailResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | Получает или устанавливает биты пикселя. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | Получает или задает формат данных эскиза. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | Получает или задает высоту эскиза в пикселях. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | Получает или задает параметры JPEG. Подходит, когда ресурс эскиза сохраняется только в формате файла JPEG. Этот параметр не действует, если задан формат RAW. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | Получает минимальную требуемую версию psd. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Строка Паскаля, дополненная, чтобы сделать размер четным (нулевое имя состоит из двух байтов 0). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | Получает или задает количество самолетов. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает подпись ресурса. Всегда должно быть «8BIM». |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурсов в байтах, включая его данные. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | Получает или задает размер после сжатия. Используется для проверки согласованности. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | Получает или задает 32-разрядные данные миниатюр ARGB. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | Получает или задает данные эскиза. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | Получает общий размер данных. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | Получает или задает ширину эскиза в пикселях. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | Получает ширину строки в байтах. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурсов в указанный поток. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | Проверяет значения ресурсов. |

### Смотрите также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* сборка [Aspose.PSD](../../)


