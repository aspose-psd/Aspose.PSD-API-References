---
title: "Classe InnerShadowEffect"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.InnerShadowEffect class. Effet de calque Ombre interne"
type: docs
weight: 2350
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---
{{< psd/tize >}}
## InnerShadowEffect class

Effet de calque d'ombre interne.

```csharp
public class InnerShadowEffect : IShadowEffect
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/angle/) { get; set; } | Obtient ou définit l'angle en degrés. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/blendmode/) { get; set; } | Obtient ou définit le mode de fusion. |
| [Color](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/color/) { get; set; } | Obtient ou définit la couleur. |
| [Distance](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/distance/) { get; set; } | Obtient ou définit la distance en pixels. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/effecttype/) { get; } | Obtient un type d'effet |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/isvisible/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [Noise](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/noise/) { get; set; } | Obtient ou définit le bruit. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/opacity/) { get; set; } | Obtient ou définit l'opacité. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/size/) { get; set; } | Obtient ou définit la valeur de flou en pixels. |
| [Spread](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/spread/) { get; set; } | Obtient ou définit la diffusion (étranglement) en pourcentage. |
| [UseGlobalLight](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/usegloballight/) { get; set; } | Obtient ou définit une valeur indiquant si [use this angle in all of the layer effects]. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/geteffectbounds/)(Rectangle, int) | Calcule et obtient les limites des pixels d'effet basées sur les limites des pixels du calque d'entrée. |

## Exemples

Le code suivant montre comment modifier les paramètres de l'effet de calque Ombre interne.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "sample_out.psd";

// Chargez une image existante dans une instance de la classe PsdImage
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

### Voir aussi

* interface [IShadowEffect](../ishadoweffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


