---
title: Class BritResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource class. Class BritResource. Resource of Brightness/Contrast Adjustment Layer
type: docs
weight: 2570
url: /net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Class BritResource. Resource of Brightness/Contrast Adjustment Layer

```csharp
public class BritResource : AdjustmentLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initializes a new instance of the `BritResource` class. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initializes a new instance of the `BritResource` class. PSD format specification contains following description: 2 Brightness 2 Contrast 2 Mean value for brightness and contrast 1 Lab color only It is not used in modern PSD(CS5 and up) where CgEd is. CgEd stores info properties |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initializes a new instance of the `BritResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Gets or sets the brightness. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Gets or sets the contrast. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Gets or sets a value indicating whether [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Gets the layer resource length in bytes. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Gets or sets the mean value for brightness and contrast. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | The type tool info key. |

### See Also

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


