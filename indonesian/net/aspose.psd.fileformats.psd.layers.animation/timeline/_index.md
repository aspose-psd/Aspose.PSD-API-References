---
title: "Kelas Timeline"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Timeline kelas. Model opsi timeline"
type: docs
weight: 1980
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
{{< psd/tize >}}
## Timeline class

Model opsi garis waktu.

```csharp
public sealed class Timeline
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Timeline](timeline/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActiveFrameIndex](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/) { get; } | Mendapatkan indeks frame aktif. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Mendapatkan atau mengatur nilai AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Mendapatkan daftar frame. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Mendapatkan atau mengatur nilai FsID. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Mendapatkan atau mengatur jumlah loop. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save)(Stream, ImageOptionsBase) | Menyimpan data PsdImage dan Timeline ke aliran yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [Save](../../aspose.psd.fileformats.psd.layers.animation/timeline/save/#save_1)(string, ImageOptionsBase) | Menyimpan data PsdImage dan Timeline ke lokasi file yang ditentukan dalam format yang ditentukan sesuai opsi penyimpanan. |
| [SwitchActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/)(int) | Mengganti frame aktif ke target. |

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


