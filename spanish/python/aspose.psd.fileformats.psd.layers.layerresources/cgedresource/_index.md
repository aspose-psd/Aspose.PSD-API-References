---
title: "Clase CgEdResource"
type: docs
weight: 130
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Inicializa una nueva instancia de la clase CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| auto | bool | r/w | Obtiene o establece un valor que indica si este [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) es automático. |
| brillo | int | r/w | Obtiene o establece el brillo. |
| contraste | int | r/w | Obtiene o establece el contraste. |
| key | int | r | Obtiene la clave del recurso de capa. |
| lab_color | bool | r/w | Obtiene o establece un valor que indica si [lab color] está en uso. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| mean_value_for_brightness_and_contrast | int | r/w | Obtiene o establece el valor medio para el brillo y el contraste. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| use_legacy | bool | r/w | Obtiene o establece un valor que indica si [use legacy] está en uso. |
| version | int | r/w | Obtiene o establece la versión. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Inicializa una nueva instancia de la clase CgEdResource

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

