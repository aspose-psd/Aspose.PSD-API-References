---
title: "CurvResource klasse"
type: docs
weight: 190
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Initialiseert een nieuw exemplaar van de [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) klasse. |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Initialiseert een nieuw exemplaar van de [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| is_data_stored_discretely | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of deze instantie discrete gegevens opslaat. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| signature | int | r | Haalt de handtekening op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Haalt de actieve manager op. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Haalt de kanaalgegevens op. |
| [get_curve_manager()](#get_curve_manager__3) | Haalt de curve‑manager op. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Initialiseert een nieuw exemplaar van de [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bytes | byte | De bytes. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Initialiseert een nieuw exemplaar van de [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| max_channel_count | int | Het maximale kanaalaantal. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Haalt de actieve manager op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Actieve manager |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Haalt de kanaalgegevens op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| channel_index | int | Index van het kanaal. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Kanaalgegevens |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Haalt de curve‑manager op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) of [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

