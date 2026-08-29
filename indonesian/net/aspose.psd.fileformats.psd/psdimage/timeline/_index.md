---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdImage. Mendapatkan Timeline dari PsdImage ini."
type: docs
weight: 250
url: /id/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Mendapatkan `Timeline` dari [`PsdImage`](../) ini.

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


