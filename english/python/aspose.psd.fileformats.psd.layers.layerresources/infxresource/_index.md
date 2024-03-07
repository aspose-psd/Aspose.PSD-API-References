---
title: InfxResource Class
type: docs
weight: 380
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Summary:** Class InfxResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.InfxResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [InfxResource()](#InfxResource__1) | Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class. |
| [InfxResource(blend_interior_elements)](#InfxResource_blend_interior_elements_2) | Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class. |
| [InfxResource(data)](#InfxResource_data_3) | Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class.<br/>            With custom or unknown value |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| blend_interior_elements | bool | r/w | Gets or sets a value indicating whether [blend interior elements]. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: InfxResource() {#InfxResource__1}


```
 InfxResource() 
```

Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class.

### Constructor: InfxResource(blend_interior_elements) {#InfxResource_blend_interior_elements_2}


```
 InfxResource(blend_interior_elements) 
```

Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| blend_interior_elements | bool | if set to <c>true</c> [blend interior elements]. |

### Constructor: InfxResource(data) {#InfxResource_data_3}


```
 InfxResource(data) 
```

Initializes a new instance of the [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) class.<br/>            With custom or unknown value

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

