---
title: "LiFeDataSource 类"
type: docs
weight: 520
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---

**Summary:** Defines the LnkeDataSource class that contains information about external linked file.<br/>            This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LiFeDataSource

**Inheritance:** LinkDataSource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LiFeDataSource()](#LiFeDataSource__1) | 初始化 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 类的新实例。 |
| [LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator)](#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2) | 初始化 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_stock_id | 字符串 | 读/写 | 获取或设置图形库 AdobeStockId，适用于 Adobe® Photoshop® CC 库。 |
| adobe_stock_license_state | 字符串 | r | 获取 Adobe® Photoshop® CC 库中（如果可用）Adobe Stock 许可证的状态。 |
| asset_locked_state | bool | 读/写 | 获取或设置指示 PSD 资产是否被锁定的值。<br/>            资产锁定状态，适用于 Adobe® Photoshop® СС 库资产。 |
| asset_mod_time | double | 读/写 | 获取或设置资产的修改时间，适用于 Adobe® Photoshop® СС Libraries 资产。 |
| child_doc_id | 字符串 | 读/写 | 获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源的 liFE 或 liFD 数据源中的子文档标识符。 |
| comp_id | int | 读/写 | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。<br/>            Comp 是设计师可以创建的页面布局的组合。使用图层 comp，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本<br/>            图层 comp 是图层面板状态的快照。图层 comp 保存三种图层选项，但此属性获取智能对象的图层 comp 选择标识符。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">智能对象中的图层组合</see> |
| date | datetime | 读/写 | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的最后写入日期和时间。 |
| element_name | 字符串 | 读/写 | 获取或设置 Adobe® Photoshop® CC Libraries 的图形库元素名称。 |
| element_ref | 字符串 | 读/写 | 获取或设置 Adobe® Photoshop® CC Libraries 的图形库元素引用。 |
| file_creator | 字符串 | 读/写 | 获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。 |
| file_name | 字符串 | 读/写 | 获取或设置 PSD 链接资源中外部或嵌入文件的名称。 |
| file_size | long | 读/写 | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的大小。 |
| file_type | 字符串 | 读/写 | 获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源包含或链接的嵌入或外部文件的类型。 |
| full_path | 字符串 | 读/写 | 获取或设置 PSD LnkE 资源的 LiFE 数据源中外部文件的完整路径。 |
| has_file_open_descriptor | bool | 读/写 | 获取或设置一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。 |
| is_library_link | bool | r | 获取一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® СС Library 项目。 |
| 长度 | long | r | 获取链接数据源的字节长度。 |
| original_comp_id | int | r | 获取当前为子文档选择的原始 Comp ID，如果未选择则为 -1。<br/>            此属性获取 Smart Objects 的原始图层 Comp 选择标识符。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| original_file_name | 字符串 | r | 获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。 |
| relative_path | 字符串 | 读/写 | 获取或设置 PSD LnkE 资源中 LiFE 数据源的外部文件相对路径。 |
| type | [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype) | r | 获取 Adobe® Photoshop® 全局链接数据源类型，该类型可以是以下之一或无：<br/>            嵌入的链接文件 liFD，对应于 PSD Lnk2Resource<br/>            外部链接文件 liFE，对应于 PSD LnkeResource<br/>            链接文件别名 liFA |
| unique_id | Guid | r | 获取 PSD 链接资源中数据源的全局唯一标识符。 |
| version | int | r | 获取 PSD LnkE / Lnk2 资源中数据源的版本。 |


### Constructor: LiFeDataSource() {#LiFeDataSource__1}


```
 LiFeDataSource() 
```

初始化 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 类的新实例。

### Constructor: LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) {#LiFeDataSource_version_unique_id_original_file_name_file_type_file_creator_2}


```
 LiFeDataSource(version, unique_id, original_file_name, file_type, file_creator) 
```

初始化 [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| version | int | 版本。 |
| unique_id | Guid | 唯一标识符。 |
| original_file_name | 字符串 | 原始文件的名称。 |
| file_type | 字符串 | 文件类型。 |
| file_creator | 字符串 | 文件创建者。 |

