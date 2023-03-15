---
title: LayerStateEffects.Effects
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerStateEffects Properti. Mendapat efek lapisan.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/effects/
---
## LayerStateEffects.Effects property

Mendapat efek lapisan.

```csharp
public ILayerEffect[] Effects { get; }
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

* interface [ILayerEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/)
* class [LayerStateEffects](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* perakitan [Aspose.PSD](../../../)


