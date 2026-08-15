---
title: "Clase VscgResource"
type: docs
weight: 30
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Inicializa una nueva instancia de la clase VscgResource. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Obtiene o establece la matriz de elementos de estructura.<br/>            **Warning:** Los valores de la matriz `Items` deben coincidir con la propiedad `KeyForData`, que determina el tipo de configuración de relleno almacenada en las estructuras dentro de `Items`. |
| key | int | r | Obtiene la clave del recurso de capa. |
| key_for_data | int | r | Obtiene la clave entera que define qué tipo de configuración de relleno se almacena en el recurso:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradiente - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Patrón - 0x5074466c - PtFlResource.TypeToolKey<br/>            ¡Advertencia! El valor de la propiedad KeyForData debe coincidir con el tipo de configuración de Relleno almacenado en las estructuras Items. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Inicializa una nueva instancia de la clase VscgResource.

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

