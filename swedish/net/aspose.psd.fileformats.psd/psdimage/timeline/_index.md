---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage egenskap. Hämtar Timeline för denna PsdImage"
type: docs
weight: 250
url: /sv/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Hämtar `Timeline` för denna [`PsdImage`](../).

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


