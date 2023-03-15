---
title: Class LayerState
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState klass. Alternativen för tidslinjelagerstatus.
type: docs
weight: 1860
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Alternativen för tidslinjelagerstatus.

```csharp
public sealed class LayerState
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LayerState](layerstate/)(int) | Initierar en ny instans av`LayerState` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Hämtar eller ställer in blandningsläget. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Hämtar eller ställer in det aktiverade tillståndet. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Hämtar eller ställer in fyllningsopacitetsvärdet. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Hämtar eller ställer in HorizontalFXRf-värdet. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Hämtar eller ställer in id. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Hämtar eller ställer in opacitetsvärdet. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Hämtar eller ställer in lagerpositionsoffset relaterad till den faktiska lagerpositionen. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Får lagertillståndseffekterna. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Hämtar eller ställer in VerticalFXRf-värdet. |

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


