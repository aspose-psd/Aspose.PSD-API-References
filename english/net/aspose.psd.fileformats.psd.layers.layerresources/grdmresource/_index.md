---
title: Class GrdmResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource class. Class GrdmResource. Contains information about GradientMap layer
type: docs
weight: 2540
url: /net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Class GrdmResource. Contains information about Gradient-Map layer.

```csharp
public class GrdmResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [GrdmResource](grdmresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Color Model. When 'Gradient type' = 'Noise', we can assign 'Color Model' to RGB/SHB/LAB (3/4/6). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Gets or sets the color points. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Is gradient dithered. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Expansion count ( = 2 for Photoshop 6.0). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | Mode for this gradient Determines 'Gradient Type' = 'Solid/Noise' (0/1). |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Name of the gradient: Unicode string, padded. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Interpolation. Determines Smoothness, when 'Gradient Type' = 'Solid' (GradientMode = 0). |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Gets the layer resource length in bytes. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; } | Maximum color of PixelDataFormat.Rgba64Bpp format. Color has ARGB channels, Each channel is 16bit. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; } | Minimum color of PixelDataFormat.Rgba64Bpp format. Color has ARGB channels, Each channel is 16bit. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Is gradient reversed. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | The random number seed used to generate colors for Noise gradient. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Roughness factor When 'Gradient type' = 'Noise', we can assign 'Roughness' (0 - 2048). |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Flag for showing transparency When 'Gradient type' = 'Noise', we can assign 'Add transparency' to true. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/signature/) { get; } | Gets the signature. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Gets or sets the transparency points. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Flag for using vector color. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Saves resource data to the specified stream container. |
| [SetPsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/setpsdversion/)(ushort) | Sets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | The type tool info key. |

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


