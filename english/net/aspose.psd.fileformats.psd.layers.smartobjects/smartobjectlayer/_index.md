---
title: SmartObjectLayer
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 3310
url: /net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---
## SmartObjectLayer class

Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file. With Smart Objects, you can: Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer without losing original image data or quality because the transforms don�t affect the original data. Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized. Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time. Edit one Smart Object and automatically update all its linked instances. Apply a layer mask that�s either linked or unlinked to the Smart Object layer. Try various designs with low-resolution placeholder images that you later replace with final versions. In Adobe� Photoshop�, you can embed the contents of an image into a PSD document. More information is here: [https://helpx.adobe.com/photoshop/using/create-smart-objects.html](https://helpx.adobe.com/photoshop/using/create-smart-objects.html) A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties. The PlLd resource can be alone for PSD versions older then 10. These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename and other parameters, including the embedded file contents in the original format as a byte array.

```csharp
public class SmartObjectLayer : Layer
```

## Properties

| Name | Description |
| --- | --- |
| [Contents](contents) { get; set; } | Gets or sets the smart object layer contents. The embedded smart object contents is the embedded raw image file: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data) and its properties. The linked smart object contents is the raw content of the linked image file if it is available and its properties: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource). We do not support loading from the Adobe� Photoshop� �� Graphics Library when [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) is true. For regular link files, at first, we use [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath) to look for the file relatively to the source image path SourceImagePath, if it is not available we look at [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath), if not then we look for the link file in the same directory where our image is: SourceImagePath. |
| [ContentsBounds](contentsbounds) { get; set; } | Gets or sets the smart object content's bounds. |
| [ContentsSource](contentssource) { get; set; } | Gets or sets the smart object content's source. |
| [ContentType](contenttype) { get; } | Gets the type of the smart object layer content. The embedded smart object contents is the embedded raw image file: [`Data`](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data). The linked smart object contents is the raw contents of the linked image file if it is available: [`LiFeDataSource`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource). We do not support loading from the Adobe� Photoshop� �� Graphics Library when [`IsLibraryLink`](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) is true. For regular link files, at first, we use [`RelativePath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath) to look for the file relatively to the source image path SourceImagePath, if it is not available we look at [`FullPath`](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath), if not then we look for the link file in the same directory where our image is: SourceImagePath. |
| [SmartFilters](smartfilters) { get; } | Gets the smart filters. |
| [SmartObjectProvider](smartobjectprovider) { get; } | Gets the smart object provider. |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToLinked](converttolinked)(string) | Converts this embedded smart object to a linked smart object. |
| [DuplicateLayer](duplicatelayer)() | Creates a new smart object layer by coping this one. Notice that for embedded smart objects the embedded image is shared. If you want to copy the embedded image use [`NewSmartObjectViaCopy`](./newsmartobjectviacopy) method. |
| [EmbedLinked](embedlinked)() | Embeds the linked smart object in this layer. |
| [ExportContents](exportcontents)(string) | Exports the embedded or linked contents to a file. |
| [LoadContents](loadcontents)(LoadOptions) | Gets the embedded or linked image contents of the smart object layer. |
| [NewSmartObjectViaCopy](newsmartobjectviacopy)() | Creates a new smart object layer by coping this one. Reproduces `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` functionality of Adobe� Photoshop�. Notice that it is enabled only for embedded smart objects because the embedded image is also copied. If you want to share the embedded image use [`DuplicateLayer`](./duplicatelayer) method. |
| [RelinkToFile](relinktofile)(string) | Re-links the linked smart object to a new file. There is no need to call UpdateModifiedContent method afterwards. |
| [ReplaceContents](replacecontents)(Image) | Replaces the smart object contents embedded in the smart object layer. |
| [ReplaceContents](replacecontents)(string) | Replaces the contents with a file. There is no need to call UpdateModifiedContent method afterwards. |
| [ReplaceContents](replacecontents)(Image, ResolutionSetting) | Replaces the smart object contents embedded in the smart object layer. |
| [ReplaceContents](replacecontents)(string, ResolutionSetting) | Replaces the contents with a file. There is no need to call UpdateModifiedContent method afterwards. |
| [UpdateModifiedContent](updatemodifiedcontent)() | Updates the smart object layer image cache with the modified content. |

### See Also

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer)
* class [SmartObjectProvider](../../aspose.psd.fileformats.psd/smartobjectprovider)
* class [LinkDataSource](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../aspose.psd.fileformats.psd.layers.smartobjects)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
