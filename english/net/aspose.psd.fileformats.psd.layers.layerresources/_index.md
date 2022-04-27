---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Aspose.PSD for .NET API Reference
description: The namespace contains PSD file format entities contained in layers.
type: docs
weight: 260
url: /net/aspose.psd.fileformats.psd.layers.layerresources/
---
The namespace contains PSD file format entities contained in layers.

## Classes

| Class | Description |
| --- | --- |
| abstract class [AdjustmentLayerResource](./adjustmentlayerresource) | Base Class for adjustments layer resources |
| class [BlncResource](./blncresource) | BlncResource class is a resource of Color Adjustment Layer. |
| class [BlwhResource](./blwhresource) | BlwhResource class is a resource of Black and White Adjustment Layer. |
| abstract class [BooleanResource](./booleanresource) | Class BooleanResource. It's pseudo resource. Photoshop haven't it |
| class [BritResource](./britresource) | Class BritResource. Resource of Brightness/Contrast Adjustment Layer |
| class [CgEdResource](./cgedresource) | Class CgEdResource. Content Generator Extra Data (Photoshop CS5) |
| class [ClassID](./classid) | The PSD Class ID object. |
| class [ClblResource](./clblresource) | Class ClblResource. This resource contains information about blending of clipped element. |
| class [CmlsResource](./cmlsresource) | Class CmlsResource. |
| class [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl |
| class [CurvesContinuousManager](./curvescontinuousmanager) | Manager for Curves Adjustment Layer that manipulates curves |
| class [CurvesDiscreteManager](./curvesdiscretemanager) | Manager for Curves Adjustment Layer that manipulates pixels' map |
| abstract class [CurvesManager](./curvesmanager) | Base Class to manage CurvResource |
| class [CurvResource](./curvresource) | Class CurvResource. Resource of Curves Adjustment Layer 1 byte - 0 if use curves, 1 if used pixels on map if 0 then: 2 bytes - short. Default is 1 4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example 2 bytes - short points count 4 bytes * count of point - points of curve 2 short: first position, second height 4 bytes - word "Crv " 2 bytes - short default is 4 for Curves 4 bytes - int. Default is 1 4 bytes - point count 4 bytes * point count - points of curve 2 short: first position, second height 0-4 bytes - Leading to be fold for four if 1 then: 2 bytes - short. Default is 1 4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example 256 * count of changed channels - ordered values of channel in range 0 - 255 4 bytes - word "Crv " 2 bytes - short. Default is 3 for pixels on map 4 bytes - int Channel count (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255 |
| class [CustResource](./custresource) | Class CustResource. This resource contains information about blending of clipped element. |
| class [ExpaResource](./exparesource) | Class ExpaResource. Resource of Exposure Adjustment Layer |
| abstract class [FillLayerResource](./filllayerresource) | Base Class for fill layer resources |
| class [FilterEffectMaskData](./filtereffectmaskdata) | The filter mask data class. |
| class [FXidResource](./fxidresource) | The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter. |
| class [FxrpResource](./fxrpresource) | Class FxrpResource. The reference point of layer |
| class [GdFlResource](./gdflresource) | Class GdFlResource. This resource contains information about blending of clipped element. |
| class [Hue2Resource](./hue2resource) | Class Hue2Resource. Resource of Exposure Adjustment Layer |
| class [InfxResource](./infxresource) | Class InfxResource. This resource contains information about blending of clipped element. |
| class [IopaResource](./ioparesource) | Class IopaResource. This resource contains information about the fill opacity property from the layer style form |
| class [KnkoResource](./knkoresource) | Class KnkoResource. This resource contains information about blending of clipped element. |
| class [LayerSectionResource](./layersectionresource) | The layer section resource. |
| class [LclrResource](./lclrresource) | Class LclrResource. This resource contains information about color of layer in layers' list is PS. It's only |
| class [LevelChannel](./levelchannel) | Class for working with channels in Levels Adjustment Layer |
| class [LevlResource](./levlresource) | Class LevlResource. Resource of Exposure Adjustment Layer |
| class [Lfx2Resource](./lfx2resource) | Lfx2 resource (effects resource) |
| class [LiFdDataSource](./lifddatasource) | Defines the liFD data source class in PSD File that contains information about an embedded file. This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files |
| class [LiFeDataSource](./lifedatasource) | Defines the LnkeDataSource class that contains information about external linked file. This is part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files |
| abstract class [LinkDataSource](./linkdatasource) | Defines the LinkDataSource class that contains information about a linked file or an asset in the PSD file. |
| abstract class [LinkResource](./linkresource) | Defines the LinkResource class that contains information about linked or embedded files in the PSD format image. The link resource may contain several [`LinkDataSource`](aspose.psd.fileformats.psd.layers.layerresources/linkdatasource) instances which can be accessed by indexers in any derived class. |
| class [Lnk2Resource](./lnk2resource) | Defines the class which contains information about embedded files in the PSD format image. The link resource may contain several [`LiFdDataSource`](aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) instances which can be accessed by the indexer. |
| class [Lnk3Resource](./lnk3resource) | Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image. The link resource may contain several [`LiFdDataSource`](aspose.psd.fileformats.psd.layers.layerresources/lifddatasource) instances which can be accessed by indexer. |
| class [LnkeResource](./lnkeresource) | Defines the LnkeResource class that contains information about external linked files or assets in the PSD format image. The link resource may contain several [`LiFeDataSource`](aspose.psd.fileformats.psd.layers.layerresources/lifedatasource) instances which can be accessed by indexer. This is a part of PSD File Format Manipulation API that helps to modify Adobe® Photoshop® files programmatically |
| class [LnsrResource](./lnsrresource) | Class lnsrResource. |
| class [Lr16Resource](./lr16resource) | The lr32 resource. |
| class [Lr32Resource](./lr32resource) | The lr32 resource. |
| class [LspfResource](./lspfresource) | Layer protected settings |
| class [LuniResource](./luniresource) | Layer name resource |
| class [LyidResource](./lyidresource) | Class LyidResource. |
| class [MixrResource](./mixrresource) | Class MixrResource. Resource of Channel Mixer Adjustment Layer |
| class [NvrtResource](./nvrtresource) | Class NvrtResource. Resource of Invert Adjustment Layer. |
| abstract class [OSTypeStructure](./ostypestructure) | Represents the OS type structure. |
| static class [OSTypeStructuresRegistry](./ostypestructuresregistry) | Represents the [`OSTypeStructure`](aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resources registry. |
| class [PattResource](./pattresource) | Class PattResource. Resource with pattern data |
| class [PattResourceData](./pattresourcedata) | The class to store the pattern data for [`PattResource`](aspose.psd.fileformats.psd.layers.layerresources/pattresource) resource. |
| abstract class [PhflResource](./phflresource) | Class PhflResource. Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 Density 1 Preserve Luminosity |
| class [PhflResourceVersion2](./phflresourceversion2) | Class PhflResource. Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 Density 1 Preserve Luminosity |
| class [PhflResourceVersion3](./phflresourceversion3) | Class PhflResource. Resource of Exposure Adjustment Layer 2 Version ( = 3 ) or ( = 2 ) 12 4 bytes each for XYZ color(Only in Version 3) 10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2) 4 Density 1 Preserve Luminosity |
| abstract class [PlacedResource](./placedresource) | Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file. Is is used to support smart object layers in the Adobe® Photoshop® images. |
| class [PlLdResource](./plldresource) | Defines the PlLdResource class that contains information about a placed layer in the PSD file. Is is used to support smart object layers in the Adobe® Photoshop® images. It was replaced by SoLdResource in the Adobe® Photoshop® CS3 |
| class [PtFlResource](./ptflresource) | Class PtFlResource. Contains Pattern Fill Layer Data. |
| class [ShmdResource](./shmdresource) | Class ShmdResource. Metadata settings |
| abstract class [SmartObjectResource](./smartobjectresource) | Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file. Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe® Photoshop® images. |
| class [SmartResourceCreator](./smartresourcecreator) | Defines the SmartResourceCreator class that can create PlLd, SoLd and SoLe resources. Is is used to support smart object layers in the Adobe® Photoshop® images. |
| class [SoCoResource](./socoresource) | Class SoCoResource. This resource contains information about Color Fill Layers |
| class [SoLdResource](./soldresource) | Defines the SoLdResource class that contains information about a smart object layer in a PSD file. Is is used to support smart object layers in the Adobe® Photoshop® images. |
| class [SoLeResource](./soleresource) | Defines the SoLeResource class that contains information about a smart object layer in a PSD file. Is is used to support smart object layers with external file links in the Adobe® Photoshop® images. |
| class [Txt2Resource](./txt2resource) | Txt2 resource class |
| class [TypeToolFontInfo](./typetoolfontinfo) | Contains information about type tool font. |
| class [TypeToolInfo6Resource](./typetoolinfo6resource) | The type tool information. For PSD version higher or equal to the 6.0. |
| class [TypeToolInfoResource](./typetoolinforesource) | The type tool information. For PSD version lower than 6.0. |
| class [TypeToolLineInfo](./typetoollineinfo) | Type tool line info. |
| class [TypeToolStyleInfo](./typetoolstyleinfo) | Type tool style information. |
| class [UnknownResource](./unknownresource) | The unknown resource. |
| abstract class [VectorPathDataResource](./vectorpathdataresource) | Class VectorPathDataResource. This resource contains information about vector layer mask |
| class [VibAResource](./vibaresource) | VibA Resource. |
| class [VmskResource](./vmskresource) | Class VmskResource. This resource contains information about vector layer mask |
| class [VogkResource](./vogkresource) | The Vector Origination Data resource. |
| class [VsmsResource](./vsmsresource) | Class VsmsResource. This resource contains information about vector layer mask |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IOSTypeStructureLoader](./iostypestructureloader) | The [`OSTypeStructure`](aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) resource loader. |
| interface [IPlacedLayerResource](./iplacedlayerresource) | Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file. Is is a markup interface used to designate PlLd, Sold and Sole resources in the Adobe® Photoshop® images. Is is used to support smart object layers in the Adobe® Photoshop® images. |
| interface [ISmartObjectLayerResource](./ismartobjectlayerresource) | Defines the ISmartObjectLayerResource interface that contains information about a smart object layer resource in the PSD file. Is is also a markup interface used to designate both Sold and Sole resources in the Adobe® Photoshop® images. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [LayerLockType](./layerlocktype) | Layer lock options |
| enum [LayerSectionSubtype](./layersectionsubtype) | The section subtype |
| enum [LayerSectionType](./layersectiontype) | The layer section type |
| enum [LinkDataSourceType](./linkdatasourcetype) | Defines the LinkDataSourceType enumeration for the data sources in the PSD link resource. |
| enum [LnsrResourceType](./lnsrresourcetype) | Discovered Possible Lnsr Resource Types |
| enum [PlacedLayerType](./placedlayertype) | Defines the PlacedLayerType enumeration for the placed layer PlLd resource. |
| enum [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Possible colors of Sheet color setting. It's UI decorative color of layer in layers' list in PS |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
