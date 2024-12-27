---
title: CurvResource Class
type: docs
weight: 190
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Initializes a new instance of the [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) class. |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Initializes a new instance of the [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| is_data_stored_discretely | bool | r/w | Gets or sets a value indicating whether this instance is data stored discrete. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Gets the active manager. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Gets the channel data. |
| [get_curve_manager()](#get_curve_manager__3) | Gets the curve manager. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Saves the resource to the specified stream container. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Initializes a new instance of the [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Initializes a new instance of the [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| max_channel_count | int | The maximum channel count. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Gets the active manager.

**Returns**

| Type | Description |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Active manager |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Gets the channel data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Channel data |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Gets the curve manager.

**Returns**

| Type | Description |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) or [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

