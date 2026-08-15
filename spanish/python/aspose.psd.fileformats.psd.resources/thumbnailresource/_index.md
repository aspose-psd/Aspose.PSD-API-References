---
title: "Clase ThumbnailResource"
type: docs
weight: 250
url: /es/python-net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---

**Summary:** The thumbnail resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ThumbnailResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ThumbnailResource()](#ThumbnailResource__1) | Inicializa una nueva instancia de la clase ThumbnailResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma del recurso de ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma regular del recurso de Photoshop. |
| bits_pixel | short | r/w | Obtiene o establece los bits por píxel. |
| data_size | int | r | Obtiene el tamaño de los datos del recurso en bytes. |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | Obtiene o establece el formato de datos de la miniatura. |
| altura | int | r/w | Obtiene o establece la altura de la miniatura en píxeles. |
| id | short | r/w | Obtiene o establece el identificador único del recurso. |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | Obtiene o establece las opciones JPEG. Adecuado cuando el recurso de miniatura se guarda únicamente en formato de archivo JPEG. Esta opción no tiene efecto cuando se define el formato RAW. |
| minimal_version | int | r | Obtiene la versión mínima requerida de psd. |
| name | string | r/w | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0). |
| planes_count | short | r/w | Obtiene o establece el recuento de planos. |
| signature | int | r | Obtiene la firma del recurso. Debe ser siempre '8BIM'. |
| tamaño | int | r | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| size_after_compression | int | r | Obtiene o establece el tamaño después de la compresión. Usado para la verificación de consistencia. |
| thumbnail_argb_32_data | int | r/w | Obtiene o establece los datos de miniatura ARGB de 32 bits. |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece los datos de la miniatura. |
| total_size | int | r | Obtiene el tamaño total de los datos. |
| width | int | r/w | Obtiene o establece el ancho de la miniatura en píxeles. |
| width_bytes | int | r | Obtiene el ancho de fila en bytes. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda los datos del bloque de recursos. |
| validate_values() | Valida los valores del recurso. |


### Constructor: ThumbnailResource() {#ThumbnailResource__1}


```
 ThumbnailResource() 
```

Inicializa una nueva instancia de la clase ThumbnailResource

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda los datos del bloque de recursos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

