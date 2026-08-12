---
title: "TimeLine.InitializeFrom"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TimeLine‑metod. Skapar en ny instans av TimeLine initierad från inmatad PsdImage"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
{{< psd/tize >}}
## TimeLine.InitializeFrom method

Skapar den nya instansen av [`TimeLine`](../), initierad från inmatad [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdImage | PsdImage | psd‑bilden. |

### Returvärde

Den nya instansen av [`TimeLine`](../), initierad från inmatad [`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

## Exempel

TimeLine‑klassen ger en hög nivå av möjlighet att manipulera tidslinjen för PsdImage, såsom att ändra ramfördröjning eller redigera lagertillstånd på en specifik ram.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Ändra borttagningsmetod för bildruta 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ändra fördröjning för bildruta 2
    timeLine.Frames[1].Delay = 15;

    // Ändra opacitet för 'Layer 1' på bildruta 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // flytta 'Layer 1' till vänster‑nedre hörnet på bildruta 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Lägger till ny bildruta
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Ändra blandningsläge för 'Layer 1' på bildruta 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Applicera ändringar tillbaka till PsdImage‑instansen
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Se även

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


