---
title: DropShadowEffect
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 2060
url: /net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---
## DropShadowEffect class

Drop Shadow Layer effect

```csharp
public class DropShadowEffect : IShadowEffect
```

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle) { get; set; } | Gets or sets the angle in degrees. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode) { get; set; } | Gets or sets the blend mode. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color) { get; set; } | Gets or sets the color. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/distance) { get; set; } | Gets or sets the distance in pixels. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype) { get; } | Gets a type of effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible) { get; set; } | Gets or sets a value indicating whether this instance is visible. |
| [KnocksOut](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/knocksout) { get; set; } | Gets or sets a value indicating whether [knocks out]. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/noise) { get; set; } | Gets or sets the noise. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/opacity) { get; set; } | Gets or sets the opacity. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/size) { get; set; } | Gets or sets the blur value in pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/spread) { get; set; } | Gets or sets the intensity as a percent. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/usegloballight) { get; set; } | Gets or sets a value indicating whether [use this angle in all of the layer effects]. |

### Examples

The following code demonstrates support for the PsdImage.GlobalAngle property to change the global angle value.

```csharp
[C#]

// When DropShadowEffect.UseGlobalLight property is 'true', then DropShadowEffect object use angle value from PsdImage.GlobalAngle property.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### See Also

* interface [IShadowEffect](../ishadoweffect)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
