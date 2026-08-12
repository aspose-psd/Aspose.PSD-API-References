---
title: "LayerStateEffects.AddGradientOverlay"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LayerStateEffects. Añade el efecto de superposición de degradado"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addgradientoverlay/
---
{{< psd/tize >}}
## LayerStateEffects.AddGradientOverlay method

Agrega el efecto de superposición de degradado.

```csharp
public GradientOverlayEffect AddGradientOverlay()
```

### Valor devuelto

La nueva instancia de la clase [`GradientOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/).

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

* class [GradientOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


