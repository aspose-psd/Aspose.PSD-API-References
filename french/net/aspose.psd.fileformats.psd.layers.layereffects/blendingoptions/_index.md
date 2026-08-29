---
title: "Classe BlendingOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.BlendingOptions class. BlendingOptions. C'est un wrapper pour BaseFxResource qui fournit une API pour les effets de calque"
type: docs
weight: 2290
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/
---
{{< psd/tize >}}
## BlendingOptions class

BlendingOptions. C'est un wrapper pour BaseFxResource qui fournit une API pour les effets de calque.

```csharp
public class BlendingOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AreEffectsEnabled](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/areeffectsenabled/) { get; set; } | Obtient ou définit la visibilité de tous les effets de calque. |
| [Effects](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/effects/) { get; set; } | Obtient les effets. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addcoloroverlay/)() | Ajoute la superposition de couleur. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/adddropshadow/)() | Ajoute l'effet d'ombre portée. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addgradientoverlay/)() | Ajoute la superposition Gradient. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addinnershadow/)() | Ajoute l'effet d'ombre interne. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/)() | Ajoute l'effet de lueur externe. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addpatternoverlay/)() | Ajoute la superposition Pattern. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addstroke/)(FillType) | Ajoute l'effet de contour. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


