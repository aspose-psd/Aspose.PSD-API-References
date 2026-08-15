---
title: "Clase LnkeResource"
type: docs
weight: 590
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/
---

**Summary:** Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image.<br/>            The link resource may contain several [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) instances which can be accessed by indexer.<br/>            This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnkeResource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LnkeResource()](#LnkeResource__1) | Inicializa una nueva instancia de la clase [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
| [LnkeResource(data_sources)](#LnkeResource_data_sources_2) | Inicializa una nueva instancia de la clase [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
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


### Constructor: LnkeResource() {#LnkeResource__1}


```
 LnkeResource() 
```

Inicializa una nueva instancia de la clase [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

### Constructor: LnkeResource(data_sources) {#LnkeResource_data_sources_2}


```
 LnkeResource(data_sources) 
```

Inicializa una nueva instancia de la clase [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_sources | [LinkDataSource[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) | Las fuentes de datos. |

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

