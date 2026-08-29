---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Timeline-egenskap. Hämtar det aktiva bildrutesindexet"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Hämtar det aktiva bildruteindexet.

```csharp
public int ActiveFrameIndex { get; }
```

## Exempel

Följande kod demonstrerar ett nytt tillvägagångssätt för att arbeta med Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Lägg till en ytterligare ram
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Se även

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


