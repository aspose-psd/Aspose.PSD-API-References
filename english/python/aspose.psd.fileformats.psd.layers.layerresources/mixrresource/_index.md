---
title: MixrResource Class
type: docs
weight: 630
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Initializes a new instance of the [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant. |
| [MixrResource(data)](#MixrResource_data_2) | Initializes a new instance of the [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| monochrome | bool | r/w | Gets or sets a value indicating whether this [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) is monochrome. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| version | short | r/w | Gets or sets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Gets the channel information raw data |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Saves the resource to the specified stream container. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Sets the channel information. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Initializes a new instance of the [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Initializes a new instance of the [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) class.<br/>            PSD format specification contains following description:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 RGB or CMYK color plus constant for the mixer settings. 4 * 2 bytes of color with 2 bytes of constant.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The data of the resource. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Gets the channel information raw data

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Raw byte array of channel info. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Sets the channel information.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |
| value | byte | The value. |

