---
title: Class LayerStateEffects
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects classe. Les effets détat de calque.
type: docs
weight: 1870
url: /fr/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
## LayerStateEffects class

Les effets d'état de calque.

```csharp
public class LayerStateEffects
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | Obtient les effets de calque. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est visible. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | Ajoute l'effet de superposition de couleurs. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | Ajoute l'effet d'ombre portée. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | Ajoute l'effet de superposition de dégradé. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | Ajoute l'effet d'ombre intérieure. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | Ajoute l'effet de lueur externe. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | Ajoute l'effet de superposition de motifs. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | Ajoute l'effet de trait. |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | Efface tous les effets de style de calque. |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | Supprime l'effet de calque à l'index spécifique. |

### Exemples

Le code suivant illustre la prise en charge des effets dans les images de la chronologie.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);
    int[] layerIds = timeLine.LayerIds;

    var layerStateEffects11 = timeLine.Frames[1].LayerStates[layerIds[1]].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeLine.Frames[2].LayerStates[layerIds[1]].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    timeLine.ApplyTo(psdImage);

    psdImage.Save(outputFile);
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* Assemblée [Aspose.PSD](../../)


