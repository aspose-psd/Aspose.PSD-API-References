---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerStateEffects metod. Lägger till linjeeffekten"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Lägger till linjeeffekten.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillType | FillType | Typen strokifyllning. |

### Returvärde

Den nya instansen av [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) klassen.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


