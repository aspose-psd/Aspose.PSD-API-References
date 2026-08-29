---
title: "MultiPageOptions-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Hämtar eller anger exportområdet. |
| merge_layers | bool | r/w | Hämtar eller anger ett värde som indikerar om [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Hämtar eller anger läget. |
| output_layers_names | string | r/w | Hämtar eller anger namn på utdata lager(Fungerar om exportformatet stöder lagernamngivning, till exempel för Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger sidans rasteriseringsalternativ. |
| page_titles | string | r/w | Hämtar eller anger sidtitlar. |
| pages | int | r/w | Hämtar eller anger sidorna. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Initierar sidorna från intervallarray |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Exportområdet. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string | Sidtitlar. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_titles | string | Sidtitlar. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Exportområdet. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int | Sidorna. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pages | int | Arrayen av sidor. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Exportområdet. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Exportområdet. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Den [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Initierar en ny instans av klassen [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Den [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Exportområdet. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Initierar sidorna från intervallarray

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Intervallen. |

