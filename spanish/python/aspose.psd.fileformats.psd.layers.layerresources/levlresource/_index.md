---
title: "Clase LevlResource"
type: docs
weight: 490
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Inicializa una nueva instancia de la clase [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Inicializa una nueva instancia de la clase [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Compatible con los modos de color GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 bytes - Versión (=2)<br/>            29 * 10 bytes - Conjuntos de registros de nivel con 5 enteros cortos<br/>            4 bytes - Cabecera Lvls (Comienza en el índice 292)<br/>            2 bytes - Versión (=3)<br/>            2 bytes - Recuento total de registros de nivel<br/>            10 * (Recuento total - 29)<br/>            El final cero del recurso Lvls también debe plegarse para cuatro |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
| version | short | r | Obtiene la versión. El valor predeterminado es 2. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Obtiene el canal. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Inicializa una nueva instancia de la clase [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Inicializa una nueva instancia de la clase [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Compatible con los modos de color GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 bytes - Versión (=2)<br/>            29 * 10 bytes - Conjuntos de registros de nivel con 5 enteros cortos<br/>            4 bytes - Cabecera Lvls (Comienza en el índice 292)<br/>            2 bytes - Versión (=3)<br/>            2 bytes - Recuento total de registros de nivel<br/>            10 * (Recuento total - 29)<br/>            El final cero del recurso Lvls también debe plegarse para cuatro

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Obtiene el canal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Datos de nivel del canal |


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

