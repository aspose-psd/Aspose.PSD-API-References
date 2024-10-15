---
title: ExpaResource Class
type: docs
weight: 280
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class. |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class. |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| exposure | float | r/w | Gets or sets the exposure. |
| gamma_correction | float | r/w | Gets or sets the gamma. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| offset | float | r/w | Gets or sets the offset. |
| psd_version | int | r | Gets the psd version. |
| signature | int | r | Gets the signature. |
| version | short | r | Gets the version. Default is 1 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class.

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bytes | byte | The bytes. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Initializes a new instance of the [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| exposure | float | The exposure. |
| offset | float | The offset. |
| gamma | float | The gamma. |

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

