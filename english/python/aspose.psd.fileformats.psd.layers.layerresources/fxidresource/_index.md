---
title: FXidResource Class
type: docs
weight: 250
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---

**Summary:** The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FXidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.2.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FXidResource(key, version, filter_effect_masks)](#FXidResource_key_version_filter_effect_masks_1) | Initializes a new instance of the [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| F_EID_TYPE_TOOL_KEY [static] | int | r | The type tool info key FEid. |
| F_XID_TYPE_TOOL_KEY [static] | int | r | The type tool info key FXid. |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | r | Gets the filter effect masks. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| signature | int | r | Gets the layer resource signature. |
| version | int | r | Gets the version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: FXidResource(key, version, filter_effect_masks) {#FXidResource_key_version_filter_effect_masks_1}


```
 FXidResource(key, version, filter_effect_masks) 
```

Initializes a new instance of the [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | int | The resource key. |
| version | int | The version. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | The filter effect masks. |

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

