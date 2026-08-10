---
title: "LayerStateEffects.AddInnerShadow"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "LayerStateEffects metode. Menambahkan efek bayangan dalam"
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addinnershadow/
---
{{< psd/tize >}}
## LayerStateEffects.AddInnerShadow method

Menambahkan efek bayangan dalam.

```csharp
public InnerShadowEffect AddInnerShadow()
```

### Nilai Kembalian

Instansi baru dari kelas [`InnerShadowEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/).

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

* class [InnerShadowEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


