---
title: "ThumbnailResource Class"
type: docs
weight: 250
url: /ru/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | Инициализирует новый экземпляр класса ThumbnailResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Подпись ресурса ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Обычная подпись ресурса Photoshop. |
| bits_pixel | short | r/w | Получает или задает количество бит на пиксель. |
| data_size | int | r | Получает размер данных ресурса в байтах. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Получает или задает формат данных миниатюры. |
| height | int | r/w | Получает или задает высоту миниатюры в пикселях. |
| id | short | r/w | Получает или задает уникальный идентификатор ресурса. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Получает или задает параметры JPEG. Подходит, когда ресурс миниатюры сохраняется только в формате JPEG. Эта опция не влияет, когда определён формат RAW. |
| minimal_version | int | r | Получает минимальную требуемую версию PSD. |
| name | string | r/w | Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| planes_count | short | r/w | Получает или задает количество плоскостей. |
| signature | int | r | Получает подпись ресурса. Должна всегда быть '8BIM'. |
| размер | int | r | Получает размер блока ресурса в байтах, включая его данные. |
| size_after_compression | int | r | Получает или задает размер после сжатия. Используется для проверки согласованности. |
| thumbnail_argb_32_data | int | r/w | Получает или задает 32‑битные данные миниатюры ARGB. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Получает или задает данные миниатюры. |
| total_size | int | r | Получает общий размер данных. |
| width | int | r/w | Получает или задает ширину миниатюры в пикселях. |
| width_bytes | int | r | Получает ширину строки в байтах. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет данные блока ресурсов. |
| validate_values() | Проверяет значения ресурса. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

Инициализирует новый экземпляр класса ThumbnailResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет данные блока ресурсов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

