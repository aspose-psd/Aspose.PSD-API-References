---
title: Class OuterGlowEffect
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.OuterGlowEffect klas. Outer Glow Layereffect
type: docs
weight: 2170
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---
## OuterGlowEffect class

Outer Glow Layer-effect

```csharp
public class OuterGlowEffect : ILayerEffect
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/) { get; set; } | Krijgt of stelt de overvloeimodus in. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/effecttype/) { get; } | Krijgt een type effect type |
| [FillColor](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/fillcolor/) { get; set; } | Krijgt of stelt de kleur in. |
| [Intensity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/) { get; set; } | Haalt of stelt de hoek in graden in. |
| [IsAntiAliasing](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isantialiasing/) { get; set; } | Krijgt of stelt ingeschakeld AntiAliasing-effect in |
| [IsSoftBlend](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/issoftblend/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [knocks-out]. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/isvisible/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is. |
| [Jitter](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/) { get; set; } | Krijgt of stelt de ruis in. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/noise/) { get; set; } | Krijgt of stelt de ruis in. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/opacity/) { get; set; } | Haalt of stelt de dekking in. |
| [Range](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/) { get; set; } | Krijgt of stelt de ruis in. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/) { get; } | Krijgt de vervagingswaarde in pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/) { get; set; } | Haalt de intensiteit op of stelt deze in als een percentage. |

### Voorbeelden

De volgende code demonstreert de OuterGlowEffect-ondersteuning.

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

### Zie ook

* interface [ILayerEffect](../ilayereffect/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* montage [Aspose.PSD](../../)


