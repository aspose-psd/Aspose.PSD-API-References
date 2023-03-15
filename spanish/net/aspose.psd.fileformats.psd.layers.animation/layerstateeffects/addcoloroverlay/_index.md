---
title: LayerStateEffects.AddColorOverlay
second_title: Referencia de API de Aspose.PSD para .NET
description: LayerStateEffects método. Agrega el efecto de superposición de color.
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addcoloroverlay/
---
## LayerStateEffects.AddColorOverlay method

Agrega el efecto de superposición de color.

```csharp
public ColorOverlayEffect AddColorOverlay()
```

### Valor_devuelto

La nueva instancia de la[`ColorOverlayEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/) clase.

### Ejemplos

El siguiente código demuestra la compatibilidad con los efectos en los marcos de la línea de tiempo.

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

### Ver también

* class [ColorOverlayEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/)
* class [LayerStateEffects](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* asamblea [Aspose.PSD](../../../)


