---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. Metode pembuangan frame menentukan apakah akan membuang frame saat ini sebelum menampilkan frame berikutnya. Anda memilih metode pembuangan untuk animasi yang menyertakan transparansi latar belakang untuk menentukan apakah frame saat ini akan terlihat melalui area transparan dari frame berikutnya.
type: docs
weight: 1850
url: /id/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Metode pembuangan frame menentukan apakah akan membuang frame saat ini sebelum menampilkan frame berikutnya. Anda memilih metode pembuangan untuk animasi yang menyertakan transparansi latar belakang untuk menentukan apakah frame saat ini akan terlihat melalui area transparan dari frame berikutnya.

```csharp
public enum FrameDisposalMethod
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Automatic | `0` | Menentukan metode pembuangan untuk frame saat ini secara otomatis, membuang frame saat ini jika frame berikutnya berisi transparansi lapisan. Untuk sebagian besar animasi, opsi Otomatis (default) memberikan hasil yang diinginkan. |
| DoNotDispose | `1` | Mempertahankan bingkai saat ini saat bingkai berikutnya ditambahkan ke tampilan. Bingkai saat ini (dan bingkai sebelumnya) dapat ditampilkan melalui area transparan dari bingkai berikutnya. |
| Dispose | `2` | Membuang bingkai saat ini dari tampilan sebelum bingkai berikutnya ditampilkan. Hanya satu bingkai yang ditampilkan setiap saat (dan bingkai saat ini tidak muncul melalui area transparan bingkai berikutnya). |

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


