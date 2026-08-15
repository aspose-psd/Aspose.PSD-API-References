---
title: "BritResource Clase"
type: docs
weight: 120
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BritResource()](#BritResource__1) | Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Brillo<br/>            2 Contraste<br/>            2 Valor medio para brillo y contraste<br/>            1 Solo color Lab<br/>            No se utiliza en PSD modernos (CS5 y superiores) donde está CgEd. CgEd almacena propiedades de información |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| brillo | short | r/w | Obtiene o establece el brillo. |
| contraste | short | r/w | Obtiene o establece el contraste. |
| key | int | r | Obtiene la clave del recurso de capa. |
| lab_color | bool | r/w | Obtiene o establece un valor que indica si [lab color]. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| mean_value_for_brightness_and_contrast | short | r/w | Obtiene o establece el valor medio para el brillo y el contraste. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brillo | short | El brillo. |
| contraste | short | El contraste. |
| mean_value_for_brightness_and_contrast | short | El valor medio para brillo y contraste. |
| lab_color | bool | si se establece en <c>true</c> [lab color]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Inicializa una nueva instancia de la clase [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Brillo<br/>            2 Contraste<br/>            2 Valor medio para brillo y contraste<br/>            1 Solo color Lab<br/>            No se utiliza en PSD modernos (CS5 y superiores) donde está CgEd. CgEd almacena propiedades de información

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes. |

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

