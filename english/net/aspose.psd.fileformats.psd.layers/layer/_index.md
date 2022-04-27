---
title: Layer
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 1990
url: /net/aspose.psd.fileformats.psd.layers/layer/
---
## Layer class

The psd layer.

```csharp
public class Layer : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [Layer](layer)() | Initializes a new instance of the [`Layer`](../layer) class. Constructor for lazy initialization. |
| [Layer](layer)(Stream) | Initializes a new instance of the [`Layer`](../layer) class. |
| [Layer](layer)(RasterImage, bool) | Initializes a new instance of the [`Layer`](../layer) class. |
| [Layer](layer)(Rectangle, byte[], byte[], byte[], string) | Initializes a new instance of the [`Layer`](../layer) class from byte arrays. |

## Properties

| Name | Description |
| --- | --- |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [BlendingOptions](blendingoptions) { get; } | Gets the blending options. |
| virtual [BlendModeKey](blendmodekey) { get; set; } | Gets or sets the blend mode key. |
| [BlendModeSignature](blendmodesignature) { get; } | Gets the blend mode signature. |
| [Bottom](bottom) { get; set; } | Gets or sets the bottom layer position. |
| [ChannelInformation](channelinformation) { get; set; } | Gets or sets the channel information. |
| [ChannelsCount](channelscount) { get; } | Gets the layer's channels count. |
| [Clipping](clipping) { get; set; } | Gets or sets the layer clipping. 0 = base, 1 = non-base. |
| [DisplayName](displayname) { get; set; } | Gets or sets the display name of the layer. |
| [ExtraLength](extralength) { get; } | Gets the layer extra information length in bytes. |
| [Filler](filler) { get; set; } | Gets or sets the layer filler. |
| [FillOpacity](fillopacity) { get; set; } | Gets or sets the fill opacity. |
| [Flags](flags) { get; set; } | Gets or sets the layer flags. bit 0 = transparency protected; bit 1 = visible; bit 2 = obsolete; bit 3 = 1 for Photoshop 5.0 and later, tells if bit 4 has useful information; bit 4 = pixel data irrelevant to appearance of document. |
| override [HasAlpha](hasalpha) { get; } | Gets a value indicating whether this instance has alpha. |
| override [Height](height) { get; } | Gets the image height. |
| [IsVisible](isvisible) { get; set; } | Gets or sets a value indicating whether the layer is visible |
| virtual [IsVisibleInGroup](isvisibleingroup) { get; } | Gets a value indicating whether this instance is visible in group(If layer is not in group it means root group). |
| [LayerBlendingRangesData](layerblendingrangesdata) { get; set; } | Gets or sets the layer blending ranges data. |
| [LayerCreationDateTime](layercreationdatetime) { get; set; } | Gets or sets the layer creation date time. |
| [LayerLock](layerlock) { get; set; } | Gets or sets the layer lock. Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag. To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](layermaskdata) { get; set; } | Gets or sets the layer mask data. |
| [LayerOptions](layeroptions) { get; } | Gets the layer options. |
| [Left](left) { get; set; } | Gets or sets the left layer position. |
| [Length](length) { get; } | Gets the overall layer length in bytes. |
| [Name](name) { get; set; } | Gets or sets the layer name. |
| [Opacity](opacity) { get; set; } | Gets or sets the layer opacity. 0 = transparent, 255 = opaque. |
| [Resources](resources) { get; set; } | Gets or sets the layer resources. |
| [Right](right) { get; set; } | Gets or sets the right layer position. |
| [SheetColorHighlight](sheetcolorhighlight) { get; set; } | Gets or sets the decorative sheet color highlight in layers' list |
| [Top](top) { get; set; } | Gets or sets the top layer position. |
| override [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| [AddLayerMask](addlayermask)(LayerMaskData) | Adds the mask to current layer. |
| [DrawImage](drawimage)(Point, RasterImage) | Draws the image on layer. |
| override [Equals](equals)(object) | Determines whether the specified Object, is equal to this instance. |
| override [GetHashCode](gethashcode)() | Returns a hash code for this instance. |
| virtual [MergeLayerTo](mergelayerto)(Layer) | Merges the layer to specified layer |
| override [Save](save)(string, bool) | Saves the object's data to the specified file location. |
| override [Save](save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| override [Save](save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [ShallowCopy](shallowcopy)() | Creates a shallow copy of the current Layer. Please [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) for explanation. |

## Other Members

| Name | Description |
| --- | --- |
| const [BlendSignature](blendsignature) | Represents blend mode signature. |
| const [LayerHeaderSize](layerheadersize) | The layer header size. |

### See Also

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
