---
title: "类 LinkDataSource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource 类。定义了 LinkDataSource 类，该类包含有关 PSD 文件中链接文件或资产的信息。"
type: docs
weight: 2990
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

定义 LinkDataSource 类，包含有关 PSD 文件中链接文件或资产的信息。

```csharp
public abstract class LinkDataSource
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | 获取或设置指示 PSD 资产是否被锁定的值。资产锁定状态，适用于 Adobe® Photoshop® СС Libraries 资产。 |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | 获取或设置资产的修改时间，适用于 Adobe® Photoshop® СС Libraries 资产。 |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | 获取或设置 Lnk2 / LnkE Adobe® Photoshop® 资源的 liFE 或 liFD 数据源中的子文档标识符。 |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | 获取或设置子文档当前选定的 comp 的 ID，如果未选中则为 -1。Comp 是设计师可以创建的页面布局的组合。使用图层 comp，您可以在单个 Adobe® Photoshop® 文件中创建、管理和查看布局的多个版本。图层 comp 是图层面板状态的快照。图层 comp 保存三种图层选项，但此属性获取智能对象的图层 Comp 选择标识符。[Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | 获取或设置 PSD 格式 LnkE / Lnk2 资源中的文件创建者。 |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | 获取或设置 Adobe® Photoshop® Lnk2 / LnkE 资源包含或链接的嵌入或外部文件的类型。 |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | 获取或设置一个值，指示此链接数据源是否具有文件打开描述符：CompId 和 OriginalCompId。 |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | 获取一个值，指示此 PSD 链接数据源是否链接到 Adobe® Photoshop® СС Library 项目。 |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | 获取链接数据源的字节长度。 |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | 获取子文档当前选定的 Comp 的原始 ID，如果未选中则为 -1。此属性获取智能对象的原始图层 Comp 选择标识符。[Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | 获取 Adobe® Photoshop® 全局链接资源中数据源的原始文件名。 |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | 获取 Adobe® Photoshop® 全局链接数据源类型，该类型可以是以下之一或无：对应于 PSD Lnk2Resource 的嵌入链接文件 liFD，对应于 PSD LnkeResource 的外部链接文件 liFE，链接文件别名 liFA。 |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | 获取 PSD 链接资源中数据源的全局唯一标识符。 |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | 获取 PSD LnkE / Lnk2 资源中数据源的版本。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


