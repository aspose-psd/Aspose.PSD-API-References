---
title: "Klass LayerState"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState-klass. Alternativen för tidslinjelagrets tillstånd"
type: docs
weight: 1960
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Alternativen för tidslinjens lagertillstånd.

```csharp
public sealed class LayerState
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LayerState](layerstate/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Hämtar eller anger blandningsläget. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Hämtar eller anger det aktiverade tillståndet. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Hämtar eller anger fyllnadens opacitetsvärde. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Hämtar eller anger värdet för HorizontalFXRf. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Hämtar eller anger lagrets ID. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Hämtar eller anger opacitetsvärdet. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Hämtar eller anger lagrets positionsförskjutning i förhållande till den faktiska lagrets position. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Hämtar lagrets tillståndseffekter. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Hämtar eller anger värdet för VerticalFXRf. |

## Exempel

Timeline‑klassen ger en hög nivå förmåga att manipulera tidslinjen för PsdImage, såsom att ändra bildrutefördröjning eller redigera lagertillstånd på en specifik bildruta.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Ändra borttagningsmetod för bildruta 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ändra fördröjning för bildruta 2
    timeline.Frames[1].Delay = 15;

    // Ändra opacitet för 'Layer 1' på bildruta 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // flytta 'Layer 1' till vänster‑nedre hörnet på bildruta 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Lägger till ny bildruta
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Ändra blandningsläge för 'Layer 1' på bildruta 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Applicera ändringar tillbaka till PsdImage‑instansen
    psdImage.Save(outputPsd);
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


