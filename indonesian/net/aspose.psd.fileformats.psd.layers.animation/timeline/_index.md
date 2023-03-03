---
title: Class TimeLine
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine kelas. Model opsi garis waktu.
type: docs
weight: 1880
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

Model opsi garis waktu.

```csharp
public sealed class TimeLine
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [TimeLine](timeline/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | Mendapat atau menyetel indeks bingkai aktif. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Mendapat atau menyetel nilai AFSt. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Mendapat daftar frame. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Mendapat atau menetapkan nilai FsID. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | Mendapat atau menyetel array id layer. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Mendapat atau mengatur jumlah loop. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | Membuat instance baru dari`TimeLine` , diinisialisasi dari input[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | Terapkan nilai garis waktu saat ini ke input[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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

* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* perakitan [Aspose.PSD](../../)


