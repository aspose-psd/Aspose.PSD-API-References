---
title: "LayerStateEffects.AddStroke"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode LayerStateEffects. Menambahkan efek goresan"
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
{{< psd/tize >}}
## LayerStateEffects.AddStroke method

Menambahkan efek goresan.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillType | FillType | Tipe isi goresan. |

### Nilai Kembalian

Instansi baru dari kelas [`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/).

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


