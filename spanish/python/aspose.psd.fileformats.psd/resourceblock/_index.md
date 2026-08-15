---
title: "ResourceBlock Clase"
type: docs
weight: 1830
url: /es/python-net/aspose.psd.fileformats.psd/resourceblock/
---

**Summary:** The resource block.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma del recurso de ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma regular del recurso de Photoshop. |
| data_size | int | r | Obtiene el tamaño de los datos del recurso en bytes. |
| id | short | r/w | Obtiene o establece el identificador único del recurso. |
| minimal_version | int | r | Obtiene la versión mínima requerida del PSD. |
| name | string | r/w | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0). |
| signature | int | r | Obtiene la firma del recurso. Debe ser siempre '8BIM'. |
| tamaño | int | r | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque de recurso en el flujo especificado. |
| validate_values() | Valida los valores del recurso. |


### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque de recurso en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

