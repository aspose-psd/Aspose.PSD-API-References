---
title: "MultiPageOptions Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt den Exportbereich. |
| merge_layers | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Liest oder setzt den Modus. |
| output_layers_names | string | r/w | Liest oder setzt die Namen der Ausgabelayer (Funktioniert, wenn das Exportformat die Benennung von Layern unterstützt, zum Beispiel für Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Seitenrasterisierungsoptionen. |
| page_titles | string | r/w | Liest oder setzt die Seitentitel. |
| pages | int | r/w | Liest oder setzt die Seiten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Initialisiert die Seiten aus dem Bereichsarray. |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Der Exportbereich. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string | Die Seitentitel. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_titles | string | Die Seitentitel. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Der Exportbereich. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pages | int | Die Seiten. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pages | int | Das Array der Seiten. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Der Exportbereich. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Der Exportbereich. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Der [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initialisiert eine neue Instanz der [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Der [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Der Exportbereich. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Initialisiert die Seiten aus dem Bereichsarray.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Die Bereiche. |

