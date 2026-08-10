---
title: "TimeLine.ApplyTo"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode TimeLine. Menerapkan nilai timeline saat ini ke PsdImage input"
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
{{< psd/tize >}}
## TimeLine.ApplyTo method

Menerapkan nilai timeline saat ini ke [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| psdImage | PsdImage | Gambar psd. |

## Contoh

Kelas TimeLine memberikan kemampuan tingkat tinggi untuk memanipulasi timeline PsdImage, seperti mengubah penundaan frame atau mengedit status lapisan pada frame tertentu.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Ubah metode dispose pada frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ubah penundaan pada frame 2
    timeLine.Frames[1].Delay = 15;

    // Ubah opasitas 'Layer 1' pada frame 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // Pindahkan 'Layer 1' ke sudut kiri-bawah pada frame 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Menambahkan frame baru
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Ubah blendMode dari 'Layer 1' pada frame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Terapkan perubahan kembali ke instance PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Lihat Juga

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


