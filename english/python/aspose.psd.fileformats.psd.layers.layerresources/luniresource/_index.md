---
title: LuniResource Class
type: docs
weight: 610
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/
---

**Summary:** Layer name resource

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LuniResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LuniResource()](#LuniResource__1) | Initializes a new instance of the [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| name | string | r/w | Gets or sets the name. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: LuniResource() {#LuniResource__1}


```
 LuniResource() 
```

Initializes a new instance of the [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) class.

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container. |
| psd_version | int | The PSD version. |

