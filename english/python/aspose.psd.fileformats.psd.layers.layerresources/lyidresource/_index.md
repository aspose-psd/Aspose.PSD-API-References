---
title: LyidResource Class
type: docs
weight: 660
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Initializes a new instance of the [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) class.<br/>            With custom or unknown value |
| [LyidResource(id)](#LyidResource_id_2) | Initializes a new instance of the [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) class. |
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
| value | int | r | Gets the value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves to the specified stream container. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Initializes a new instance of the [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) class.<br/>            With custom or unknown value

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Initializes a new instance of the [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| id | int | The identifier of layer. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |

