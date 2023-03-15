---
title: Class Frame
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.Frame klas. Die Optionen des Zeitlinienrahmenelements.
type: docs
weight: 1840
url: /de/net/aspose.psd.fileformats.psd.layers.animation/frame/
---
## Frame class

Die Optionen des Zeitlinienrahmenelements.

```csharp
public sealed class Frame
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Frame](frame/)(TimeLine) | Initialisiert eine neue Instanz von`Frame` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Delay](../../aspose.psd.fileformats.psd.layers.animation/frame/delay/) { get; set; } | Ruft den Frame-Verzögerungswert in Centa-Sekunden ab oder legt ihn fest. Beispielsweise enthält 1 Sekunde 100 Centa-Sekunden. |
| [DisposalMethod](../../aspose.psd.fileformats.psd.layers.animation/frame/disposalmethod/) { get; set; } | Ruft die Entsorgungsmethode des Frames ab oder legt sie fest. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/frame/id/) { get; set; } | Ruft die Frame-ID ab oder setzt sie. |
| [LayerStates](../../aspose.psd.fileformats.psd.layers.animation/frame/layerstates/) { get; } | Ruft ab oder legt die Ebenenzustände des Frames fest. |

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


