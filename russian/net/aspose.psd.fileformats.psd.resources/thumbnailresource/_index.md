---
title: "Класс ThumbnailResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource класс. Блок ресурса миниатюры"
type: docs
weight: 4380
url: /ru/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
{{< psd/tize >}}
## ThumbnailResource class

Блок ресурса миниатюры.

```csharp
public class ThumbnailResource : ResourceBlock
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | Получает или задает количество битов на пиксель. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | Получает размер данных ресурса в байтах. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | Получает или задает формат данных миниатюры. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | Получает или задает высоту миниатюры в пикселях. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Получает или задает уникальный идентификатор ресурса. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | Получает или задает параметры JPEG. Подходит, когда ресурс миниатюры сохраняется только в формате JPEG. Эта опция не влияет, если определён формат RAW. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | Получает минимальную требуемую версию PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Получает или задает имя ресурса. Паскаль-строка, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | Получает или задает количество плоскостей. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Получает сигнатуру ресурса. Должна всегда быть '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Получает размер блока ресурса в байтах, включая его данные. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | Получает или задает размер после сжатия. Используется для проверки согласованности. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | Получает или задает 32‑битные ARGB данные миниатюры. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | Получает или задает данные миниатюры. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | Получает общий размер данных. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | Получает или задает ширину миниатюры в пикселях. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | Получает ширину строки в байтах. |

## Методы

| Имя | Описание |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Сохраняет блок ресурса в указанный поток. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | Проверяет значения ресурса. |

### См. также

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


