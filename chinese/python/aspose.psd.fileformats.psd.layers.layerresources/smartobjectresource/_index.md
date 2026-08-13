---
title: "SmartObjectResource 类"
type: docs
weight: 900
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | 该 PSB 特定的资源签名。 |
| RESOURCE_SIGNATURE [static] | int | r | 该通用资源签名。 |
| anti_alias_policy | int | 读/写 | 获取或设置 PSD 图像中智能对象图层数据的抗锯齿策略。 |
| 底部 | double | 读/写 | 获取或设置 PSD 图像中已放置图层的底部位置。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置 PSD 文件中已放置图层的边界。 |
| comp | int | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的 comp 值。<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">智能对象中的图层组合</see> |
| comp_id | int | 读/写 | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。<br/>            Comp 是设计师可以创建的页面布局的组合。使用图层组合，您可以在单个 Adobe Photoshop 文件中创建、管理和查看布局的多个版本。图层组合是图层面板状态的快照。图层组合保存三种图层选项，但此属性获取 PSD 文件中智能对象图层的图层组合选择标识符。<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">智能对象中的图层组合</see> |
| crop | int | 读/写 | 获取或设置 PSD 图像中智能对象图层数据的裁剪。 |
| duration_denominator | int | 读/写 | 获取或设置持续时间的分母。 |
| duration_numerator | int | 读/写 | 获取或设置持续时间的分子。 |
| frame_count | int | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的帧计数。 |
| frame_step_denominator | int | 读/写 | 获取或设置帧步长的分母。 |
| frame_step_numerator | int | 读/写 | 获取或设置帧步长的分子。 |
| height | double | 读/写 | 获取或设置高度。 |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置水平网格点的度量单位。 |
| horizontal_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| is_custom | bool | 读/写 | 获取或设置一个值，指示此实例的扭曲样式是否为自定义。<br/>            如果为 true，则包含网格点；如果设置为 false，则会删除网格点。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 获取或设置 PSD 文件中智能对象图层数据的描述符项。 |
| key | int | r | 获取图层资源键。 |
| left | double | 读/写 | 获取或设置 PSD 文件中已放置图层的左侧位置。 |
| 长度 | int | r | 获取智能对象资源的字节长度。 |
| non_affine_transform_matrix | double | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的非仿射变换矩阵。 |
| original_comp_id | int | r | 获取当前为子文档选中的 Comp 的原始 ID，如果未选中则为 -1。<br/>            此属性获取 PSD 文件中智能对象图层的原始图层 Comp 选择标识符。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">智能对象中的图层 Comp</see> |
| page_number | int | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的页码。 |
| perspective | double | 读/写 | 获取或设置 PSD 文件中已放置图层的透视值。 |
| perspective_other | double | 读/写 | 获取或设置 PSD 文件中已放置图层的其他透视值。 |
| placed_id | Guid | 读/写 | 获取或设置此智能对象图层数据在 PSD 图像中的唯一标识符。 |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | 获取或设置 PSD 文件中智能对象图层数据的类型。 |
| psd_version | int | r | 获取图层资源所需的最低 psd 版本。0 表示没有限制。 |
| resolution | double | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的分辨率。 |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置 PSD 文件中智能对象图层数据的分辨率测量单位。 |
| right | double | 读/写 | 获取或设置 PSD 文件中已放置图层的右侧位置。 |
| signature | int | r | 获取签名。 |
| top | double | 读/写 | 获取或设置 PSD 图像中已放置图层的顶部位置。 |
| total_pages | int | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的总页数。 |
| transform_matrix | double | 读/写 | 获取或设置 PSD 文件中智能对象图层数据的变换矩阵。 |
| u_order | int | 读/写 | 获取或设置 PSD 文件中已放置图层的 U 顺序值。 |
| unique_id | Guid | r/w | 获取或设置 PSD 图像中智能对象图层数据的全局唯一标识符 [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/)。 |
| v_order | int | 读/写 | 获取或设置 PSD 文件的 V 顺序值。 |
| value | double | 读/写 | 获取或设置 PSD 图像中已放置图层的扭曲值。 |
| version | int | r | 获取 PSD 文件中已放置图层的版本，通常为 3。 |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 获取或设置垂直网格点的度量单位。 |
| vertical_mesh_points | double | 读/写 | 获取或设置 PSD 文件中已放置图层的水平网格点。 |
| width | double | 读/写 | 获取或设置宽度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 将智能对象资源保存到指定的流容器中。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

将智能对象资源保存到指定的流容器中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 要保存到的流容器。 |
| psd_version | int | PSD 版本。 |

