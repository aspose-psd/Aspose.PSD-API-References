---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod uppräkning. Metoden för bortskaffande av ram anger om den aktuella bildrutan ska kasseras innan nästa bildruta visas. Du väljer en kasseringsmetod för animeringar som inkluderar bakgrundsgenomskinlighet för att ange om den aktuella ramen ska vara synlig genom de transparenta områdena i nästa bildruta.
type: docs
weight: 1850
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Metoden för bortskaffande av ram anger om den aktuella bildrutan ska kasseras innan nästa bildruta visas. Du väljer en kasseringsmetod för animeringar som inkluderar bakgrundsgenomskinlighet för att ange om den aktuella -ramen ska vara synlig genom de transparenta områdena i nästa bildruta.

```csharp
public enum FrameDisposalMethod
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Automatic | `0` | Bestämmer automatiskt en bortskaffningsmetod för den aktuella bilden och kasserar den aktuella ramen om nästa bildruta innehåller lagertransparens. För de flesta animeringar ger alternativet Automatisk (standard) de önskade resultaten. |
| DoNotDispose | `1` | Bevarar den aktuella bildrutan när nästa bildruta läggs till på skärmen. Den aktuella bildrutan (och föregående bildrutor) kan visas genom genomskinliga områden i nästa bildruta. |
| Dispose | `2` | Förkastar den aktuella bildrutan från displayen innan nästa bildruta visas. Endast en enda bildruta visas när som helst (och den aktuella bildrutan visas inte genom de genomskinliga områdena i nästa bildruta). |

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


