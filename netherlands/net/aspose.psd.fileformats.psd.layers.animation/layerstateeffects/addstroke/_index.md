---
title: LayerStateEffects.AddStroke
second_title: Aspose.PSD voor .NET API-referentie
description: LayerStateEffects methode. Voegt het lijneffect toe.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

Voegt het lijneffect toe.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillType | FillType | Het type slagvulling. |

### Winstwaarde

Het nieuwe exemplaar van de[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) klas.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* montage [Aspose.PSD](../../../)


