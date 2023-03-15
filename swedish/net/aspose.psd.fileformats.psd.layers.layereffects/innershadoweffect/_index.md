---
title: Class InnerShadowEffect
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect klass. Effekt av inre skugglager
type: docs
weight: 2160
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
## InnerShadowEffect class

Effekt av inre skugglager

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Hämtar eller ställer in vinkeln i grader. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Hämtar eller ställer in blandningsläget. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Hämtar eller ställer in färgen. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Hämtar eller ställer in avståndet i pixlar. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Får en typ av effekt |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är synlig. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Får eller ställer in bruset. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Hämtar eller ställer in opaciteten. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Hämtar eller ställer in oskärpa värdet i pixlar. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Får eller ställer in spridningen (choke) som procent. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Hämtar eller ställer in ett värde som anger om [använd denna vinkel i alla lagereffekter]. |

### Exempel

Följande kod visar hur man ändrar inställningarna för den inre skuggskiktseffekten.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
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

### Se även

* interface [IShadowEffect](../ishadoweffect/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* hopsättning [Aspose.PSD](../../)


