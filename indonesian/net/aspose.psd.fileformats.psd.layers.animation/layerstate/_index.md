---
title: "Kelas LayerState"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState class. Opsi status lapisan pada timeline"
type: docs
weight: 1960
url: /id/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Opsi status lapisan garis waktu.

```csharp
public sealed class LayerState
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [LayerState](layerstate/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Mendapatkan atau mengatur mode pencampuran. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Mendapatkan atau mengatur status aktif. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Mendapatkan atau mengatur nilai opacity isi. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Mendapatkan atau mengatur nilai HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Mendapatkan atau mengatur id lapisan. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Mendapatkan atau mengatur nilai opacity. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Mendapatkan atau mengatur offset posisi lapisan yang terkait dengan posisi lapisan sebenarnya. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Mendapatkan efek status lapisan. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Mendapatkan atau mengatur nilai VerticalFXRf. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


