---
title: TimeLine.ApplyTo
second_title: Aspose.PSD voor .NET API-referentie
description: TimeLine methode. Actuele tijdlijnwaarden toepassen op invoerPsdImage .
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/timeline/applyto/
---
## TimeLine.ApplyTo method

Actuele tijdlijnwaarden toepassen op invoer[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public void ApplyTo(PsdImage psdImage)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| psdImage | PsdImage | De psd-afbeelding. |

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

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* montage [Aspose.PSD](../../../)


