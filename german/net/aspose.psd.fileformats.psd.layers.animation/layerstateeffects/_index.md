---
title: "Klasse LayerStateEffects"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerStateEffects Klasse. Die Layer-Status-Effekte"
type: docs
weight: 1970
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/
---
{{< psd/tize >}}
## LayerStateEffects class

Die Effekte des Layer-Zustands.

```csharp
public class LayerStateEffects
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Effects](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/) { get; } | Ruft die Layer-Effekte ab. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/isvisible/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob diese Instanz sichtbar ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddColorOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/)() | Fügt den Farbüberlagerungseffekt hinzu. |
| [AddDropShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/adddropshadow/)() | Fügt den Drop Shadow Effekt hinzu. |
| [AddGradientOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/)() | Fügt den Verlauf-Overlay-Effekt hinzu. |
| [AddInnerShadow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/)() | Fügt den Inneren Schatten-Effekt hinzu. |
| [AddOuterGlow](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/)() | Fügt den äußeren Leuchteffekt hinzu. |
| [AddPatternOverlay](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addpatternoverlay/)() | Fügt den Muster-Overlay-Effekt hinzu. |
| [AddStroke](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/)(FillType) | Fügt den Kontur-Effekt hinzu. |
| [ClearLayerStyle](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/clearlayerstyle/)() | Löscht alle Layer-Stil-Effekte. |
| [RemoveEffectAt](../../aspose.psd.fileformats.psd.layers.animation/layerstateeffects/removeeffectat/)(int) | Entfernt den Layer-Effekt am angegebenen Index. |

## Beispiele

Der folgende Code demonstriert die Unterstützung von Effekten in Timeline-Frames.

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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


