---
title: Class LayerState
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState klas. De opties voor de status van de tijdlijnlaag.
type: docs
weight: 1860
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

De opties voor de status van de tijdlijnlaag.

```csharp
public sealed class LayerState
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LayerState](layerstate/)(int) | Initialiseert een nieuw exemplaar van het`LayerState` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Krijgt of stelt de blen-modus in. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Krijgt of stelt de ingeschakelde status in. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Haalt of stelt de vuldekkingswaarde in. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Haalt de waarde van HorizontalFXRf op of stelt deze in. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Haalt of stelt de id in. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Haalt de dekkingswaarde op of stelt deze in. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Haalt de offset van de laagpositie op of stelt deze in gerelateerd aan de daadwerkelijke laagpositie. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Krijgt de laagstatuseffecten. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Haalt de VerticalFXRf-waarde op of stelt deze in. |

### Voorbeelden

De klasse TimeLine biedt een mogelijkheid op hoog niveau om de tijdlijn van PsdImage te manipuleren, zoals het wijzigen van framevertraging of het bewerken van de laagstatus op een specifiek frame.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Wijzig de verwijderingsmethode van frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Wijzig de vertraging van frame 2
    timeLine.Frames[1].Delay = 15;

    // Wijzig de dekking van 'Laag 1' op frame 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // verplaats 'Laag 1' naar de linkerbenedenhoek van frame 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Voegt een nieuw frame toe
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Wijzig blendMode van 'Laag 1' op frame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Wijzigingen terug toepassen op PsdImage-instantie
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* montage [Aspose.PSD](../../)


