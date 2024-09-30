---
title: PlLdResource Class
type: docs
weight: 770
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.<br/>            It was replaced by SoLdResource in the Adobe® Photoshop® CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.8.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| TYPE_TOOL_KEY [static] | int | r | The type tool info key. |
| anti_alias_policy | int | r/w | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| bottom | double | r/w | Gets or sets the bottom location of the placed layer in the PSD image. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Gets or sets the bounds of the placed layer in the PSD file. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Gets or sets the measure unit of the horizontal mesh points. |
| horizontal_mesh_points | double | r/w | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| is_custom | bool | r/w | Gets or sets a value indicating whether this instance warp style is custom.<br/>            If true it contains mesh points. If set to false it erases mesh points. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Gets or sets the warp items. |
| key | int | r | Gets the PlLd resource key. |
| left | double | r/w | Gets or sets the left location of the placed layer in the PSD file. |
| length | int | r | Gets the PlLd resource length in bytes. |
| page_number | int | r/w | Gets or sets the page number of the placed layer in the PSD file. |
| perspective | double | r/w | Gets or sets the perspective value of the placed layer in the PSD file. |
| perspective_other | double | r/w | Gets or sets the perspective other value of the placed layer in the PSD file. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Gets or sets the type of the placed layer in the PSD file. |
| psd_version | int | r | Gets the minimal psd version required for the PlLd resource. 0 indicates no restrictions. |
| right | double | r/w | Gets or sets the right location of the placed layer in the PSD file. |
| signature | int | r | Gets the PlLd resource signature. |
| top | double | r/w | Gets or sets the top location of the placed layer in the PSD image. |
| total_pages | int | r/w | Gets or sets the total pages of the placed layer in the PSD file. |
| transform_matrix | double | r/w | Gets or sets the transform matrix of the placed layer in the PSD file. |
| u_order | int | r/w | Gets or sets the U order value of the placed layer in the PSD file. |
| unique_id | Guid | r/w | Gets or sets the global unique identifier of the placed layer in the PSD image. |
| v_order | int | r/w | Gets or sets the V order value of the placed layer in the PSD file. |
| value | double | r/w | Gets or sets the warp value of the placed layer in the PSD image. |
| version | int | r | Gets the version of the placed layer in the PSD file, usually 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Gets or sets the measure unit of the vertical mesh points. |
| vertical_mesh_points | double | r/w | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the PlLD resource to the specified stream container. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the PlLD resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

