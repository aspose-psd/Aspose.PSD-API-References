---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Timeline. Mengalihkan frame aktif ke frame yang ditargetkan"
type: docs
weight: 80
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Mengganti frame aktif ke target.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Indeks frame target. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| IndexOutOfRangeException | Indeks baru dari frame aktif harus berada dalam rentang jumlah frame. |

## Contoh

Kode berikut menunjukkan pendekatan baru untuk bekerja dengan Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Tambahkan satu frame lagi
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Lihat Juga

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


