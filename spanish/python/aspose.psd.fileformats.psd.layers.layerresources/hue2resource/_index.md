---
title: "Clase Hue2Resource"
type: docs
weight: 350
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Inicializa una nueva instancia de la clase [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/). |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Inicializa una nueva instancia de la clase [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| colorize | bool | r/w | Obtiene o establece un valor que indica si este [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) está coloreado. |
| hue | short | r/w | Obtiene o establece el tono maestro. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| lightness | short | r/w | Obtiene o establece la luminosidad maestra. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Obtiene los rangos de la capa de ajuste de tono/saturación.<br/>            Los rangos en PS pueden cambiar de nombre si se modifica el rango, por lo que debemos trabajar por índice. |
| saturación | short | r/w | Obtiene o establece la saturación maestra. |
| signature | int | r | Obtiene la firma. |
| version | short | r | Obtiene la versión. El valor predeterminado es 2. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Inicializa una nueva instancia de la clase [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/).

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Inicializa una nueva instancia de la clase [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/).

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

