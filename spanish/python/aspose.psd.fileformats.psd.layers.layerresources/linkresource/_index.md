---
title: "Clase LinkResource"
type: docs
weight: 540
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---

**Summary:** Defines the LinkResource class that contains information about linked or embedded files in the PSD format image.<br/>            The link resource may contain several [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) instances which can be accessed by indexers in any derived class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LinkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| data_source_count | int | r | Obtiene la cantidad de fuentes de datos de enlace que pueden ser accedidas mediante el indexador. |
| is_empty | bool | r | Obtiene un valor que indica si esta instancia de recurso de enlace está vacía. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de enlace global PSD en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda los datos del bloque de recursos. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda los datos del bloque de recursos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

