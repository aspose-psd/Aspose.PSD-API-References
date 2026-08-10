---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti Timeline. Mendapatkan indeks frame aktif"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Mendapatkan indeks frame aktif.

```csharp
public int ActiveFrameIndex { get; }
```

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


