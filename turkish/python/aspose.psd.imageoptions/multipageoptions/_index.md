---
title: "MultiPageOptions Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Dışa aktarma alanını alır veya ayarlar. |
| merge_layers | bool | r/w | Bir değeri alır veya ayarlar; [merege layers] olup olmadığını gösterir. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Modu alır veya ayarlar. |
| output_layers_names | string | r/w | Çıktı katman adlarını alır veya ayarlar(İhracat formatı katman adlandırmayı destekliyorsa çalışır, örneğin Psd için) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Sayfa rasterleştirme seçeneklerini alır veya ayarlar. |
| page_titles | string | r/w | Sayfa başlıklarını alır veya ayarlar. |
| pages | int | r/w | Sayfaları alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Sayfaları aralıklar dizisinden başlatır |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İhracat alanı. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string | Sayfa başlıkları. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_titles | string | Sayfa başlıkları. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İhracat alanı. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pages | int | Sayfalar. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pages | int | Sayfalar dizisi. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İhracat alanı. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İhracat alanı. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Bu [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Yeni bir [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Bu [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İhracat alanı. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Sayfaları aralıklar dizisinden başlatır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Aralıklar. |

