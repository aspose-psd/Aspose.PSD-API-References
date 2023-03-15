---
title: LayerStateEffects.AddOuterGlow
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerStateEffects metode. Menambahkan efek cahaya luar.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
## LayerStateEffects.AddOuterGlow method

Menambahkan efek cahaya luar.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Nilai Pengembalian

Instance baru dari[`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/) kelas.

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

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* perakitan [Aspose.PSD](../../../)


