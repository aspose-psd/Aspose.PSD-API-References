---
title: BritResource
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2260
url: /net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
## BritResource class

Class BritResource. Resource of Brightness/Contrast Adjustment Layer

```csharp
public class BritResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [BritResource](britresource)() | Initializes a new instance of the [`BritResource`](../britresource) class. |
| [BritResource](britresource)(byte[]) | Initializes a new instance of the [`BritResource`](../britresource) class. PSD format specification contains following description: 2 Brightness 2 Contrast 2 Mean value for brightness and contrast 1 Lab color only It is not used in modern PSD(CS5 and up) where CgEd is. CgEd stores info properties |
| [BritResource](britresource)(short, short, short, bool) | Initializes a new instance of the [`BritResource`](../britresource) class. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness) { get; set; } | Gets or sets the brightness. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast) { get; set; } | Gets or sets the contrast. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/key) { get; } | Gets the layer resource key. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor) { get; set; } | Gets or sets a value indicating whether [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length) { get; } | Gets the layer resource length in bytes. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast) { get; set; } | Gets or sets the mean value for brightness and contrast. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/psdversion) { get; } | Gets the psd version. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Returns a String that represents this instance. |

## Other Members

| Name | Description |
| --- | --- |
| const [TypeToolKey](typetoolkey) | The type tool info key. |

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
