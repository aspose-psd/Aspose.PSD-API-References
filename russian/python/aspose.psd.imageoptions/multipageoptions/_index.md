---
title: "Класс MultiPageOptions"
type: docs
weight: 70
url: /ru/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает область экспорта. |
| merge_layers | bool | r/w | Получает или задает значение, указывающее, следует ли [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Получает или задает режим. |
| output_layers_names | string | r/w | Получает или задает имена выходных слоев (Работает, если формат экспорта поддерживает именование слоев, например для Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры растеризации страницы. |
| page_titles | string | r/w | Получает или задает заголовки страниц. |
| pages | int | r/w | Получает или задает страницы. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Инициализирует страницы из массива диапазонов |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Область экспорта. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_titles | string | Заголовки страниц. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_titles | string | Заголовки страниц. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Область экспорта. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pages | int | Страницы. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pages | int | Массив страниц. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Область экспорта. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Область экспорта. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Элемент [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Инициализирует новый экземпляр класса [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Элемент [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Область экспорта. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Инициализирует страницы из массива диапазонов

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Диапазоны. |

