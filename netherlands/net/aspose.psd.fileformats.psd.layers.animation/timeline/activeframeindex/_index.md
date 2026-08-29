---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Timeline-eigenschap. Haalt de actieve frame-index op"
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Haalt de actieve frame-index op.

```csharp
public int ActiveFrameIndex { get; }
```

## Voorbeelden

De volgende code toont een nieuwe benadering om met de Timeline te werken.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Voeg nog een frame toe
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Zie ook

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


