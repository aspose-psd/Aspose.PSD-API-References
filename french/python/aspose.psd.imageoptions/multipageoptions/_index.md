---
title: "Classe MultiPageOptions"
type: docs
weight: 70
url: /fr/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit la zone d'exportation. |
| merge_layers | bool | r/w | Obtient ou définit une valeur indiquant si [couches de fusion]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Obtient ou définit le mode. |
| output_layers_names | chaîne | r/w | Obtient ou définit les noms des calques de sortie(Fonctionne si le format d'exportation prend en charge la nomination des calques, par exemple pour Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation de la page. |
| page_titles | chaîne | r/w | Obtient ou définit les titres de page. |
| pages | int | r/w | Obtient ou définit les pages. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Initialise les pages à partir du tableau de plages |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La zone d'exportation. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | chaîne | Les titres de page. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page_titles | chaîne | Les titres de page. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La zone d'exportation. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int | Les pages. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pages | int | Le tableau de pages. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La zone d'exportation. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La zone d'exportation. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Le [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initialise une nouvelle instance de la classe [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Le [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | La zone d'exportation. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Initialise les pages à partir du tableau de plages

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Les plages. |

