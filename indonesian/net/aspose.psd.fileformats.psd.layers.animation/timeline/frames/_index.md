---
title: "Timeline.Frames"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti Timeline. Mendapatkan daftar frame"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/frames/
---
{{< psd/tize >}}
## Timeline.Frames property

Mendapatkan daftar frame.

```csharp
public Frame[] Frames { get; set; }
```

## Contoh

Kelas Timeline memberikan kemampuan tingkat tinggi untuk memanipulasi timeline PsdImage, seperti mengubah penundaan frame atau menyunting status lapisan pada frame tertentu.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Ubah metode dispose pada frame 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ubah penundaan pada frame 2
    timeline.Frames[1].Delay = 15;

    // Ubah opasitas 'Layer 1' pada frame 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // Pindahkan 'Layer 1' ke sudut kiri-bawah pada frame 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Menambahkan frame baru
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Ubah blendMode dari 'Layer 1' pada frame 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Terapkan perubahan kembali ke instance PsdImage
    psdImage.Save(outputPsd);
}
```

### Lihat Juga

* class [Frame](../../frame/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


