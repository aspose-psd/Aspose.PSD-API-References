---
title: "TimeLine.InitializeFrom"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TimeLine-Methode. Erstellt eine neue Instanz von TimeLine, initialisiert aus dem Eingabe‑PsdImage"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
{{< psd/tize >}}
## TimeLine.InitializeFrom method

Erstellt die neue Instanz von [`TimeLine`](../), initialisiert aus dem Eingabe‑[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdImage | PsdImage | Das psd‑Bild. |

### Rückgabewert

Die neue Instanz von [`TimeLine`](../), initialisiert aus dem Eingabe‑[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

## Beispiele

Die TimeLine‑Klasse bietet eine hochrangige Möglichkeit, die Timeline von PsdImage zu manipulieren, z. B. die Bildverzögerung zu ändern oder den Layer‑Zustand in einem bestimmten Bild zu bearbeiten.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Ändere die Dispose-Methode von Frame 1
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ändere die Verzögerung von Frame 2
    timeLine.Frames[1].Delay = 15;

    // Ändere die Deckkraft von 'Layer 1' in Frame 2
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // Verschiebe 'Layer 1' in die linke untere Ecke in Frame 3
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Fügt einen neuen Frame hinzu
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // Ändere den blendMode von 'Layer 1' in Frame 4
    LayerState layerState31 = timeLine.Frames[3].LayerStates[timeLine.LayerIds[1]];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Änderungen zurück auf die PsdImage-Instanz anwenden
    timeLine.ApplyTo(psdImage);
    psdImage.Save(outputPsd);
}
```

### Siehe auch

* class [PsdImage](../../../aspose.psd.fileformats.psd/psdimage/)
* class [TimeLine](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* assembly [Aspose.PSD](../../../)


