---
title: Class OuterGlowEffect
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect class. Outer Glow Layer effect
type: docs
weight: 2350
url: /net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
{{< psd/tize >}}
## OuterGlowEffect class

Outer Glow Layer effect

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Properties

| Name | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Gets or sets the blend mode. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Gets a type of effect type |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Gets or sets the color. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Gets or sets the angle in degrees. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Gets or sets enabled AntiAliasing effect |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Gets or sets a value indicating whether [knocks out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Gets or sets a value indicating whether this instance is visible. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Gets or sets the noise. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Gets or sets the noise. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Gets or sets the opacity. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Gets or sets the noise. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; set; } | Gets the blur value in pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Gets or sets the intensity as a percent. |

## Methods

| Name | Description |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/geteffectbounds/)(Rectangle, int) | Calculate and gets the bounds of effect pixels based on input layer pixels bounds. |

## Examples

The following code demonstrates the OuterGlowEffect support.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### See Also

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


