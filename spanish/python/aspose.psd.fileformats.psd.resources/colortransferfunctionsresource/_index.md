---
title: "Clase ColorTransferFunctionsResource"
type: docs
weight: 60
url: /es/python-net/aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/
---

**Summary:** Color transfer resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.ColorTransferFunctionsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorTransferFunctionsResource()](#ColorTransferFunctionsResource__1) | Inicializa una nueva instancia de la clase ColorTransferFunctionsResource. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma del recurso de ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma regular del recurso de Photoshop. |
| color_transfer_data | byte | r/w | Obtiene o establece los datos de transferencia de color. |
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


### Constructor: ColorTransferFunctionsResource() {#ColorTransferFunctionsResource__1}


```
 ColorTransferFunctionsResource() 
```

Inicializa una nueva instancia de la clase ColorTransferFunctionsResource.

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque de recurso en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

