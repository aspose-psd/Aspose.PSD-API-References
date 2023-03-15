---
title: LayerStateEffects.AddDropShadow
second_title: Aspose.PSD för .NET API-referens
description: LayerStateEffects metod. Lägger till skuggeffekten.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
## LayerStateEffects.AddDropShadow method

Lägger till skuggeffekten.

```csharp
public DropShadowEffect AddDropShadow()
```

### Returvärde

Den nya instansen av[`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) klass.

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

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* hopsättning [Aspose.PSD](../../../)


