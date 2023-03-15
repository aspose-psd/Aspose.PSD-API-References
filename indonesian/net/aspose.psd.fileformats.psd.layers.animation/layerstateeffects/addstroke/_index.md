---
title: LayerStateEffects.AddStroke
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerStateEffects metode. Menambahkan efek goresan.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstateeffects/addstroke/
---
## LayerStateEffects.AddStroke method

Menambahkan efek goresan.

```csharp
public StrokeEffect AddStroke(FillType fillType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fillType | FillType | Jenis mengisi stroke. |

### Nilai Pengembalian

Instance baru dari[`StrokeEffect`](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/) kelas.

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

* class [StrokeEffect](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/)
* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [LayerStateEffects](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../layerstateeffects/)
* perakitan [Aspose.PSD](../../../)


