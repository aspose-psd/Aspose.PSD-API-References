---
title: "LayerStateEffects.AddStroke"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LayerStateEffects. Añade el efecto de trazo"
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Agrega el efecto de trazo.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillType | FillType | El tipo de relleno de trazo. |

### Valor devuelto

La nueva instancia de la clase [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/).

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


