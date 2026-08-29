---
title: "LayerState.BlendMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerState-Eigenschaft. Gibt den Mischmodus zurück oder legt ihn fest"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.animation/layerstate/blendmode/
---
{{< psd/tize >}}
## LayerState.BlendMode property

Liefert oder setzt den Mischmodus.

```csharp
public BlendMode BlendMode { get; set; }
```

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [LayerState](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


