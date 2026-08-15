---
title: "Clase MultiPageOptions"
type: docs
weight: 70
url: /es/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece el área de exportación. |
| merge_layers | bool | r/w | Obtiene o establece un valor que indica si [merege layers]. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | Obtiene o establece el modo. |
| output_layers_names | string | r/w | Obtiene o establece los nombres de las capas de salida(Funciona si el formato de exportación admite la denominación de capas, por ejemplo para Psd) |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización de la página. |
| page_titles | string | r/w | Obtiene o establece los títulos de página. |
| pages | int | r/w | Obtiene o establece las páginas. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | Inicializa las páginas a partir del arreglo de rangos |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El área de exportación. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_titles | string | Los títulos de página. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_titles | string | Los títulos de página. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El área de exportación. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int | Las páginas. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pages | int | El arreglo de páginas. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El área de exportación. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El área de exportación. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | El [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

Inicializa una nueva instancia de la clase [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | El [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El área de exportación. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

Inicializa las páginas a partir del arreglo de rangos

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | Los rangos. |

