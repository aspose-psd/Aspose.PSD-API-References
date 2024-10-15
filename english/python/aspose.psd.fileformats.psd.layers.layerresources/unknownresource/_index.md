---
title: UnknownResource Class
type: docs
weight: 1050
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/
---

**Summary:** The unknown resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.UnknownResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [UnknownResource(signature, key)](#UnknownResource_signature_key_1) | Initializes a new instance of the [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| data | byte | r/w | Gets or sets the data. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the specified stream container. |


### Constructor: UnknownResource(signature, key) {#UnknownResource_signature_key_1}


```
 UnknownResource(signature, key) 
```

Initializes a new instance of the [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| signature | int | The signature. |
| key | int | The resource key. |

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

