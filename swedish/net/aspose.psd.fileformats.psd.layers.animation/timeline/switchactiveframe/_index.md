---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Timeline‑metod. Byter den aktiva ramen till den målade"
type: docs
weight: 80
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Byter den aktiva bildrutan till den önskade.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | Det målade ramindexet. |

### Undantag

| undantag | villkor |
| --- | --- |
| IndexOutOfRangeException | Det nya indexet för den aktiva ramen bör ligga inom ramen för antalet ramar. |

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


