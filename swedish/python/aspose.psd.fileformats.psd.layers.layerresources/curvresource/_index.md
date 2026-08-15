---
title: "CurvResource-klass"
type: docs
weight: 190
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Initierar en ny instans av klassen [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) . |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Initierar en ny instans av klassen [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| is_data_stored_discretely | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans har data lagrad diskret. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| signatur | int | r | Hämtar signaturen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Hämtar den aktiva hanteraren. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Hämtar kanaldata. |
| [get_curve_manager()](#get_curve_manager__3) | Hämtar kurvhanteraren. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Initierar en ny instans av klassen [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bytes | byte | Byte. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Initierar en ny instans av klassen [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| max_channel_count | int | Det maximala kanalantalet. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Hämtar den aktiva hanteraren.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Aktiv hanterare |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Hämtar kanaldata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| channel_index | int | Kanalens index. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Kanaldata |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Hämtar kurvhanteraren.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) eller [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

