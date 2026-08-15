---
title: "Clase MixrResource"
type: docs
weight: 680
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Inicializa una nueva instancia de la [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) clase.<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Versión ( = 1)<br/>            2 Monocromo<br/>            20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |
| [MixrResource(data)](#MixrResource_data_2) | Inicializa una nueva instancia de la [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) clase.<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Versión ( = 1)<br/>            2 Monocromo<br/>            20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| monochrome | bool | r/w | Obtiene o establece un valor que indica si este [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) es monocromo. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| version | short | r/w | Obtiene o establece la versión. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Obtiene los datos brutos de la información del canal. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Guarda el recurso en el contenedor de flujo especificado. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Establece la información del canal. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Inicializa una nueva instancia de la [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) clase.<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Versión ( = 1)<br/>            2 Monocromo<br/>            20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Inicializa una nueva instancia de la [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) clase.<br/>            La especificación del formato PSD contiene la siguiente descripción:<br/>            2 Versión ( = 1)<br/>            2 Monocromo<br/>            20 color RGB o CMYK más constante para los ajustes del mezclador. 4 * 2 bytes de color con 2 bytes de constante.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos del recurso. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Obtiene los datos brutos de la información del canal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Matriz de bytes crudos de la información del canal. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Establece la información del canal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |
| value | byte | El valor. |

