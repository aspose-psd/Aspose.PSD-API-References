---
title: "Класс GridAndGuidesResouce"
type: docs
weight: 110
url: /ru/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Инициализирует новый экземпляр класса GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | Подпись ресурса ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | Обычная подпись ресурса Photoshop. |
| data_size | int | r | Получает размер данных ресурса в байтах. |
| grid_cycle_x | int | r/w | Получает или задает горизонтальный цикл сетки. По умолчанию 576. |
| grid_cycle_y | int | r/w | Получает или задает вертикальный цикл сетки. По умолчанию 576. |
| guide_count | int | r | Получает количество блоков ресурсов направляющих. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Получает или задает направляющие. |
| header_version | int | r/w | Получает или задает версию заголовка. Это значение должно всегда быть 1. |
| id | short | r/w | Получает или задает уникальный идентификатор ресурса. |
| minimal_version | int | r | Получает минимальную требуемую версию PSD. |
| name | string | r/w | Получает или задает имя ресурса. Строка Pascal, дополненная до чётного размера (пустое имя состоит из двух байтов 0). |
| signature | int | r | Получает подпись ресурса. Должна всегда быть '8BIM'. |
| размер | int | r | Получает размер блока ресурса в байтах, включая его данные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream)](#save_stream_1) | Сохраняет блок ресурса в указанный поток. |
| validate_values() | Проверяет значения ресурса. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Инициализирует новый экземпляр класса GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Сохраняет блок ресурса в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Поток, в который сохраняется блок ресурса. |

