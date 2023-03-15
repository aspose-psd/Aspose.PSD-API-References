---
title: Class Frame
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame klass. Alternativen för tidslinjeobjekt.
type: docs
weight: 1840
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Alternativen för tidslinjeobjekt.

```csharp
public sealed class Frame
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Frame](frame/)(TimeLine) | Initierar en ny instans av`Frame` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Hämtar eller ställer in ramfördröjningsvärdet i centa-sekunder. Innehåller till exempel på 1 sekund 100 centa-sekunder. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Hämtar eller ställer in kasseringsmetoden för ramen. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Hämtar eller ställer in ram-id. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Gets ot ställer in lagertillstånden för ramen. |

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


