---
title: LspfResource Class
type: docs
weight: 600
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class. |
| [LspfResource(data)](#LspfResource_data_2) | Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class.<br/>            With custom or unknown value |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key 1819504742 |
| is_composite_protected | bool | r/w | Gets or sets a value indicating whether this instance is composite protected. |
| is_position_protected | bool | r/w | Gets or sets a value indicating whether this instance is position protected. |
| is_transparency_protected | bool | r/w | Gets or sets a value indicating whether this instance is transparency protected. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Gets or sets the type of the lock. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class.

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class.<br/>            With custom or unknown value

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The resource data. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Initializes a new instance of the [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_transparency_protected | bool | if set to <c>true</c> [is transparency protected]. |
| is_composite_protected | bool | if set to <c>true</c> [is composite protected]. |
| is_position_protected | bool | if set to <c>true</c> [is position protected]. |

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

