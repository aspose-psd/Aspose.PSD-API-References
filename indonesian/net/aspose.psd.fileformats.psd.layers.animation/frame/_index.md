---
title: Class Frame
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame kelas. Opsi item kerangka waktu.
type: docs
weight: 1840
url: /id/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Opsi item kerangka waktu.

```csharp
public sealed class Frame
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Frame](frame/)(TimeLine) | Menginisialisasi instance baru dari`Frame` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Mendapat atau menetapkan nilai frame delay dalam centa-seconds. Misal dalam 1 second berisi 100 centa-seconds. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Mendapat atau menyetel metode pembuangan frame. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Mendapat atau mengatur frame id. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Dapat mengatur status lapisan frame. |

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


