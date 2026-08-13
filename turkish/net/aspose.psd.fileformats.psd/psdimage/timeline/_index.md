---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage özelliği. Bu PsdImage'ın Zaman Çizelgesini alır."
type: docs
weight: 250
url: /tr/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Bu [`PsdImage`](../) nesnesinin `Timeline`'ını alır.

```csharp
public Timeline Timeline { get; }
```

## Örnekler

Aşağıdaki kod, Timeline ile çalışmak için yeni bir yaklaşımı gösterir.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Bir çerçeve daha ekle
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


