---
title: TimeLine.ApplyTo
second_title: Aspose.PSD för .NET API-referens
description: TimeLine metod. Tillämpa aktuella tidslinjevärden på indataPsdImage .
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
## TimeLine.ApplyTo method

Tillämpa aktuella tidslinjevärden på indata[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| psdImage | PsdImage | Psd-bilden. |

### Exempel

Klassen TimeLine ger en hög nivå förmåga att manipulera tidslinjen för PsdImage, som att ändra bildrutefördröjning eller redigera lagertillstånd på en specifik bildruta.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Ändra avyttringsmetod för ram 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ändra fördröjning av bildruta 2
    timeLine.Frames[1].Delay = 15;

    // Ändra opaciteten för 'Layer 1' på bildruta 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // flytta 'Layer 1' till det nedre vänstra hörnet på bildruta 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Lägger till ny ram
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Ändra blendMode för 'Layer 1' på bildruta 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Tillämpa ändringar tillbaka till PsdImage-instansen
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Se även

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* hopsättning [Aspose.PSD](../../../)


