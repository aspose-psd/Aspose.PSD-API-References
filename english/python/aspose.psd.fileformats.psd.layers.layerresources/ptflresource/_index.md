---
title: PtFlResource Class
type: docs
weight: 810
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_1) | Initializes a new instance of the [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| align_with_layer | bool | r/w | Gets or sets a value indicating whether [align with layer]. |
| is_linked_with_layer | bool | r/w | Gets or sets a value indicating whether this instance is linked with layer. |
| key | int | r | Gets the layer resource key. |
| length | int | r | Gets the layer resource length in bytes. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Gets or sets the offset. |
| pattern_id | string | r/w | Gets or sets the pattern identifier. |
| pattern_name | string | r/w | Gets or sets the name of the pattern. |
| psd_version | int | r | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| scale | double | r/w | Gets or sets the scale. |
| signature | int | r | Gets the layer resource signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the resource to the specified stream container. |


### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_1}


```
 PtFlResource(pattern_name, pattern_id) 
```

Initializes a new instance of the [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pattern_name | string | Name of the pattern. |
| pattern_id | string | The pattern identifier. |

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

