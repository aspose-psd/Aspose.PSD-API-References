---
title: "IPlacedLayerResource 类"
type: docs
weight: 390
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/
---

**Summary:** Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file.<br/>            Is is a markup interface used to designate PlLd, Sold and Sole resources in the Adobe® Photoshop® images.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPlacedLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| anti_alias_policy | int | 读/写 | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| 底部 | double | 读/写 | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 文件中已放置图层的边界。 |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置水平网格点的度量单位。 |
| horizontal_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| is_custom | bool | 读/写 | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。<br/>            如果为 true，则包含网格点；如果设置为 false，则会删除网格点。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 获取或设置扭曲项。 |
| left | double | 读/写 | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| page_number | int | 读/写 | 获取或设置 PSD 文件中已放置图层的页码。 |
| perspective | double | 读/写 | 获取或设置 PSD 文件中已放置图层的透视值。 |
| perspective_other | double | 读/写 | 获取或设置 PSD 文件中已放置图层的其他透视值。 |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | 获取或设置 PSD 文件中已放置图层的类型。 |
| right | double | 读/写 | 获取或设置 PSD 文件中已放置图层的右侧位置。 |
| top | double | 读/写 | 获取或设置 PSD 图像中已放置图层的顶部位置。 |
| total_pages | int | 读/写 | 获取或设置 PSD 文件中已放置图层的总页数。 |
| transform_matrix | double | 读/写 | 获取或设置 PSD 文件中已放置图层的变换矩阵。 |
| u_order | int | 读/写 | 获取或设置 PSD 文件中已放置图层的 U 顺序值。 |
| unique_id | Guid | 读/写 | 获取或设置 PSD 图像中已放置图层的全局唯一标识符或智能对象。 |
| v_order | int | 读/写 | 获取或设置 PSD 文件的 V 顺序值。 |
| value | double | 读/写 | 获取或设置 PSD 图像中已放置图层的扭曲值。 |
| version | int | r | 获取 PSD 文件中已放置图层的版本，通常为 3-5。 |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置垂直网格点的度量单位。 |
| vertical_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |


