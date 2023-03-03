---
title: TimeLine.Frames
second_title: Aspose.PSD untuk Referensi .NET API
description: TimeLine Properti. Mendapat daftar frame.
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
## TimeLine.Frames property

Mendapat daftar frame.

```csharp
public Frame[] Frames { get; set; }
```

### Contoh

Kelas TimeLine memberikan kemampuan tingkat tinggi untuk memanipulasi garis waktu PsdImage, seperti mengubah penundaan bingkai atau mengedit status lapisan pada bingkai tertentu.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Ubah metode pembuangan frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ubah delay frame 2
    timeLine.Frames[1].Delay = 15;

    // Ubah opasitas 'Lapisan 1' pada bingkai 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // pindahkan 'Lapisan 1' ke pojok kiri bawah pada bingkai 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Menambahkan bingkai baru
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Ubah blendMode dari 'Layer 1' pada frame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Menerapkan perubahan kembali ke instance PsdImage
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Lihat juga

* class [Frame](../../frame/)
* class [TimeLine](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* perakitan [Aspose.PSD](../../../)


