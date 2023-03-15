---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod opsomming. De verwijderingsmethode voor frames geeft aan of het huidige frame moet worden weggegooid voordat het volgende frame wordt weergegeven. U selecteert een verwijderingsmethode voor animaties die achtergrondtransparantie bevatten om op te geven of het huidige frame zichtbaar zal zijn door de transparante gebieden van het volgende frame.
type: docs
weight: 1850
url: /nl/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

De verwijderingsmethode voor frames geeft aan of het huidige frame moet worden weggegooid voordat het volgende frame wordt weergegeven. U selecteert een verwijderingsmethode voor animaties die achtergrondtransparantie bevatten om op te geven of het huidige -frame zichtbaar zal zijn door de transparante gebieden van het volgende frame.

```csharp
public enum FrameDisposalMethod
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Automatic | `0` | Bepaalt automatisch een verwijderingsmethode voor het huidige frame, waarbij het huidige frame wordt weggegooid als het volgende frame laagtransparantie bevat. Voor de meeste animaties levert de optie Automatisch (standaard) de gewenste resultaten op. |
| DoNotDispose | `1` | Behoudt het huidige frame terwijl het volgende frame aan het scherm wordt toegevoegd. Het huidige frame (en voorgaande frames) kan zichtbaar zijn door transparante gebieden van het volgende frame. |
| Dispose | `2` | Verwijdert het huidige frame van het scherm voordat het volgende frame wordt weergegeven. Er wordt altijd slechts één frame weergegeven (en het huidige frame verschijnt niet door de transparante gebieden van het volgende frame). |

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


