---
title: "Clase PattResource"
type: docs
weight: 770
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PattResource()](#PattResource__1) | Inicializa una nueva instancia de la clase [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Inicializa una nueva instancia de la clase [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de herramienta de tipo 'Patt' para 8 bits. |
| TYPE_TOOL_KEY2 [static] | int | r | La clave de información de herramienta de tipo 'Pat2' para 16 bits. |
| TYPE_TOOL_KEY3 [static] | int | r | La clave de información de herramienta de tipo 'Pat3' para 32 bits. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Obtiene o establece los datos de patrones; |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda los datos del bloque de recursos. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Inicializa una nueva instancia de la clase [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Inicializa una nueva instancia de la clase [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | int | La clave del tipo de recurso. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Los datos de patrones. |

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

