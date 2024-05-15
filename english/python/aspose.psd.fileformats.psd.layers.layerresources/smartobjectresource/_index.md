---
title: SmartObjectResource Class
type: docs
weight: 850
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.4.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | The PSB-specific resource signature. |
| RESOURCE_SIGNATURE [static] | int | r | The common resource signature. |
| anti_alias_policy | int | r/w | Gets or sets the anti alias policy of the smart object layer data in the PSD image. |
| bottom | double | r/w | Gets or sets the bottom location of the placed layer in the PSD image. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Gets or sets the bounds of the placed layer in the PSD file. |
| comp | int | r/w | Gets or sets the comp value of the smart object layer data in the PSD file.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| comp_id | int | r/w | Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected.<br/>            Comps are compositions of a page layout which designers can create. Using layer comps, you can create, manage, and view multiple versions<br/>            of a layout in a single Adobe® Photoshop® file. A layer comp is a snapshot of a state of the Layers panel. Layer comps save three types of layer options but<br/>            this property gets the Layer Comp selection identifier for he smart object layer in the PSD file.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| crop | int | r/w | Gets or sets the crop of the smart object layer data in the PSD image. |
| duration_denominator | int | r/w | Gets or sets the duration denominator. |
| duration_numerator | int | r/w | Gets or sets the duration numerator. |
| frame_count | int | r/w | Gets or sets the frame count of the smart object layer data in the PSD file. |
| frame_step_denominator | int | r/w | Gets or sets the frame step denominator. |
| frame_step_numerator | int | r/w | Gets or sets the frame step numerator. |
| height | double | r/w | Gets or sets the height. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Gets or sets the measure unit of the horizontal mesh points. |
| horizontal_mesh_points | double | r/w | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| is_custom | bool | r/w | Gets or sets a value indicating whether this instance warp style is custom.<br/>            If true it contains mesh points. If set to false it erases mesh points. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Gets or sets the descriptor items of the smart object layer data in the PSD file. |
| key | int | r | Gets the layer resource key. |
| left | double | r/w | Gets or sets the left location of the placed layer in the PSD file. |
| length | int | r | Gets the smart object resource length in bytes. |
| non_affine_transform_matrix | double | r/w | Gets or sets the non affine transform matrix of the smart object layer data in the PSD file. |
| original_comp_id | int | r | Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected.<br/>            This property gets the original layer Comp selection identifier for he smart object layer in the PSD file.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| page_number | int | r/w | Gets or sets the page number of the smart object layer data in the PSD file. |
| perspective | double | r/w | Gets or sets the perspective value of the placed layer in the PSD file. |
| perspective_other | double | r/w | Gets or sets the perspective other value of the placed layer in the PSD file. |
| placed_id | Guid | r/w | Gets or sets the unique identifier of this smart object layer data in the PSD image. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Gets or sets the type of the smart object layer data in the PSD file. |
| psd_version | int | r | Gets the minimal psd version required for the smart object resource. 0 indicates no restrictions. |
| resolution | double | r/w | Gets or sets the resolution of the smart object layer data in the PSD file. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Gets or sets the resolution measure unit of the smart object layer data in the PSD file. |
| right | double | r/w | Gets or sets the right location of the placed layer in the PSD file. |
| signature | int | r | Gets the smart object resource signature. |
| top | double | r/w | Gets or sets the top location of the placed layer in the PSD image. |
| total_pages | int | r/w | Gets or sets the total pages number of the smart object layer data in the PSD file. |
| transform_matrix | double | r/w | Gets or sets the transform matrix of the smart object layer data in the PSD file. |
| u_order | int | r/w | Gets or sets the U order value of the placed layer in the PSD file. |
| unique_id | Guid | r/w | Gets or sets the global unique identifier of the smart object layer data [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) in the PSD image. |
| v_order | int | r/w | Gets or sets the V order value of the placed layer in the PSD file. |
| value | double | r/w | Gets or sets the warp value of the placed layer in the PSD image. |
| version | int | r | Gets the version of the placed layer in the PSD file, usually 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Gets or sets the measure unit of the vertical mesh points. |
| vertical_mesh_points | double | r/w | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| width | double | r/w | Gets or sets the width. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Saves the smart object resource to the specified stream container. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Saves the smart object resource to the specified stream container.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | The stream container to save to. |
| psd_version | int | The PSD version. |

