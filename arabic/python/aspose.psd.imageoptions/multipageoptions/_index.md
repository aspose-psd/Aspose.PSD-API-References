---
title: "MultiPageOptions فئة"
type: docs
weight: 70
url: /ar/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | يحصل أو يضبط منطقة التصدير. |
| merge_layers | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | يحصل أو يعيّن الوضع. |
| output_layers_names | string | r/w | يحصل أو يعيّن أسماء طبقات الإخراج(يعمل إذا كان تنسيق التصدير يدعم تسمية الطبقات، على سبيل المثال لـ Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | يحصل أو يعيّن خيارات تمثيل الصفحة. |
| page_titles | string | r/w | يحصل أو يعيّن عناوين الصفحات. |
| pages | int | r/w | يحصل أو يعيّن الصفحات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | يُهيئ الصفحات من مصفوفة النطاقات |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | منطقة التصدير. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| page_titles | string | عناوين الصفحات. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| page_titles | string | عناوين الصفحات. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | منطقة التصدير. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pages | int | الصفحات. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| pages | int | مصفوفة الصفحات. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | منطقة التصدير. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | منطقة التصدير. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | ال [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

يُنشئ مثلاً جديدًا من الفئة [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | ال [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | منطقة التصدير. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

يُهيئ الصفحات من مصفوفة النطاقات

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | النطاقات. |

