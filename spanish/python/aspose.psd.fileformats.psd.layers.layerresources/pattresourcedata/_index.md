---
title: "Clase PattResourceData"
type: docs
weight: 780
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Inicializa una nueva instancia de la clase PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| altura | short | r | Obtiene la altura. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Obtiene el modo de imagen. |
| longitud | int | r | Obtiene la longitud del patrón. |
| name | string | r/w | Obtiene o establece el nombre. |
| pattern_data | int | r | Obtiene los datos del patrón. |
| pattern_id | string | r/w | Obtiene o establece el identificador del patrón. |
| version | int | r | Obtiene la versión. |
| width | short | r | Obtiene el ancho. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Guarda los datos del patrón. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Establece el patrón. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Inicializa una nueva instancia de la clase PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Guarda los datos del patrón.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Establece el patrón.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels | int | Los píxeles. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Los límites. |

