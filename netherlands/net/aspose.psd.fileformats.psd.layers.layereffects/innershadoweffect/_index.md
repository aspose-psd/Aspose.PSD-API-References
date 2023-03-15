---
title: Class InnerShadowEffect
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect klas. Binnenste schaduwlaageffect
type: docs
weight: 2160
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Binnenste schaduwlaageffect

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Haalt of stelt de hoek in graden in. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Krijgt of stelt de overvloeimodus in. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Krijgt of stelt de kleur in. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Haalt of stelt de afstand in pixels in. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Krijgt een type effect |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Krijgt of stelt de ruis in. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Haalt of stelt de dekking in. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Haalt of stelt de vervagingswaarde in pixels in. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Krijgt of stelt de spreiding (choke) in als percentage. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die aangeeft of [deze hoek in alle laageffecten moet worden gebruikt]. |

### Voorbeelden

De volgende code laat zien hoe u de instellingen van het Inner Shadow Layer Effect kunt wijzigen.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
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

### Zie ook

* interface [IShadowEffect](../ishadoweffect/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* montage [Aspose.PSD](../../)


