---
title: "LayerStateEffects.AddOuterGlow"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "LayerStateEffects metode. Menambahkan efek cahaya luar"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addouterglow/
---
{{< psd/tize >}}
## LayerStateEffects.AddOuterGlow method

Menambahkan efek cahaya luar.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Nilai Kembalian

Instansi baru dari kelas [`OuterGlowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/).

## Contoh

Kode berikut menunjukkan dukungan efek dalam frame Timeline.

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

### Lihat Juga

* class [OuterGlowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


