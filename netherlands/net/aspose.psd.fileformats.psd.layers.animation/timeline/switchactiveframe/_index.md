---
title: "Timeline.SwitchActiveFrame"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Timeline-methode. Schakelt het actieve frame naar het doel"
type: docs
weight: 80
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/timeline/switchactiveframe/
---
{{< psd/tize >}}
## Timeline.SwitchActiveFrame method

Schakelt het actieve frame naar het doel.

```csharp
public void SwitchActiveFrame(int targetActiveFrameIndex)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetActiveFrameIndex | Int32 | De index van het doelframe. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| IndexOutOfRangeException | De nieuwe index van het actieve frame moet binnen het bereik van het aantal frames liggen. |

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


