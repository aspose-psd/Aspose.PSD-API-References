---
title: LevlResource Class
type: docs
weight: 450
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Initializes a new instance of the [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) class. |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Initializes a new instance of the [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) class.<br/>            Supported in GrayScale, Duotone, RGB, CMYK, Lab color modes<br/>            2 bytes - Version (=2)<br/>            29 * 10 bytes - Sets of level records with 5 short integers<br/>            4 bytes - Lvls header (Starts at 292 index)<br/>            2 bytes - Version (=3)<br/>            2 bytes - Count of total level record<br/>            10 * (Total Count - 29)<br/>            Zero ending of Lvls resource should be fold for four too |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| version | short | r | Gets the version. Default is 2 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Gets the channel. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Saves the resource to the specified stream container. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Initializes a new instance of the [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) class.

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Initializes a new instance of the [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) class.<br/>            Supported in GrayScale, Duotone, RGB, CMYK, Lab color modes<br/>            2 bytes - Version (=2)<br/>            29 * 10 bytes - Sets of level records with 5 short integers<br/>            4 bytes - Lvls header (Starts at 292 index)<br/>            2 bytes - Version (=3)<br/>            2 bytes - Count of total level record<br/>            10 * (Total Count - 29)<br/>            Zero ending of Lvls resource should be fold for four too

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Gets the channel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| channel_index | int | Index of the channel. |

**Returns**

| Type | Description |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Level Data of Channel |


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

