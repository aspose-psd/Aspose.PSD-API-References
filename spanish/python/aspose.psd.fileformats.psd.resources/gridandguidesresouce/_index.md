---
title: "Clase GridAndGuidesResouce"
type: docs
weight: 110
url: /es/python-net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---

**Summary:** Represents the grid and guides resource.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.GridAndGuidesResouce

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GridAndGuidesResouce()](#GridAndGuidesResouce__1) | Inicializa una nueva instancia de la clase GridAndGuidesResouce |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | La firma del recurso de ImageReady. |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | La firma regular del recurso de Photoshop. |
| data_size | int | r | Obtiene el tamaño de los datos del recurso en bytes. |
| grid_cycle_x | int | r/w | Obtiene o establece el ciclo de cuadrícula horizontal. El valor predeterminado es 576. |
| grid_cycle_y | int | r/w | Obtiene o establece el ciclo de cuadrícula vertical. El valor predeterminado es 576. |
| guide_count | int | r | Obtiene el recuento de bloques de recursos de guía. |
| guides | [GuideResource[]](/psd/python-net/aspose.psd.fileformats.psd.resources/guideresource) | r/w | Obtiene o establece las guías. |
| header_version | int | r/w | Obtiene o establece la versión del encabezado. Este valor debe ser siempre 1. |
| id | short | r/w | Obtiene o establece el identificador único del recurso. |
| minimal_version | int | r | Obtiene la versión mínima requerida de psd. |
| name | string | r/w | Obtiene o establece el nombre del recurso. Cadena Pascal, rellenada para que el tamaño sea par (un nombre nulo consiste en dos bytes de 0). |
| signature | int | r | Obtiene la firma del recurso. Debe ser siempre '8BIM'. |
| tamaño | int | r | Obtiene el tamaño del bloque de recurso en bytes, incluidos sus datos. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream)](#save_stream_1) | Guarda el bloque de recurso en el flujo especificado. |
| validate_values() | Valida los valores del recurso. |


### Constructor: GridAndGuidesResouce() {#GridAndGuidesResouce__1}


```
 GridAndGuidesResouce() 
```

Inicializa una nueva instancia de la clase GridAndGuidesResouce

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

Guarda el bloque de recurso en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El flujo donde guardar el bloque de recurso. |

