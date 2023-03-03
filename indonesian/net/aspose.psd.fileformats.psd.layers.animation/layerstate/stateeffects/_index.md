---
title: LayerState.StateEffects
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerState Properti. Mendapat efek status lapisan.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/
---
## LayerState.StateEffects property

Mendapat efek status lapisan.

```csharp
public LayerStateEffects StateEffects { get; }
```

### Contoh

Kode berikut menunjukkan dukungan efek dalam bingkai Timeline.

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

### Lihat juga

* class [LayerStateEffects](../../layerstateeffects/)
* class [LayerState](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstate/)
* perakitan [Aspose.PSD](../../../)


