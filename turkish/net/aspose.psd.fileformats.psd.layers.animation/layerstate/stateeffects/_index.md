---
title: LayerState.StateEffects
second_title: Aspose.PSD for .NET API Referansı
description: LayerState mülk. Katman durumu efektlerini alır.
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Katman durumu efektlerini alır.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Örnekler

Aşağıdaki kod, Zaman Çizelgesi çerçevelerindeki efektlerin desteğini gösterir.

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

### Ayrıca bakınız

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* toplantı [Aspose.PSD](../../../)


