---
title: Class LayerState
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState klas. Die Optionen für den Status der Zeitachsenebene.
type: docs
weight: 1860
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
## LayerState class

Die Optionen für den Status der Zeitachsenebene.

```csharp
public sealed class LayerState
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LayerState](layerstate/)(int) | Initialisiert eine neue Instanz von`LayerState` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Ruft den Mischmodus ab oder legt ihn fest. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Ruft den aktivierten Status ab oder legt ihn fest. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Ruft den Fülldeckkraftwert ab oder legt ihn fest. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Ruft den HorizontalFXRf-Wert ab oder legt ihn fest. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Ruft die ID ab oder legt sie fest. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Ruft den Deckkraftwert ab oder legt ihn fest. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Holt oder setzt den Schichtpositionsversatz bezogen auf die tatsächliche Schichtposition. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Ruft die Ebenenstatuseffekte ab. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Ruft den VerticalFXRf-Wert ab oder legt ihn fest. |

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


