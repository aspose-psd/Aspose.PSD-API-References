---
title: Class LayerStateEffects
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects klas. De laagstatuseffecten.
type: docs
weight: 1870
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
## LayerStateEffects class

De laagstatuseffecten.

```csharp
public class LayerStateEffects
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | Krijgt de laageffecten. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie zichtbaar is. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | Voegt het kleuroverlay-effect toe. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | Voegt het slagschaduweffect toe. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | Voegt het verloopoverlay-effect toe. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | Voegt het binnenste schaduweffect toe. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | Voegt het buitenste gloedeffect toe. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | Voegt het patroonoverlay-effect toe. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | Voegt het lijneffect toe. |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | Wist alle laagstijleffecten. |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | Verwijdert het laageffect bij de specifieke index. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van effecten in tijdlijnframes.

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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* montage [Aspose.PSD](../../)


