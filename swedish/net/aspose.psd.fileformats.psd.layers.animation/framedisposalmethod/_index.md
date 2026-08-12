---
title: "Enum FrameDisposalMethod"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod enum. Bildrutes borttagningsmetod specificerar om den aktuella bildrutan ska kasseras innan nästa bildruta visas. Du väljer en borttagningsmetod för animationer som inkluderar bakgrundstransparens för att ange om den aktuella bildrutan kommer att vara synlig genom de transparenta områdena i nästa bildruta."
type: docs
weight: 1950
url: /sv/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

Metoden för bildrutes borttagning specificerar om den aktuella bildrutan ska kasseras innan nästa bildruta visas. Du väljer en borttagningsmetod för animationer som inkluderar bakgrundstransparens för att ange om den aktuella bildrutan kommer att vara synlig genom de transparenta områdena i nästa bildruta.

```csharp
public enum FrameDisposalMethod
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Automatic | `0` | Bestämmer en borttagningsmetod för den aktuella ramen automatiskt och kastar bort den aktuella ramen om nästa ram innehåller lagrets transparens. För de flesta animationer ger alternativet Automatisk (standard) önskat resultat. |
| DoNotDispose | `1` | Bevarar den aktuella ramen när nästa ram läggs till på displayen. Den aktuella ramen (och föregående ramar) kan synas genom transparenta områden i nästa ram. |
| Dispose | `2` | Kastar bort den aktuella ramen från displayen innan nästa ram visas. Endast en enda ram visas åt gången (och den aktuella ramen visas inte genom de transparenta områdena i nästa ram). |

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


