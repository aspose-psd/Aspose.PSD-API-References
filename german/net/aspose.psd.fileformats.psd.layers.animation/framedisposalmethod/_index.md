---
title: Enum FrameDisposalMethod
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.FrameDisposalMethod opsomming. Die FrameEntsorgungsmethode gibt an ob der aktuelle Frame verworfen werden soll bevor der nächste Frame angezeigt wird. Sie wählen eine Entsorgungsmethode für Animationen mit Hintergrundtransparenz aus um anzugeben ob der aktuelle Frame durch die transparenten Bereiche des nächsten Frames sichtbar ist.
type: docs
weight: 1850
url: /de/net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---
## FrameDisposalMethod enumeration

Die Frame-Entsorgungsmethode gibt an, ob der aktuelle Frame verworfen werden soll, bevor der nächste Frame angezeigt wird. Sie wählen eine Entsorgungsmethode für Animationen mit Hintergrundtransparenz aus, um anzugeben, ob der aktuelle Frame durch die transparenten Bereiche des nächsten Frames sichtbar ist.

```csharp
public enum FrameDisposalMethod
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Automatic | `0` | Legt automatisch eine Entsorgungsmethode für das aktuelle Bild fest und verwirft das aktuelle Bild, wenn das nächste Bild Ebenentransparenz enthält. Bei den meisten Animationen liefert die Option Automatisch (Standard) die gewünschten Ergebnisse. |
| DoNotDispose | `1` | Behält das aktuelle Einzelbild bei, wenn das nächste Einzelbild zur Anzeige hinzugefügt wird. Das aktuelle Einzelbild (und vorangegangene Einzelbilder) können durch transparente Bereiche des nächsten Einzelbilds hindurchscheinen. |
| Dispose | `2` | Verwirft das aktuelle Bild aus der Anzeige, bevor das nächste Bild angezeigt wird. Es wird immer nur ein einzelnes Bild angezeigt (und das aktuelle Bild erscheint nicht durch die transparenten Bereiche des nächsten Bildes). |

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


