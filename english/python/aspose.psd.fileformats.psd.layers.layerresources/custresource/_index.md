---
title: CustResource Class
type: docs
weight: 230
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustResource()](#CustResource__1) | Initializes a new instance of the [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) class. |
| [CustResource(data)](#CustResource_data_2) | Initializes a new instance of the [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| key | int | r | Gets the layer resource key. |
| layer_created_date_time | datetime | r/w | Gets or sets the layer created date. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Initializes a new instance of the [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) class.

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Initializes a new instance of the [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The data of the resource. |

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

