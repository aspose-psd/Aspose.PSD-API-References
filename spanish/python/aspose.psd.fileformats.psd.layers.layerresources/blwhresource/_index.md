---
title: "Clase BlwhResource"
type: docs
weight: 90
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Inicializa una nueva instancia de la clase BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| black_and_white_preset_file_name | string | r/w | Obtiene o establece el nombre de archivo de preset en blanco y negro. |
| azules | int | r/w | Obtiene o establece el valor de azules. |
| bw_preset_kind | int | r/w | Obtiene o establece el valor del tipo de preset en blanco y negro. |
| cianes | int | r/w | Obtiene o establece el valor de cianes. |
| verdes | int | r/w | Obtiene o establece el valor de verdes. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| magentas | int | r/w | Obtiene o establece el valor de magentas. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| rojos | int | r/w | Obtiene o establece el valor de reds. |
| signature | int | r | Obtiene la firma. |
| tint_color | int | r/w | Obtiene o establece el valor ARGB del Tint Color. |
| use_tint | bool | r/w | Obtiene o establece un valor que indica si se usa [tint color]. |
| yellows | int | r/w | Obtiene o establece el valor de yellows. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Inicializa una nueva instancia de la clase BlwhResource

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

