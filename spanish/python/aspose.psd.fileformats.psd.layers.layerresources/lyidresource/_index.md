---
title: "Clase LyidResource"
type: docs
weight: 660
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Inicializa una nueva instancia de la clase [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Con valor personalizado o desconocido |
| [LyidResource(id)](#LyidResource_id_2) | Inicializa una nueva instancia de la clase [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| value | int | r | Obtiene el valor. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda en el contenedor de flujo especificado. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Inicializa una nueva instancia de la clase [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).<br/>            Con valor personalizado o desconocido

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Inicializa una nueva instancia de la clase [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | int | El identificador de la capa. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo. |
| psd_version | int | La versión PSD. |

