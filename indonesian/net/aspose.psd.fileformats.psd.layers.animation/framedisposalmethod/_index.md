---
title: "Enum FrameDisposalMethod"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. Metode pembuangan frame menentukan apakah harus membuang frame saat ini sebelum menampilkan frame berikutnya. Anda memilih metode pembuangan untuk animasi yang mencakup transparansi latar belakang untuk menentukan apakah frame saat ini akan terlihat melalui area transparan pada frame berikutnya."
type: docs
weight: 1950
url: /id/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

Metode pembuangan frame menentukan apakah frame saat ini harus dibuang sebelum menampilkan frame berikutnya. Anda memilih metode pembuangan untuk animasi yang mencakup transparansi latar belakang untuk menentukan apakah frame saat ini akan terlihat melalui area transparan pada frame berikutnya.

```csharp
public enum FrameDisposalMethod
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Automatic | `0` | Menentukan metode pembuangan untuk frame saat ini secara otomatis, membuang frame saat ini jika frame berikutnya mengandung transparansi lapisan. Untuk kebanyakan animasi, opsi Automatic (default) menghasilkan hasil yang diinginkan. |
| DoNotDispose | `1` | Mempertahankan frame saat ini saat frame berikutnya ditambahkan ke tampilan. Frame saat ini (dan frame sebelumnya) dapat terlihat melalui area transparan pada frame berikutnya. |
| Dispose | `2` | Membuang frame saat ini dari tampilan sebelum frame berikutnya ditampilkan. Hanya satu frame yang ditampilkan pada satu waktu (dan frame saat ini tidak muncul melalui area transparan pada frame berikutnya). |

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


