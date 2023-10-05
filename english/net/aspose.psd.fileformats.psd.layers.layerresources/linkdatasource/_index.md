---
title: Class LinkDataSource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkDataSource class. Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file
type: docs
weight: 2820
url: /net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/
---
{{< psd/tize >}}
## LinkDataSource class

Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file.

```csharp
public abstract class LinkDataSource
```

## Properties

| Name | Description |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Gets or sets a value indicating whether the PSD asset is locked. The asset locked state, for Adobe® Photoshop® СС Libraries assets. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Gets or sets the asset modified time, for Adobe® Photoshop® СС Libraries assets. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Gets or sets the child document identifier in the liFE or liFD data source of the Lnk2 / LnkE Adobe® Photoshop® resource. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Gets or sets the ID of the currently selected comp for the child document, which will be -1 if none are selected. Comps are compositions of a page layout which designers can create. Using layer comps, you can create, manage, and view multiple versions of a layout in a single Adobe® Photoshop® file. A layer comp is a snapshot of a state of the Layers panel. Layer comps save three types of layer options but this property gets the Layer Comp selection identifier for Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Gets or sets the file creator in the PSD format LnkE / Lnk2 resource. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Gets or sets the type of the embedded or external file which Adobe® Photoshop® Lnk2 / LnkE resource contains or links. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Gets or sets a value indicating whether this link data source has the file open descriptor: CompId and OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Gets a value indicating whether this PSD link data source links to the Adobe® Photoshop® СС Library item. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Gets the link data source length in bytes. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Gets the original ID of the currently selected Comp for the child document, which will be -1 if none are selected. This property gets the original layer Comp selection identifier for Smart Objects. [Layer comps in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Gets the original file name of the data source in the Adobe® Photoshop® global link resource. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Gets the Adobe® Photoshop® global link data source type that can be one of the following or none: The embedded linked file liFD that corresponds to the PSD Lnk2Resource The external linked file liFE that corresponds to the PSD LnkeResource The linked file alias liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Gets the global unique identifier of the data source in the PSD link resource. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Gets the version of the data source in the PSD LnkE / Lnk2 resource. |

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


