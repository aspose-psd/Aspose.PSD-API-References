---
title: "Clase PtFlResource"
type: docs
weight: 860
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | Inicializa una nueva instancia de la clase [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | Inicializa una nueva instancia de la clase [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| align_with_layer | bool | r/w | Obtiene o establece un valor que indica si [alinear con capa]. |
| ángulo | double | r/w | Obtiene o establece el ángulo. |
| is_linked_with_layer | bool | r/w | Obtiene o establece un valor que indica si esta instancia está vinculada con la capa. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Obtiene o establece el desplazamiento. |
| pattern_id | string | r/w | Obtiene o establece el identificador del patrón. |
| pattern_name | string | r/w | Obtiene o establece el nombre del patrón. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| scale | double | r/w | Obtiene o establece la escala. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

Inicializa una nueva instancia de la clase [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

Inicializa una nueva instancia de la clase [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pattern_name | string | Nombre del patrón. |
| pattern_id | string | El identificador del patrón. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

