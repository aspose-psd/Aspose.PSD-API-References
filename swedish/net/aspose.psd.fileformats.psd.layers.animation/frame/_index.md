---
title: "Klass Frame"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame klass. Alternativen för tidslinjebildrutesobjektet"
type: docs
weight: 1940
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
{{< psd/tize >}}
## Frame class

Alternativen för tidslinjens bildrutelement.

```csharp
public sealed class Frame
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Frame](frame/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Hämtar eller anger bildrutefördröjningsvärdet i centisekunder. Till exempel innehåller 1 sekund 100 centisekunder. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Hämtar eller anger borttagningsmetoden för bildruta. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Hämtar eller anger bildrute‑id. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; set; } | Hämtar eller anger lagertillstånden för bildruta. |

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


