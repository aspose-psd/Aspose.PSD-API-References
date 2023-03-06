---
title: Class TimeLine
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine klass. Tidslinjealternativmodellen.
type: docs
weight: 1880
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

Tidslinjealternativmodellen.

```csharp
public sealed class TimeLine
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TimeLine](timeline/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | Hämtar eller ställer in det aktiva ramindexet. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Hämtar eller ställer in AFSt-värdet. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Hämtar listan med ramar. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Hämtar eller ställer in FsID-värdet. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | Hämtar eller ställer in lager-id-matrisen. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Hämtar eller ställer in antalet loopar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | Skapar den nya instansen av`TimeLine` , initierad från ingång[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | Tillämpa aktuella tidslinjevärden på indata[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* hopsättning [Aspose.PSD](../../)


