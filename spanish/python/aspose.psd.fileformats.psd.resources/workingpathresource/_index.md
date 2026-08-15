---
title: "Clase WorkingPathResource"
type: docs
weight: 320
url: /es/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/
---

**Summary:** Working path resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.WorkingPathResource

**Inheritance:** IVectorPathData, ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WorkingPathResource(data_bytes)](#WorkingPathResource_data_bytes_1) | Inicializa una nueva instancia de la clase [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma del recurso de ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma regular del recurso de Photoshop. |
| data_size | int | r | Obtiene el tamaño de los datos del recurso en bytes. |
| id | short | r/w | Obtiene o establece el identificador único del recurso. |
| is_disabled | bool | r/w | Obtiene o establece un valor que indica si esta instancia está deshabilitada. |
| is_inverted | bool | r/w | Obtiene o establece un valor que indica si esta instancia está invertida. |
| is_not_linked | bool | r/w | Obtiene o establece un valor que indica si esta instancia no está vinculada. |
| minimal_version | int | r | Obtiene la versión mínima requerida del PSD. |
| name | string | r/w | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0). |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Obtiene o establece los registros de ruta. |
| signature | int | r | Obtiene la firma del recurso. Debe ser siempre '8BIM'. |
| tamaño | int | r | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
| version | int | r/w | Obtiene o establece la versión. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque de recurso en el flujo especificado. |
| validate_values() | Valida los valores del recurso. |


### Constructor: WorkingPathResource(data_bytes) {#WorkingPathResource_data_bytes_1}


```
 WorkingPathResource(data_bytes) 
```

Inicializa una nueva instancia de la clase [WorkingPathResource](/psd/python-net/aspose.psd.fileformats.psd.resources/workingpathresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| data_bytes | byte | Los datos de la ruta vectorial. |

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque de recurso en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

