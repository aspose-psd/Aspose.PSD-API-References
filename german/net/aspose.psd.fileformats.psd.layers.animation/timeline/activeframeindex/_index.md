---
title: "Timeline.ActiveFrameIndex"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Timeline-Eigenschaft. Gibt den aktiven Frame-Index zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.animation/timeline/activeframeindex/
---
{{< psd/tize >}}
## Timeline.ActiveFrameIndex property

Ruft den Index des aktiven Frames ab.

```csharp
public int ActiveFrameIndex { get; }
```

## Beispiele

Der folgende Code demonstriert einen neuen Ansatz zur Arbeit mit der Timeline.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputFile = "output_edited.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    Timeline timeline = psdImage.Timeline;
    
    // Ein weiteres Bild hinzufügen
    List<Frame> frames = new List<Frame>(timeline.Frames);
    frames.Add(new Frame());
    timeline.Frames = frames.ToArray();

    timeline.SwitchActiveFrame(4);

    psdImage.Save(outputFile);
}
```

### Siehe auch

* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


