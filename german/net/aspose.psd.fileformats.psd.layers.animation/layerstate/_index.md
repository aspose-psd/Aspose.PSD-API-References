---
title: "Klasse LayerState"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Animation.LayerState Klasse. Die Optionen des Zeitleisten-Layer-Zustands"
type: docs
weight: 1960
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstate/
---
{{< psd/tize >}}
## LayerState class

Die Optionen des Zeitlinien-Layer-Zustands.

```csharp
public sealed class LayerState
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LayerState](layerstate/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/) { get; set; } | Liefert oder setzt den Mischmodus. |
| [Enabled](../../aspose.psd.fileformats.psd.layers.animation/layerstate/enabled/) { get; set; } | Liest oder setzt den aktivierten Zustand. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/fillopacity/) { get; set; } | Liest oder setzt den Füllungs-Opazitätswert. |
| [HorizontalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/horizontalfxrf/) { get; set; } | Liest oder setzt den HorizontalFXRf-Wert. |
| [Id](../../aspose.psd.fileformats.psd.layers.animation/layerstate/id/) { get; set; } | Liest oder setzt die Layer-ID. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.animation/layerstate/opacity/) { get; set; } | Liest oder setzt den Opazitätswert. |
| [PositionOffset](../../aspose.psd.fileformats.psd.layers.animation/layerstate/positionoffset/) { get; set; } | Liest oder setzt den Positionsversatz des Layers in Bezug auf die tatsächliche Layer-Position. |
| [StateEffects](../../aspose.psd.fileformats.psd.layers.animation/layerstate/stateeffects/) { get; } | Liest die Layer-Zustandseffekte. |
| [VerticalFXRf](../../aspose.psd.fileformats.psd.layers.animation/layerstate/verticalfxrf/) { get; set; } | Liest oder setzt den VerticalFXRf-Wert. |

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


