---
title: "Clase VmskResource"
type: docs
weight: 1100
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | Inicializa una nueva instancia de la clase [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
| [VmskResource(data)](#VmskResource_data_2) | Inicializa una nueva instancia de la clase [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| is_disabled | bool | r/w | Obtiene o establece un valor que indica si esta instancia está deshabilitada. |
| is_inverted | bool | r/w | Obtiene o establece un valor que indica si esta instancia está invertida. |
| is_not_linked | bool | r/w | Obtiene o establece un valor que indica si esta instancia no está vinculada. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Obtiene o establece los registros de ruta. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| version | int | r/w | Obtiene o establece la versión. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

Inicializa una nueva instancia de la clase [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

Inicializa una nueva instancia de la clase [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos del recurso. |

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

