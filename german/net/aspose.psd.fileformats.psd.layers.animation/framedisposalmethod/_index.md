---
title: "Enum FrameDisposalMethod"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod Enum. Die Frame-Entsorgungsmethode gibt an, ob der aktuelle Frame verworfen werden soll, bevor der nächste Frame angezeigt wird. Sie wählen eine Entsorgungsmethode für Animationen mit Hintergrundtransparenz, um festzulegen, ob der aktuelle Frame durch die transparenten Bereiche des nächsten Frames sichtbar sein wird."
type: docs
weight: 1950
url: /de/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
{{< psd/tize >}}
## FrameDisposalMethod enumeration

Die Frame-Entsorgungsmethode gibt an, ob das aktuelle Frame verworfen werden soll, bevor das nächste Frame angezeigt wird. Sie wählen eine Entsorgungsmethode für Animationen mit Hintergrundtransparenz, um festzulegen, ob das aktuelle Frame durch die transparenten Bereiche des nächsten Frames sichtbar sein wird.

```csharp
public enum FrameDisposalMethod
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Automatic | `0` | Bestimmt automatisch eine Entsorgungsmethode für den aktuellen Frame und verwirft den aktuellen Frame, wenn der nächste Frame Ebenentransparenz enthält. Für die meisten Animationen liefert die Option Automatisch (Standard) das gewünschte Ergebnis. |
| DoNotDispose | `1` | Behält den aktuellen Frame bei, wenn der nächste Frame zur Anzeige hinzugefügt wird. Der aktuelle Frame (und vorherige Frames) kann durch transparente Bereiche des nächsten Frames sichtbar werden. |
| Dispose | `2` | Verwirft den aktuellen Frame aus der Anzeige, bevor der nächste Frame angezeigt wird. Es wird jederzeit nur ein einzelner Frame angezeigt (und der aktuelle Frame erscheint nicht durch die transparenten Bereiche des nächsten Frames). |

## Beispiele

Die Timeline-Klasse bietet eine hochrangige Möglichkeit, die Timeline von PsdImage zu manipulieren, z. B. das Ändern der Frame-Verzögerung oder das Bearbeiten des Layer-Status in einem bestimmten Frame.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image800.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;

    // Ändere die Dispose-Methode von Frame 1
    timeline.Frames[0].DisposalMethod = FrameDisposalMethod.DoNotDispose;

    // Ändere die Verzögerung von Frame 2
    timeline.Frames[1].Delay = 15;

    // Ändere die Deckkraft von 'Layer 1' in Frame 2
    LayerState layerState11 = timeline.Frames[1].LayerStates[1];
    layerState11.Opacity = 50;

    // Verschiebe 'Layer 1' in die linke untere Ecke in Frame 3
    LayerState layerState21 = timeline.Frames[2].LayerStates[1];
    layerState21.PositionOffset = new Point(-50, 230);

    // Fügt einen neuen Frame hinzu
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    // Ändere den blendMode von 'Layer 1' in Frame 4
    LayerState layerState31 = timeline.Frames[3].LayerStates[1];
    layerState31.BlendMode = BlendMode.Dissolve;

    // Änderungen zurück auf die PsdImage-Instanz anwenden
    psdImage.Save(outputPsd);
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../)


