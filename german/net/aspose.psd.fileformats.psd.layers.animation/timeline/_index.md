---
title: Class TimeLine
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.TimeLine klas. Das Zeitlinienoptionsmodell.
type: docs
weight: 1880
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/
---
## TimeLine class

Das Zeitlinienoptionsmodell.

```csharp
public sealed class TimeLine
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TimeLine](timeline/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActiveFrame](../../aspose.psd.fileformats.psd.layers.animation/timeline/activeframe/) { get; set; } | Ruft den Index des aktiven Frames ab oder setzt ihn. |
| [AFSt](../../aspose.psd.fileformats.psd.layers.animation/timeline/afst/) { get; set; } | Ruft den AFSt-Wert ab oder setzt ihn. |
| [Frames](../../aspose.psd.fileformats.psd.layers.animation/timeline/frames/) { get; set; } | Ruft die Liste der Frames ab. |
| [FsID](../../aspose.psd.fileformats.psd.layers.animation/timeline/fsid/) { get; set; } | Ruft den FsID-Wert ab oder legt ihn fest. |
| [LayerIds](../../aspose.psd.fileformats.psd.layers.animation/timeline/layerids/) { get; set; } | Ruft das Ebenen-ID-Array ab oder legt es fest. |
| [LoopesCount](../../aspose.psd.fileformats.psd.layers.animation/timeline/loopescount/) { get; set; } | Ruft die Anzahl der Schleifen ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [InitializeFrom](../../aspose.psd.fileformats.psd.layers.animation/timeline/initializefrom/)(PsdImage) | Erstellt die neue Instanz von`TimeLine` , initialisiert von der Eingabe[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |
| [ApplyTo](../../aspose.psd.fileformats.psd.layers.animation/timeline/applyto/)(PsdImage) | Wende aktuelle Zeitlinienwerte auf die Eingabe an[`PsdImage`](../../aspose.psd.fileformats.psd/psdimage/) . |

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

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* Montage [Aspose.PSD](../../)


