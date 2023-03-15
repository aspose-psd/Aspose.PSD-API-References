---
title: LayerStateEffects.AddColorOverlay
second_title: Aspose.PSD för .NET API-referens
description: LayerStateEffects metod. Lägger till färgöverlagringseffekten.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/
---
## LayerStateEffects.AddColorOverlay method

Lägger till färgöverlagringseffekten.

```csharp
public ColorOverlayEffect AddColorOverlay()
```

### Returvärde

Den nya instansen av[`ColorOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) klass.

### Exempel

Följande kod visar stöd för effekter i tidslinjeramar.

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

### Se även

* class [ColorOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)
* class [LayerStateEffects](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* hopsättning [Aspose.PSD](../../../)


