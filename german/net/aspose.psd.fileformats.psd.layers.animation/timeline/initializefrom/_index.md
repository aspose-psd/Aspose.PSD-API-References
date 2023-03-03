---
title: TimeLine.InitializeFrom
second_title: Aspose.PSD für .NET-API-Referenz
description: TimeLine methode. Erstellt die neue Instanz vonTimeLine  initialisiert von der EingabePsdImage .
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/
---
## TimeLine.InitializeFrom method

Erstellt die neue Instanz von[`TimeLine`](../) , initialisiert von der Eingabe[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/) .

```csharp
public static TimeLine InitializeFrom(PsdImage psdImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| psdImage | PsdImage | Das psd-Bild. |

### Rückgabewert

Die neue Instanz von[`TimeLine`](../) , initialisiert von der Eingabe[`PsdImage`](../../../aspose.psd.fileformats.psd/psdimage/).

### Beispiele

Die TimeLine-Klasse bietet eine allgemeine Möglichkeit, die Zeitleiste von PsdImage zu manipulieren, z. B. das Ändern der Frame-Verzögerung oder das Bearbeiten des Ebenenstatus auf einem bestimmten Frame.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    TimeLine timeLine = TimeLine.InitializeFrom(psdImage);

    // Löschmethode von Frame 1 ändern
    timeLine.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Verzögerung von Frame 2 ändern
    timeLine.Frames[1].Delay = 15;

    // Deckkraft von 'Layer 1' auf Frame 2 ändern
    LayerState layerState11 = timeLine.Frames[1].LayerStates[timeLine.LayerIds[1]];
    layerState11.Opacity = 50;

    // 'Layer 1' in die linke untere Ecke von Frame 3 verschieben
    LayerState layerState21 = timeLine.Frames[2].LayerStates[timeLine.LayerIds[1]];
    layerState21.PositionOffset = new Point(-50, 230);

    // Fügt einen neuen Rahmen hinzu
    List<Frame> frames = new List<Frame>(timeLine.Frames);
    frames.Add(new Frame(timeLine));
    timeLine.Frames = frames.ToArray();

    // BlendMode von 'Layer 1' auf Frame 4 ändern
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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../timeline/)
* Montage [Aspose.PSD](../../../)


