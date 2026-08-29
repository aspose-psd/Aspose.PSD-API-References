---
title: "LayerStateEffects.AddDropShadow"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerStateEffects metod. Lägger till kastskuggeffekten"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddDropShadow method

Lägger till fallskuggeffekten.

```csharp
public DropShadowEffect AddDropShadow()
```

### Returvärde

Den nya instansen av [`DropShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/) klassen.

## Exempel

Följande kod demonstrerar stöd för effekter i Timeline-ramar.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    var layerStateEffects11 = timeline.Frames[1].LayerStates[1].StateEffects;

    layerStateEffects11.AddDropShadow();
    layerStateEffects11.AddGradientOverlay();

    var layerStateEffects21 = timeline.Frames[2].LayerStates[1].StateEffects;
    layerStateEffects21.AddStroke(FillType.Color);
    layerStateEffects21.IsVisible = false;

    psdImage.Save(outputFile);
}
```

### Se även

* class [DropShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


