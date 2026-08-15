---
title: "Clase IPartialRawDataLoader"
type: docs
weight: 1940
url: /es/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Procesa los datos cargados. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Procesa los datos cargados. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Procesa los datos cargados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de datos. |
| datos | byte | Los datos sin procesar. |
| start | [Point](/psd/python-net/aspose.psd/point) | El punto de datos inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](/psd/python-net/aspose.psd/point) | El punto de datos final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Procesa los datos cargados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de datos. |
| datos | byte | Los datos sin procesar. |
| start | [Point](/psd/python-net/aspose.psd/point) | El punto de datos inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](/psd/python-net/aspose.psd/point) | El punto de datos final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones de carga. |

