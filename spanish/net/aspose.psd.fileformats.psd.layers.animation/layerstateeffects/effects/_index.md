---
title: "LayerStateEffects.Effects"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad LayerStateEffects. Obtiene los efectos de capa"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
{{< psd/tize >}}
## LayerStateEffects.Effects property

Obtiene los efectos de capa.

```csharp
public ILayerEffect[] Effects { get; }
```

## Ejemplos

El siguiente código demuestra el soporte de efectos en los fotogramas de Timeline.

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

### Ver también

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


