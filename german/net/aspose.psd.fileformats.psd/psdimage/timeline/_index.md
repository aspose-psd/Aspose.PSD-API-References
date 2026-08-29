---
title: "PsdImage.Timeline"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Eigenschaft. Gibt die Timeline dieses PsdImage zurück"
type: docs
weight: 250
url: /de/net/aspose.psd.fileformats.psd/psdimage/timeline/
---
{{< psd/tize >}}
## PsdImage.Timeline property

Gibt die `Timeline` dieses [`PsdImage`](../) zurück.

```csharp
public Timeline Timeline { get; }
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

* class [Timeline](../../../aspose.psd.fileformats.psd.layers.animation/timeline/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


