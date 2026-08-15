---
title: "Clase IRasterImagePixelLoader"
type: docs
weight: 2010
url: /es/python-net/aspose.psd/irasterimagepixelloader/
---

**Summary:** The raster image pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImagePixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [load_partial_pixels(rectangle, partial_pixel_loader)](#load_partial_pixels_rectangle_partial_pixel_loader_1) | Carga píxeles parcialmente (por bloques). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Carga datos sin procesar. |


### Method: load_partial_pixels(rectangle, partial_pixel_loader) {#load_partial_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_pixels(rectangle, partial_pixel_loader) 
```

Carga píxeles parcialmente (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |
| partial_pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | El cargador parcial de píxeles. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Carga datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo desde el cual cargar los datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará la conversión de datos. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

