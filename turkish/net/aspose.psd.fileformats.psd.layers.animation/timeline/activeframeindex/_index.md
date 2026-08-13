---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Timeline özelliği. Etkin çerçeve indeksini alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Etkin çerçeve indeksini alır.

```csharp
public int ActiveFrameIndex { get; }
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

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


