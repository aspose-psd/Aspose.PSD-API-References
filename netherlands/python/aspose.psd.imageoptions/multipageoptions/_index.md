---
title: "MultiPageOptions Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt op of stelt het exportgebied in. |
| merge_layers | bool | r/w | Geeft of stelt een waarde in die aangeeft of [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Geeft of stelt de modus in. |
| output_layers_names | string | r/w | Geeft of stelt de namen van de uitvoerlagen in (Werkt als het exportformaat lagennaamgeving ondersteunt, bijvoorbeeld voor Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Geeft of stelt de rasterisatie‑opties voor de pagina in. |
| page_titles | string | r/w | Geeft of stelt de paginatitels in. |
| pages | int | r/w | Geeft of stelt de pagina's in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Initialiseert de pagina's vanuit een reeks‑array. |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Het exportgebied. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_titles | string | De paginatitels. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_titles | string | De paginatitels. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Het exportgebied. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pages | int | De pagina's. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pages | int | De array van pagina's. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Het exportgebied. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Het exportgebied. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | De [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initialiseert een nieuw exemplaar van de [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | De [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Het exportgebied. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Initialiseert de pagina's vanuit een reeks‑array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | De reeksen. |

