---
title: "Clase CurvResource"
type: docs
weight: 190
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Inicializa una nueva instancia de la clase [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Inicializa una nueva instancia de la clase [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La firma de recurso específica de PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La firma de recurso común. |
| TYPE_TOOL_KEY [static] | int | r | La clave de información de la herramienta de tipo. |
| is_data_stored_discretely | bool | r/w | Obtiene o establece un valor que indica si esta instancia almacena datos de forma discreta. |
| key | int | r | Obtiene la clave del recurso de capa. |
| longitud | int | r | Obtiene la longitud del recurso de capa en bytes. |
| psd_version | int | r | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| signature | int | r | Obtiene la firma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Obtiene el administrador activo. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Obtiene los datos del canal. |
| [get_curve_manager()](#get_curve_manager__3) | Obtiene el administrador de curvas. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Guarda el recurso en el contenedor de flujo especificado. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Inicializa una nueva instancia de la clase [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bytes | byte | Los bytes. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Inicializa una nueva instancia de la clase [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| max_channel_count | int | El recuento máximo de canales. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Obtiene el administrador activo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Administrador activo |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Obtiene los datos del canal.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| channel_index | int | Índice del canal. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Datos del canal |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Obtiene el administrador de curvas.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) o [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Guarda el recurso en el contenedor de flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | El contenedor de flujo donde guardar. |
| psd_version | int | La versión PSD. |

