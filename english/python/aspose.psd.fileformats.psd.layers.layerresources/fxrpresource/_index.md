---
title: FxrpResource Class
type: docs
weight: 280
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/
---

**Summary:** Class FxrpResource. The reference point of layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FxrpResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FxrpResource()](#FxrpResource__1) | Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class. |
| [FxrpResource(data)](#FxrpResource_data_2) | Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class.<br/>            With custom or unknown value |
| [FxrpResource(x, y)](#FxrpResource_x_y_3) | Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class. |
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
| x | double | r/w | Gets or sets the x of reference point |
| y | double | r/w | Gets or sets the y of reference point |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves to the specified stream container. |


### Constructor: FxrpResource() {#FxrpResource__1}


```
 FxrpResource() 
```

Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class.

### Constructor: FxrpResource(data) {#FxrpResource_data_2}


```
 FxrpResource(data) 
```

Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class.<br/>            With custom or unknown value

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The resource data. |

### Constructor: FxrpResource(x, y) {#FxrpResource_x_y_3}


```
 FxrpResource(x, y) 
```

Initializes a new instance of the [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | double | The x coordinate of reference point |
| y | double | The y coordinate of reference point |

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

