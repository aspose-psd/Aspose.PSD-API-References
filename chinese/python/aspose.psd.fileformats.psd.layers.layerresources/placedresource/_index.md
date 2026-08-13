---
title: "PlacedResource 类"
type: docs
weight: 830
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| anti_alias_policy | int | 读/写 | 获取或设置 PSD 图像中已放置图层的抗锯齿策略。 |
| 底部 | double | 读/写 | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 文件中已放置图层的边界。 |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置水平网格点的度量单位。 |
| horizontal_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| is_custom | bool | 读/写 | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。<br/>            如果为 true，则包含网格点；如果设置为 false，则会删除网格点。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 获取或设置扭曲项。 |
| key | int | r | 获取图层资源键。 |
| left | double | 读/写 | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| 长度 | int | r | 获取图层资源的字节长度。 |
| page_number | int | 读/写 | 获取或设置 PSD 文件中已放置图层的页码。 |
| perspective | double | 读/写 | 获取或设置 PSD 文件中已放置图层的透视值。 |
| perspective_other | double | 读/写 | 获取或设置 PSD 文件中已放置图层的其他透视值。 |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | 获取或设置 PSD 文件中已放置图层的类型。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| right | double | 读/写 | 获取或设置 PSD 文件中已放置图层的右侧位置。 |
| signature | int | r | 获取签名。 |
| top | double | 读/写 | 获取或设置 PSD 图像中已放置图层的顶部位置。 |
| total_pages | int | 读/写 | 获取或设置 PSD 文件中已放置图层的总页数。 |
| transform_matrix | double | 读/写 | 获取或设置 PSD 文件中已放置图层的变换矩阵。 |
| u_order | int | 读/写 | 获取或设置 PSD 文件中已放置图层的 U 顺序值。 |
| unique_id | Guid | 读/写 | 获取或设置 PSD 图像中已放置图层的全局唯一标识符。 |
| v_order | int | 读/写 | 获取或设置 PSD 文件的 V 顺序值。 |
| value | double | 读/写 | 获取或设置 PSD 图像中已放置图层的扭曲值。 |
| version | int | r | 获取 PSD 文件中已放置图层的版本，通常为 3。 |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置垂直网格点的度量单位。 |
| vertical_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将资源保存到指定的流容器。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将资源保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

