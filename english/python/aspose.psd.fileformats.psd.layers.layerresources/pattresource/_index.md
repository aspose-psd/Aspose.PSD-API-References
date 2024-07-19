---
title: PattResource Class
type: docs
weight: 720
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResource()](#PattResource__1) | Initializes a new instance of the [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) class. |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Initializes a new instance of the [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The 'Patt' type tool info key for 8-bits. |
| TYPE_TOOL_KEY2 [static] | int | r | The 'Pat2' type tool info key for 16-bits. |
| TYPE_TOOL_KEY3 [static] | int | r | The 'Pat3' type tool info key for 32-bits. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Gets or sets the patterns data; |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource block data. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Initializes a new instance of the [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) class.

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Initializes a new instance of the [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | int | The resource type key. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | The patterns data. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the resource block data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

