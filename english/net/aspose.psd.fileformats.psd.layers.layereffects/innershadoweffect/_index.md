---
title: Class InnerShadowEffect
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect class. Inner Shadow Layer effect
type: docs
weight: 2330
url: /net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Inner Shadow Layer effect

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Gets or sets the angle in degrees. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Gets or sets the blend mode. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Gets or sets the color. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Gets or sets the distance in pixels. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Gets a type of effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Gets or sets a value indicating whether this instance is visible. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Gets or sets the noise. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Gets or sets the opacity. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Gets or sets the blur value in pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Gets or sets the spread (choke) as percentage. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Gets or sets a value indicating whether [use this angle in all of the layer effects]. |

## Methods

| Name | Description |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Calculate and gets the bounds of effect pixels based on input layer pixels bounds. |

## Examples

The following code demonstrates how to change settings of the Inner Shadow Layer Effect.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Load an existing image into an instance of PsdImage class
var loadOptions = new PsdLoadOptions();
loadOptions.LoadEffectsResource = true;
using (var image = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    var layer = image.Layers[image.Layers.Length - 1];
    var shadowEffect = (IShadowEffect)layer.BlendingOptions.Effects[0];

    shadowEffect.Color = Color.Green;
    shadowEffect.Opacity = 128;
    shadowEffect.Distance = 1;
    shadowEffect.UseGlobalLight = false;
    shadowEffect.Size = 2;
    shadowEffect.Angle = 45;
    shadowEffect.Spread = 50;
    shadowEffect.Noise = 5;

    image.Save(outputFile, new PsdOptions(image));
}
```

### See Also

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


