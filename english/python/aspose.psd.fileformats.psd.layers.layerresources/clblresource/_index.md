---
title: ClblResource Class
type: docs
weight: 120
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class. |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class. |
| [ClblResource(data)](#ClblResource_data_3) | Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class.<br/>            With custom or unknown value |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| blend_clipped_elements | bool | r/w | Gets or sets a value indicating whether [blend clipped elements]. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class.

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| blend_clipped_elements | bool | if set to <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Initializes a new instance of the [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) class.<br/>            With custom or unknown value

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The resource data. |

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

