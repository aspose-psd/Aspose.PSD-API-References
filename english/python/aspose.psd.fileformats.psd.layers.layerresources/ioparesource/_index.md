---
title: IopaResource Class
type: docs
weight: 400
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Initializes a new instance of the [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) class. |
| [IopaResource(data)](#IopaResource_data_2) | Initializes a new instance of the [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| fill_opacity | byte | r/w | Gets or sets the fill opacity. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Initializes a new instance of the [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) class.

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Initializes a new instance of the [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The raw byte data. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

